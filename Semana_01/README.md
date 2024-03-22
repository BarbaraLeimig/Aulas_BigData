# Projeto de Criacao do Ambiente Virtual Python

## Passo a passo
- Acessar o ambiente **command prompt** do terminal do VsCode
- Criar o ambiente virtual do Python: python -m venv venv
- Ativar o ambiente virtual: .\venv\Scripts\activate
- Criar um arquivo README.md para documentar o seu projeto
- Criar um arquivo .gitignore e passar dentro dele a pasta venv: venv/
- Criar um arquivo requirements.txt
- Crie um arquivo chamado aula01.ipynb
- Instalar a biblioteca pandas: pip install pandas
- Adicione pandas ao arquivo requeriments.txt
- No arquivo aula01.ipynb, ative o ambiente virtual: Select Kernel > Python Environment > venv
- Importe o pandas como pd
- Crie a variável url = "https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/stuff/titanic.csv"
- Carregue o conjunto de dados da url com o método read_csv do pandas em uma variável chamada data.
