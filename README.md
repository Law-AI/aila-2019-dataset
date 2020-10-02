# aila-2019-dataset
Available for download at https://zenodo.org/record/4063986#.X3dBUMIzbX4

# Dataset of the AILA (Artificial Intelligence for Legal Assistance) Track at FIRE 2019

Track website : https://sites.google.com/view/fire-2019-aila/

Conference website : http://fire.irsi.res.in/fire/2019/home

In countries following the Common Law system (e.g., UK, USA, Canada, Australia, India), there are two primary sources of law – Statutes (established laws) and Precedents (prior cases). Statutes deal with applying legal principles to a situation (facts / scenario / circumstances which lead to filing the case). Precedents or prior cases help a lawyer understand how the Court has dealt with similar scenarios in the past, and prepare the legal reasoning accordingly.

When a lawyer is presented with a situation (that will potentially lead to filing of a case), it will be very beneficial to him/her if there is an automatic system that identifies a set of related prior cases involving similar situations as well as statutes/acts that can be most suited to the purpose in the given situation. Such a system shall not only help a lawyer but also benefit a common man, in a way of getting a preliminary understanding, even before he/she approaches a lawyer. It shall assist him/her in identifying where his/her legal problem fits, what legal actions he/she can proceed with (through statutes) and what were the outcomes of similar cases (through precedents).

Motivated by the above scenario, we propose two tasks here :

Task 1 : Identifying relevant prior cases for a given situation

Task 2 : Identifying most relevant statutes for a given situation
 

# Task Description:

You will be given a set of 50 queries, each of which describes a situation.

## Task 1: Identifying relevant prior cases

We provide ~3000 case documents of cases that were judged in the Supreme Court of India. For each query, the task is to retrieve the most similar / relevant case document with respect to the situation in the given query.

## Task 2: Identifying relevant statutes

We have identified a set of 197 statutes (Sections of Acts) from Indian law, that are relevant to some of the queries. We provide the title and description of these statutes. For each query, the task is to identify the most relevant statutes (from among the 197 statutes). Note that, the task can be modelled either as an unsupervised retrieval task (where you search for relevant statues) or as a supervised classification task (e.g., trying to predict for each statute whether it is relevant). For the latter, case documents provided for Task 1 can be utilised. However, if a team wishes to apply supervised models, then it is their responsibility to create the necessary training data.
