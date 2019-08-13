# Homebrew-AlternativeVersions


Alternative formulas for Homebrew


**1. apache-opennlp.rb**

openNLP version 1.5.3 (fully compatible with the openNLP package in R).

*To train a dataset*

``` 
opennlp TokenNameFinderTrainer -model test_model.bin -lang en -data test_lines_opennlp.train.txt -encoding UTF-8 
```
