# LMSI_OCDE_ALL_COUNTRIES

Este repositório contém um Jupyter Notebook para a análise automática de sentimentos e cálculo de índices de legibilidade de documentos em PDF, especificamente direcionado para relatórios governamentais de países da OCDE. O notebook extrai o texto dos documentos, realiza uma análise de sentimentos usando o dicionário de sentimentos Loughran-McDonald, e calcula o índice de legibilidade Flesch-Kincaid.

## Funcionalidades

- **Extração de texto**: Extração de texto de arquivos PDF.
- **Análise de sentimentos**: Utilização do dicionário financeiro Loughran-McDonald para avaliar o sentimento do texto.
- **Cálculo de índices de legibilidade**: Utilização da fórmula Flesch-Kincaid Index para avaliar a legibilidade do texto.
- **Exportação de dados**: Os resultados são salvos em uma planilha Excel, organizados por país e documento.

## Pré-requisitos

Antes de executar o notebook, certifique-se de que as seguintes bibliotecas Python estão instaladas:

- nltk
- pandas
- openpyxl
- pdfminer.six
- pyphen

Você pode instalar todas as dependências necessárias usando o seguinte comando:

```bash
pip install nltk pandas openpyxl pdfminer.six pyphen

## Configuração

1.Clone este repositório em seu computador local.
2.Baixe os dados necessários para a análise através do seguinte link do Google Drive: https://drive.google.com/file/d/1OeTzX6oYhgNBBtQc-btyjII01WZSox_L/view
3.Descompacte o arquivo baixado na pasta PAISES_OCDE/ dentro do diretório do projeto.
4.Abra o Jupyter Notebook LMSI_excel.ipynb e execute as células para iniciar a análise.


## Estrutura de Diretórios

/LMSI_OCDE_ALL_COUNTRIES
│
├── PAISES_OCDE/          # Diretório contendo os PDFs para análise
└── LMSI_excel.ipynb     # Jupyter Notebook principal


## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE.md para detalhes.



