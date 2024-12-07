Este projeto é uma ferramenta de web scraping desenvolvida em Python que coleta informações de produtos, como nomes e preços, do site da Nova Líder Informática e salva os dados em uma planilha Excel.

# Objetivo
Automatizar a extração de informações sobre computadores disponíveis no site da Nova Líder Informática, gerando uma planilha com os detalhes dos produtos, como nome e preço.

# Tecnologias Utilizadas
Python

Selenium: Automação de navegadores para acessar e coletar os dados.

OpenPyXL: Manipulação e criação de planilhas Excel.

Google Chrome e ChromeDriver: Para acessar e navegar no site.

# Como Funciona

O script utiliza o Selenium para acessar o site da Nova Líder Informática.

Ele coleta os títulos dos produtos (nomes) e os preços exibidos no site.

Os dados coletados são armazenados em uma planilha Excel com duas colunas: Produto e Preço.

A planilha é salva no arquivo produtos.xlsx.
