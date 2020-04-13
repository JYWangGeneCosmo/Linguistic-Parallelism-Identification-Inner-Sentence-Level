#                                     linguistic-parallelism-identification

In this project, a classifier is trained based on machine learning methods to identify the following 4 types of inner-sentence level parallelism in texts. (A sister project about inter-sentence level parallelism please see: )

• type 1: …A cc B… e.g. Yet every so often, the oath is taken amidst [gathering clouds and raging storms]. (Obama, 2009)

• type 2: …A, B… e.g. Homes have been lost, [jobs shed, businesses shuttered]. (Obama, 2009)

• type 3: …A cc B cc C… e.g. Americans are [generous and strong and decent]… (Bush, 2001)

• type 4: …A, B (,) cc C… e.g. A new national pride will [stir our souls, lift our sights, and heal our divisions]. (Trump, 2017)

* Note: "cc" refers to coordinating words, namely "while (as in conj.)" or part of a paired conjunction, e.g. "not only… but also…"; "either… or…"; A, B, C refer to the parallel elements with similar grammatical structures.

### Description of the files in the repository of linguistic-parallelism-identification

- A Machine Learning Approach to Identify Textual Parallel Structure.pdf: The paper delivers the detailed information about the process, parameter settings, performance and error analysis etc. of developing the automatic parallelism identification method.

- Project_Parallelism_Identification(including developing details).ipynb: Python script (jupyter notebook) for English parallelism identification (including developing details).

- How_to_use_parallelism_identifier.pdf: contains detailed information (guide) about how to use the python script to identify parallelisms for other texts.

- Parallelism_Identifier.zip: contains 2 Python scripts (jupyter notebook) for English parallelism identification (final version) for both Mac and Windows system; Training data (3 American Inaugural Speeches) and test data (2 TED talks).

