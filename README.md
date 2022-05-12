# gro_inteligence_datascience_assignment
Attached to this email is a zip file entitled ‘gro_nlp_homework.zip’ - it contains 4 .csv files


Parameters:

Use Python
Please read the full set of instructions before proceeding
We are unable to provide any further information or assistance on the task beyond this document. Part of the challenge is to complete the task with ONLY the included information.
Unfortunately, we are unable to accept late submissions.

Goal:

Think of this task as a vocabulary matching problem where you match terms of the same meaning. We have two different sources reporting data; source 1 and source 2. The two sources use different methods of assigning names to the commodity terms. We would like you to align these two different data sources;  whenever the same agricultural commodity appears in both sources, match them and represent them as a pair.


The two sources are of different sizes; and thus not all terms have corresponding pairs. You may notice that some terms in source 1 are not expressed in perfect English 

 

Data:

matched_data.csv has 2 columns:
source_1 and source_2. Each row consists of an agricultural term from source_1 and its closest in meaning match from source_2. This serves as an example of matched data. Note that those matching terms are not in the source_1.csv and source_2.csv files described below so they will not appear in your predictions.
source_1.csv has 2 columns: id and name. This file consists of all the term names reported by source 1, and their corresponding id.
source_2.csv has 2 columns: id and name. This file consists of all the term names reported by source 2, and their corresponding id.
predicted_matches.csv has 2 columns: source_1 and source_2.
This file serves as an example of how you should submit your results. Your submission file should only have 2 columns. Each row represents a matched pair from source_1 and source_2 respectively. A matched pair are terms that you define as having similar meaning with high confidence. The pairs are represented by their corresponding ids. Please make sure to submit the pairs by their ids and not their names. 


 

Evaluation criteria:

Your results will be scored on the number of correct matches against a set of ground truth.
Your results should be a one-to-one mapping; one id from one source should not match to more than one id from another source.
Part of the task is to tackle the question with only the information provided - if this requires you to make assumptions, please make those assumptions clear in the Google Colab notebook
We are unable to provide any further information or assistance on the task beyond this document
Spend no more than 7 hours on this.


If you are successful, we will be able to provide you information on the next rounds in the few days following the deadline.

 

Thanks - and best of luck,
