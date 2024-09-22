# AuthorFinderProject
Three problems
were analyzed: if two texts
 are generated by the same NLG, if text is from
 a human, and classify the texts with respect
 to the NLG. We consider some of the Neural
 Language Generation (NLG) models such as
 GPT-3 and try researching different Linguis
tic Features such as POS statistics, stylometric
 features and so on. We used two different BiL
STMarchitectures and two kinds of tokenizers
 as well as compared the results with that of the
 Random Forests. The data is generated from
 10 NLG methods and a human. In conjunc
tion to this we also carried out a Reddit case
 study where we extracted the data from 2 NLG
 methods and a human and experimented with
 the models that we used on the actual set and
 analyzed the results.

 **Introduction**
 With the developments in the field of chatbots
 which could mimic the human language, there’s
 a high ground for the models to be used as part
 of the deep fakes. Thus in this project we have
 analyzed various prior work in order to solve the
 following three questions.
 1. Same or not: Whether the generated text is
 from the same NLG method (human) or not.
 2. Human vs bot: Whether the text is from a
 human or an NLG method.
 3. Which NLGmethod: Whetherthetext is from
 the ith NLG method from a set of k methods


The datasets are available in the Datasets folder. One has to download them and the code files for all the three tasks are also available in the code files folder. There codes available specifically for each balanced as well as the imbalanced dataset for the tasks 1 and 2, in case of 3rd task the files are available but the dataset is made available in the zip format please unzip it before use. Also the see the naming convention for each file.

Naming convention for task 1: task1 + dataset_type(balnaced or imbalance) + model_type(there are 4 models) 

Note: For the task 1 XG Boost methods the naming convention is as follows task1 + XGBoost_balanced_imbalanced

Naming convention for task 2: task2p1 + dataset_type(balnaced or imbalance) + model_type(there are 4 models) 

Naming convention for task 3: task3 + model_type(there are four of them)

Naming convention for reddit task 1: task1 + dataset_type(balnaced or imbalance) + model_type(there are 4 models) + reddit

Note: For the reddit task 1 XG Boost methods the naming convention is as follows task1 + XBBoost + reddit +balanced_imbalanced

Naming convention for task 2: task2p1 + dataset_type(balnaced or imbalance) + model_type(there are 4 models) +reddit

Naming convention for task 3: task3 + model_type(there are four of them) + reddit
