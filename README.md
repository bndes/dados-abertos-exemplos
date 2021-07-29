# Portal de Dados Abertos do BNDES - Exemplos

Códigos de exemplo para uso do [Portal de Dados Abertos do BNDES](https://dadosabertos.bndes.gov.br).

## Exemplos

- [python-exemplo.ipynb](python-exemplo.ipynb) - carrega dados em um Dataframe e exibe um gráfico
- [python-api.ipynb](python-api.ipynb) - usa a api para busca de dados e download
- [python-api-filtros.ipynb](python-api-python-api-filtros.ipynb) - usa a API para filtrar dados. Use para baixar só os dados que precisa e trabalhar com arquivos menores. 

## Executando o código Python 

Todas as bibliotecas utilizadas nos exemplos estão no arquivo [requirements.txt](requirements.txt). Recomenda-se o uso de um ambiente virtual: 
```
python -m venv .venv
# ative com o ambiente virtual para sua plataforma. 
# Eg.: No Windows execute ".\.venv\Scripts\activate"
#      no Unix execute "source ./venv/bin/activate"
pip install -r requirements.txt
```

Então execute o comando `jupyter-lab` para executar os notebooks.
