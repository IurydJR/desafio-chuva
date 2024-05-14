# Desafio chuva inc.
Web Scrapping Project

## Descrição:
Este projeto faz parte do desafio dado pela empresa chuva inc. e consiste em um aplicativo para realizar web scraping em uma página HTML específica, extrair informações sobre artigos acadêmicos e gerar um arquivo XLSX com os dados extraídos.

## Tecnologias Utilizadas:
1. PHP
2. Biblioteca [DOM](https://www.php.net/manual/pt_BR/class.domdocument.php)
3. Biblioteca [Spout](https://opensource.box.com/spout/getting-started/) para PHP

## Estrutura do Projeto:
```bash
- readme.md
- assets/
  - origin.html (arquivo HTML de origem para web scraping)
  - papers.xlsx (arquivo XLSX gerado pelo webscraping)
- src/WebScrapping/
  - Entity/
    - Paper.php (classe que representa um artigo acadêmico)
    - Person.php (classe que representa uma pessoa)
  - Scrapper.php (classe responsável por realizar o web scraping)
  - Spouter.php (classe responsável por gerar o arquivo XLSX)
  - Main.php (classe principal para execução do projeto)
```

## Funcionalidades:
1. Web Scraping:

A classe Scrapper é responsável por realizar o web scraping da página HTML de origem.
Extrai informações sobre artigos acadêmicos, incluindo título, autores, instituições e tipo de apresentação.
Retorna os dados extraídos em formato de array.

2. Geração de Arquivo XLSX:

A classe Spouter é responsável por gerar um arquivo XLSX com os dados extraídos.
Utiliza a biblioteca Spout para PHP para criar e escrever os dados no arquivo XLSX.
Formata as células do arquivo XLSX com estilos específicos.

3. Execução do Projeto:

A classe Main é responsável por orquestrar a execução do projeto.
Carrega a página HTML de origem.
Utiliza a classe Scrapper para realizar o web scraping e extrair os dados.
Utiliza a classe Spouter para gerar o arquivo XLSX com os dados extraídos.

## Uso:
Certifique-se de ter PHP e o Composer instalado em seu ambiente de desenvolvimento.
Instale a biblioteca [Spout](https://opensource.box.com/spout/getting-started/) para PHP utilizando o Composer.
Execute o arquivo Main.php para iniciar o projeto.
```bash
// Executar o projeto
php Main.php
```

## Autores:
Iury Rodrigues [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iury-djr/) [![](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/IurydJR)
