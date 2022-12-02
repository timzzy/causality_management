### Causal Management Architecture
Causality identification and detection framework

###### Thesis Note

System behavior is often expressed by causal relations in requirements (e.g. if event 1 exist, then event 2 exist ). Automatically extracting this embedded causal knowledge supports not only reasoning about requirements dependencies, but also various automated engineering tasks such as seamless derivation of test cases. We understand causality extraction from requirements as a two step problem: First, we need to detect if requirements have causal properties or not, and then we need to understand and extract their causal relations.

############## The package contains the source code of the following two language models, which are the machine learning and dee learning BERT algorithm: 
- Evaluating the performance of the five machine learning algorithms explored in the study. 
- Simulate the impact of the dataset and annotation guidelines on the model performance during categorizion of causal categories

---

## Required Installs

To run the scripts in this, following tools, datasets downloaded from kaggle need to be available. First, advisable that it runs on a GPU, as it stops or hangs when the code is ran on a CPU because of the memory and processor requirements of the of the NL-based dataset:

#1 Install python >= 3.6, and run the command ''' pip install required_installs.txt''' to install the required python packages for the jypyter notebook environment

#2 Download requirement engineering documents from Kaggle using the link https://www.kaggle.com/code/kmader/quickdraw-with-wavenet-classifier and label it as data_explore and put in the datasets folder

#3 Use the cell labelled "cue phrase" in freq_cue_phrase.csv as a guide to what you looking for in every sentence

#4 Use the cell labelled "Cue Phrase" in precision_cue_phrase to estimate the precision for each sentence category 

#5 Install the tool CRF language suite at http://www.chokkan.org/software/crfsuite/installs

#6 Import the coreNLP file in the frameworks folder to call the coreNLP framework from the folder named framework which housed all the downloaded external frameworks used on this project

#Average run time - 40 to 160 minutes depending on computing resources, specifically, a GPU-based processor is recommended

#About 21 (twenty one) python modules specified in the notebooks needs to be installed on the host machine to run the full implementation
