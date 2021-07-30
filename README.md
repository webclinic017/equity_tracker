# equity_tracker

Trabalho de Conclusão de Curso - Escola Politécnica da Universidade de São Paulo.

Equities portfolio based on financial Machine Learning and Genetic Algorithm for Portfolio Optimization.
Not tested/improved for linux environments. We will do this.

## 1. First setup

### 1.1 Clone repository

Open terminal/prompt and navigate to the folder you want to install. Then, run:

`
git clone https://github.com/lucaspenna00/equity_tracker
`

### 1.2 Install dependences

Go to **equity_tracker** repository:

`
cd equity_tracker
`

Then, run:

`
pip install -r requirements.txt
`

### 1.3 SimFin setup and Download CVM Data

The source of data is the CVM (SEC equivalent in brazilian market) data repository and SimFin API. The data can be obtained for free.
There are plenty of fundamentalist data that we are using in this project, such as Income Statements, Cash Flows and Balance Sheets for br and US markets.
Just ensure you have enough space to download the data (approximately 10GB free in hard disk).

e.g.:

`
python install.py 2011 2021
`
