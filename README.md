# LMSI_OCDE_ALL_COUNTRIES

Este repositório contém um conjunto de códigos, elaborados no Jupyter Notebook, para a análise automática de indicadoree de sentimentos e cálculo de índices de legibilidade das minutas de decisões de política monetária de um conjunto de Bancos Centrais dos países da OCDE. O notebook extrai o texto dos documentos em PDF, realiza uma análise de sentimentos usando o dicionário de sentimentos Loughran-McDonald, e calcula o índice de legibilidade Flesch-Kincaid, agrupando os resultados em um único arquivo Excel. 

## Funcionalidades


- **Análise de sentimentos**: Utilização do dicionário financeiro Loughran-McDonald para avaliar o sentimento do texto.
- **Cálculo de índices de legibilidade**: Utilização da fórmula Flesch-Kincaid Index para avaliar a legibilidade do texto.
- **Exportação de dados**: Os resultados são salvos em uma planilha Excel, organizados por país e data

## Pré-requisitos

Antes de executar o notebook, certifique-se de que as seguintes bibliotecas Python estão instaladas:

- nltk
- pandas
- openpyxl
- pdfminer.six
- pyphen

Você pode instalar todas as dependências necessárias usando o seguinte comando:


pip install nltk pandas openpyxl pdfminer.six pyphen

## Configuração

1.Clone este repositório em seu computador local.

2.Baixe os PDFS das minutas de decisões monetárias dos países da OCDE a serem analisados através do seguinte link do Google Drive: https://drive.google.com/file/d/1OeTzX6oYhgNBBtQc-btyjII01WZSox_L/view

3.Descompacte o arquivo baixado na pasta PAISES_OCDE/ dentro do diretório do projeto.

4.Abra o Jupyter Notebook LMSI_excel.ipynb e execute as células para iniciar a análise.


## Estrutura de Diretórios
```
/LMSI_OCDE_ALL_COUNTRIES
│
├── PAISES_OCDE/          # Diretório contendo os PDFs para análise
└── LMSI_excel.ipynb     # Jupyter Notebook principal

```

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.

## Autoria e financiamento

Esse código foi elaborado no âmbito do Grupo de Pesquisa de Comunicação das Autoridades e Instituições Econômicas, da Universidade Católica de Petrópolis, com financiamento, via bolsa de iniciação científica, pelo CNPq. Os autores deste trabalho são:

Flávio Motta - Aluno do curso de bacharelado em Administração da Univerisdade Católica de Petrólis e Bolsista de Iniciação Científica do CNPq.

Rodolfo Nicolay - Professor do Mestrado Profissional em Gestão de Projetos em Engenharia da Universidade Católica de Petrópolis e Coordenador do grupo de pesquisa. 

Matheus Alvim - Aluno do curso de bacharelado em Economia e pesquisador voluntário do grupo de pesquisa. 

