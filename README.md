# Homebrew-AlternativeVersions


Alternative formulas for Homebrew


**1. apache-opennlp.rb**

openNLP version 1.5.3 (fully compatible with the openNLP package in R).

*How to update SHA256*

``` 
brew fetch https://raw.githubusercontent.com/cromanpa94/Homebrew-AlternativeVersions/master/apache-opennlp.rb --build-from-source
``` 

Then you get 
``` 
Already downloaded: PATH/Library/Caches/Homebrew/downloads/c33b8b7ac16f8bdfaec4e394c3164f612294264e6a1d2ff04f2f55eae158a69c--apache-opennlp-1.5.3-bin.tar.gz
``` 

Use ```c33b8b7ac16f8bdfaec4e394c3164f612294264e6a1d2ff04f2f55eae158a69c``` to update SHA256.


*To install the package*

``` 
brew install https://raw.githubusercontent.com/cromanpa94/Homebrew-AlternativeVersions/master/apache-opennlp.rb
``` 

*To train a dataset*

``` 
opennlp TokenNameFinderTrainer -model test_model.bin -lang en -data test_lines_opennlp.train.txt -encoding UTF-8 
```
