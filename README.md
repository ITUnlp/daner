# daner
Named Entity Recognition for Danish

Distributed by [ITU NLP](https://nlp.itu.dk)

This tool uses Stanford CoreNLP NER and the model from DKIE to tag incoming Danish plaintext for named entities, in three classes: location, person, and organization names.

To run:

* Download and, if needed, unzip
* In the same directory as the code, where your text is in "textfile", run:
  * `daner <textfile>` (Windows)
  * `./daner <textfile>` (Mac or Linux)

References:
* DKIE - Derczynski et al. (2014). "DKIE: Open Source Information Extraction for Danish". In Proceedings of EACL
* Stanford NER - Jenny Rose Finkel, Trond Grenager, and Christopher Manning. (2005). "Incorporating Non-local Information into Information Extraction Systems by Gibbs Sampling". Proceedings of the 43nd Annual Meeting of the Association for Computational Linguistics (ACL 2005), pp. 363-370.
