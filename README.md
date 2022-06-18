# Automatically assesing social disclosure from CSR reports

This repo contains our work as part of the course FIN-407 Financial Econometrics at EPFL. The project aims to automatically asses the level of social disclosures from CSR reports. We achieve this by fine-tuning a Small BERT transformer to classify setnences as whether they disclose information concerning a social GRI standard or not. Furthermore, we use these scores to build social scores for companies and use these scores in a panel data regression to assess whether social score impacts financial performance. More information can be found in our report named report.pdf in this repo, but we include the abstract here for simplicity:

### Abstract
During the last decade, the interest in Environmental Social and Governance (ESG) scores and rankings have skyrocketed. Investors, policymakers, and the public are concerned with how companies deal with the climate, their employees, and society as a whole. Concurrently, Deep Learning and Natural Language Processing (NLP) have undergone a revolution thanks to increased processing power, data availability, and recently more advanced algorithms. In this paper, we combine the two by automatically assessing the level of social disclosure in sustainability reports. We achieve this by fine-tuning a SmallBERT transformer on classifying a sentence as either social disclosure or not according to the GRI standards. In the end, we achieve an accuracy of 95% and an F1-score of 95%. Furthermore, we use the sentence scores to build company social scores for 89 companies on the S&P 500. The company scores are then used in a panel data regression to determine social scores' impact on financial performance. We find no statistically significant relationship between social scores and companies' excess return over the S&P 500 index.


### Instructions
To reproduce the experiments conducted in this project follow the following instructions:

#### BERT Model
- Upload the file `bert_train.ipynb` to Google Colab and run all cells

#### Social scoring
- Download the reports we ran the model on from: https://drive.google.com/drive/folders/1Bwvb1J25A0O3Jt_nRisnED-FnX-bVxBR?usp=sharing and place the reports folder in this repo
- If you want to run the model on more reports, please place them in the reports folder from the previous step
- Upload the file to Google Colab and run all cells

#### Financial model
- Run the file panel_data.ipynb


Authors:
- Benjamin Rike
- Asbjørn Nisi
