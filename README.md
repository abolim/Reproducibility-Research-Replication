# Replication of Comparative Studies of Detecting Abusive Language on Twitter
Repository for the project on research paper replication in WI 2020 Data Reproducibility course

CONTRIBUTORS

1. [Aboli Moroney](https://github.com/abolim "Aboli's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0003-1226-3185" href="https://orcid.org/0000-0003-1226-3185" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

2. [Mayank Goel](https://github.com/mickkygoel "Mayank's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0002-2458-910X" href="https://orcid.org/0000-0002-2458-910X" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

3. [Harini Ram Prasad](https://github.com/hariniramp "Harini's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0001-5419-8030" href="https://orcid.org/0000-0001-5419-8030" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

4. [Samarth Modi](https://github.com/samarthjmodi "Samarth's Github page") <a itemprop="sameAs" content="https://orcid.org/0000-0003-0681-231X" href="https://orcid.org/0000-0003-0681-231X" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

CONTENTS

Lately, there has been a lot of effort and research on identifying content that is abusive or offensive on online and social media. Twitter recently published a relatively large and reliable dataset on ‘Hate and Abusive Speech on Twitter’. As Data Scientists, we fully understand the need to find the best methods and data for identifying such content and flagging it as inappropriate.
 
In this repository, our aim is to reproduce some of the findings in a research paper that performs a comparative study and provides suggestions for using additional features and data for improving such classification of hate and abusive speech using Twitter data.
Using the data and code provided by the authors, we aim to replicate the efficacy and accuracy of machine learning models such as Naive Bayes, Logistic Regression, SVM and Random Forest presented in this paper. Our ultimate goal is to understand how each of these techniques performs on the different types of classifications and generate identical results for precision, recall and F1 score as reported by the authors. The choice of models to reproduce is based on the observation that the top precision has been generated by some of these models as well as our experimental constraints for executing the code.

Citation: Lee, Y., Yoon, S., & Jung, K. (2018). Comparative studies of detecting abusive language on twitter. arXiv preprint arXiv:1808.10245.

URL: https://arxiv.org/abs/1808.10245

Git Repository: https://github.com/younggns/comparative-abusive-lang/blob/master/README.md

DATA
 
The link to the exact data used in the research is mentioned in the GitHub page by the authors.
The data itself is hosted in another GitHub repository called hatespeech-twitter managed by ENCASE (The organization for the ENCASE (ENhancing seCurity and privAcy in the Social wEb) Horizon 2020 European Research Programme). Following is the link to the repository hosting the data: https://github.com/ENCASEH2020/hatespeech-twitter

The data is present in the csv format, in the file titled hatespeech_labels.csv.
The file contains Tweet IDs of ~100k tweets used in training and testing the models. These IDs should be sufficient to extract all the data that we need to reproduce the research work.
 
Additionally, the owners of the data are open to sharing the full extracted data file upon request via email. In case we are unable to extract the tweets using the available data file, we will try reaching the data owners at their provided email ID (a.m.founta@gmail.com).

