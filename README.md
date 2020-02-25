# Cancer-Prognosis-using-NLP
## Advisor: Dr. Mayank Singh, Indian Insitute of Technology Gandhinagar
## Natural Language Processing course project

### Introduction
* In this project we have tried to address the problem of delay in the cancer prognosis by exploiting the abundant information available in the Electronic Health Records(EHRs).
* [CliNER](http://text-machine.cs.uml.edu/cliner/)(Clinical Named Entitiy Recognition) has been used to extract sentences that pertaining to symptoms, treatments and tests as EHRs contain a lot information that may be not useful such as doctor name, admission date etc.
* [Bio-BERT](https://github.com/dmis-lab/biobert) an bio-specific BERT(Bidirectional Encoder Representations from Transformers) has been employed to get sentence embeddings to be used in machine learning techniques for prediction of probability of cancer.

### Dataset
* We have extracted the EHRs from the [MIMIC-III](https://alpha.physionet.org/content/mimiciii/1.4/)(Medical Information Mart for In- tensive Care III) dataset. The dataset has restricted access and therefore, the outputs from CliNER has not been made public.

### References
* William Boag, Kevin Wacome, Tristan Naumann, and Anna Rumshisky. 2015. Cliner: a lightweight tool for clinical named entity recognition. AMIA Joint Summits on Clinical Research Informatics (poster).
* Jinhyuk Lee, Wonjin Yoon, Sungdong Kim, Donghyeon Kim, Sunkyu Kim, Chan Ho So, and Jaewoo Kang. 2019. BioBERT: a pre-trained biomedical language representation model for biomedical text mining. Bioinformatics.
* Alistair EW Johnson, Tom J Pollard, Lu Shen, H Lehman Li-wei, Mengling Feng, Moham- mad Ghassemi, Benjamin Moody, Peter Szolovits, Leo Anthony Celi, and Roger G Mark. 2016. Mimic- iii, a freely accessible critical care database. Scien- tific data, 3:160035.
