# Automatically assesing social disclosure from CSR reports

This repo contains our work as part of the course FIN-407 Financial Econometrics at EPFL. The project aims to automatically asses the level of social disclosures from CSR reports. We achieve this by fine-tuning a Small BERT transformer to classify setnences as whether they disclose information concerning a social GRI standard or not. Furthermore, we use these scores to build social scores for companies and use these scores in a panel data regression to assess whether social score impacts financial performance. More information can be found in our report named report.pdf in this repo.

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
