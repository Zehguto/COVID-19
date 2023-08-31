# COVID-19 Deaths and Underlying Diseases Statistics Project

This project aims to analyze statistics related to COVID-19 cases and the illnesses people had together. We will use the Python language and the Jupyter Notebook environment to run the code.
## About Dataset countent:
The dataset was provided by the Mexican government [link](https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico). This dataset contains an enormous number of anonymized patient-related information including pre-conditions. The raw dataset consists of 21 unique features and 1,048,576 unique patients. In the Boolean features, 1 means "yes" and 2 means "no". values as 97 and 99 are missing data.

- sex: 1 for female and 2 for male.
- age: of the patient.
- classification: covid test findings. Values 1-3 mean that the patient was diagnosed with covid in different
- degrees. 4 or higher means that the patient is not a carrier of covid or that the test is inconclusive.
- patient type: type of care the patient received in the unit. 1 for returned home and 2 for hospitalization.
- pneumonia: whether the patient already have air sacs inflammation or not.
- pregnancy: whether the patient is pregnant or not.
- diabetes: whether the patient has diabetes or not.
- copd: Indicates whether the patient has Chronic obstructive pulmonary disease or not.
- asthma: whether the patient has asthma or not.
- inmsupr: whether the patient is immunosuppressed or not.
- hypertension: whether the patient has hypertension or not.
- cardiovascular: whether the patient has heart or blood vessels related disease.
- renal chronic: whether the patient has chronic renal disease or not.
- other disease: whether the patient has other disease or not.
- obesity: whether the patient is obese or not.
- tobacco: whether the patient is a tobacco user.
- usmr: Indicates whether the patient treated medical units of the first, second or third level.
- medical unit: type of institution of the National Health System that provided the care.
- intubed: whether the patient was connected to the ventilator.
- icu: Indicates whether the patient had been admitted to an Intensive Care Unit.
- date died: If the patient died indicate the date of death, and 9999-99-99 otherwise.

## Requirement
Make sure you have Python installed on your computer. We recommend the latest version of Python 3.
## Environment Setting
##### 1 Install Jupyter Notebook by running the following command in your terminal:
```terminal
pip install jupyter
```
##### 2 Then clone the project repository to your computer:
```terminal
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```
##### 3 Access the project directory:
```terminal
cd nome-do-repositorio
```
##### 4 Install the necessary libraries by running the command:

```terminal
pip install pandas matplotlib seaborn
```
## Executing the Code
##### Abra o Jupyter Notebook executando o seguinte comando no diretório do projeto:
```terminal
jupyter notebook
```
In the browser, you will be redirected to the Jupyter Notebook interface. Click on the file-name.ipynb to open it.
Within the Jupyter Notebook, you will be able to run the code cells by pressing Shift + Enter or by clicking the 'Run' button.

## Contribution
Feel free to contribute to this project by opening an issue or submitting a pull request. All collaboration is welcome!



