# Análise da Premier League 2024/2025

Este projeto foi desenvolvido com o objetivo de treinar e aprimorar conhecimentos em Python, focando especialmente em técnicas de web scraping e manipulação de dados. A análise foi realizada utilizando dados da Premier League 2024/2025, extraídos do site [FBref](https://fbref.com).

## 🧠 Objetivo

O projeto surgiu a partir da ideia de um amigo que realiza análises esportivas e solicitou informações específicas sobre a Premier League. O objetivo principal foi coletar, processar e apresentar esses dados de forma estruturada.
O projeto surgiu a partir da ideia de um amigo que realiza análises esportivas e solicitou informações específicas sobre a Premier League. O objetivo principal foi coletar, processar e apresentar a quantidade de gols marcados pelos times em casa e fora.


## 🛠️ Técnicas Utilizadas

- **Web Scraping com Pandas**: Utilização da função `pd.read_html()` para extrair tabelas diretamente das páginas da web do FBref, sem a necessidade de bibliotecas adicionais como BeautifulSoup ou Selenium.

- **Manipulação de Dados com Pandas**: Processamento e limpeza dos dados extraídos para garantir precisão e consistência nas informações apresentadas.

- **Estilização com Pandas Styler**: Aplicação de estilos personalizados às tabelas geradas, incluindo a remoção do índice, para melhorar a apresentação dos dados.

- **Versionamento com Git**: Controle de versão do projeto utilizando Git, com os arquivos armazenados no repositório GitHub [PatriciaFalchi/Analise-Premiere-League](https://github.com/PatriciaFalchi/Analise-Premiere-League).

## 🧑‍💻 Ambiente de Desenvolvimento

O código foi desenvolvido no Visual Studio Code (VS Code), utilizando a extensão oficial do Jupyter para VS Code.

## 📁 Estrutura do Repositório

- `analise.ipynb`: Notebook contendo a primeira versão do código de análise e processamento dos dados.
- `analise_2.ipynb`: Versão final com a análise apresentada em HTML.
- `index.html`: Arquivo HTML gerado com a tabela apresnetando os dados análisados. https://patriciafalchi.github.io/Analise-Premiere-League/
