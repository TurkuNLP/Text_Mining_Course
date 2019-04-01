# Named entity recognition

The performance of basic machine learning-based named entity recognition systems can drop dramatically when they are applied to text from a different genre/domain from their training data. In this project, you will study this effect further and explore ways to improve NER system generalization.

(**Note**: this project is cast in terms of Finnish NER. If you wish to do the project for English NER, get in touch and we'll prepare English resources.)

## Milestone I

The [Turku Dependency treebank](http://bionlp.utu.fi/fintreebank.html) is a Finnish corpus covering multiple text genres (news, blogs, legal text, fiction, etc.) and is already annotated for proper nouns (likely names) and multi-token name spans. However, this annotation does not specifically identify named entities and their types (person, organization, etc.). To allow evaluation on this data, first revise a small subset of the data into full named entity annotation using the [brat annotation tool](http://brat.nlplab.org/). Then, train a basic CRF-based NER system using [FiNER data](https://github.com/mpsilfve/finer-data) (tech news texts) and evaluate it separately on FiNER test data and on your newly annotated data. Report the precision, recall and F-score of the system and provide a brief analysis of system errors.

**Resources**: We will provide the annotation tool, data, and basic NER system.

## Milestone II

The basic NER system learns in part by "memorizing" the specific names occurring in its training data. To help the system perform better on data involving different names, explore the use of additional context and surface features as well as the integration of dictionary data (e.g. names from [WikiData](https://www.wikidata.org/wiki/Wikidata:Main_Page) or [Omorfi lexemes](https://github.com/flammie/omorfi/blob/develop/src/lexemes.tsv)). Evaluate each modification both on the FiNER data and your newly annotated multi-genre data, and provide an analysis of feature weights.

**Resources**: Processed dictionary data will be made available.

## Milestone III

The training data of machine learning systems should cover the genres/domains of text that the system will be applied to. As a step toward making it possible to train Finnish NER systems on a diverse corpus, apply the manual annotation process from Milestone I to a separate, larger subset of the Turku Dependency Treebank. Evaluate your improved NER system separately with training only on FiNER data and training with a combination of this data with your new training data. Report the results in terms of precision, recall and F-score and provide ananalysis of system errors.

**Resources**: We will provide the annotation tool and data.
