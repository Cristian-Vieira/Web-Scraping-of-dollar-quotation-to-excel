# Web Scraping da Cotação do Dólar 
 Este código é um exemplo de como fazer Web Scraping da página de resultados do Google para obter a cotação do dólar e salvar estes dados em uma planilha Excel, com a data e hora da consulta.

## Objetivo
 - Automatizar a busca e salvamento da cotação do dólar em uma planilha Excel, você pode adaptar o código para realizar outras pesquisas no Google ou em qualquer outro site.

## Fluxo de ações
 1. Verifica se já **existe** um arquivo Excel com o nome **pré-definido** para o salvamento dos dados. Caso **sim**, segue para o próximo passo; caso **não**, cria um arquivo Excel com o nome pré-definido e segue para o próximo passo.
 2. Acessa a URL do Google **pré-definida**, faz o web scraping da página do Google procurando pela tag que contém a cotação do dólar.
 3. **Obtém** a cotação do **dólar** em uma variável.
 4. Abre a planilha do Excel.
 5. Encontra a próxima linha vazia na planilha.
 6. **Obtém** a data e hora atuais.
 7. **Insere** na primeira célula da linha a data e hora atuais.
 8. **Insere** na segunda célula da linha o valor da cotação do dólar.
 9. Salva a planilha.


## Requisitos
 - Python 3.x
 - Bibliotecas: requests, BeautifulSoup, selenium, openpyxl

## Como usar
 1. Certifique-se de ter o Python 3.x instalado em seu sistema.
 2. Instale as bibliotecas necessárias executando o seguinte comando no terminal:
 ```pip install requests beautifulsoup4 selenium openpyxl```
 3. Faça o download ou clone este repositório.
 4. Navegue até o diretório onde você salvou os arquivos do repositório.
 5. Execute o código usando o seguinte comando:
 ```python Import dolar value.py```
 6. Verifique se o arquivo "cotacao_dolar.xlsx" foi criado ou atualizado com os dados da cotação do dólar.

## Notas
 - Este código usa o Selenium para automatizar o navegador Chrome. Certifique-se de ter o Chrome WebDriver configurado corretamente.
 - A cotação do dólar é obtida a partir da página de resultados do Google. É possível que a estrutura da página ou a classe CSS do elemento da cotação possam mudar no futuro, o que exigirá uma atualização no código.
 -A cotação do valor do dolar ira vir conforme a sua localização e configurações de localização do seu navegador Chrome

#

### Description in English:

# Web Scraping of dollar quotation to excel
 This code is an example of how to web Scraping the Google results page to obtain the dollar rate and save this data in an Excel spreadsheet, with the date and time of the query.

## Objective
 - Automate the search and saving of the dollar exchange rate in an Excel spreadsheet. You can adapt the code to perform other searches on Google or any other website.

## Actions Flow
 1. Check if there is already an Excel file with the predefined name for data storage. If **yes**, proceed to the next step; if **no**, create a new Excel file with the predefined name and proceed to the next step.
 2. Access the predefined Google URL, scrape the Google page to find the tag that contains the dollar exchange rate.
 3. **Retrieve** the dollar exchange rate and store it in a variable.
 4. Open the Excel spreadsheet.
 5. Find the next empty row in the spreadsheet.
 6. **Retrieve** the current date and time.
 7. **Insert** the current date and time in the first cell of the row.
 8. **Insert** the dollar exchange rate value in the second cell of the row.
 9. Save the spreadsheet.

## Requirements
 - Python 3.x
 - Libraries: requests, BeautifulSoup, selenium, openpyxl

## How to Use
 1. Make sure you have Python 3.x installed on your system.
 2. Install the necessary libraries by running the following command in the terminal:
  ```pip install requests beautifulsoup4 selenium openpyxl```
 3. Download or clone this repository.
 4. Navigate to the directory where you saved the repository files.
 5. Run the code using the following command:
 ```python Import dolar value.py```
 6. Check if the "cotacao_dolar.xlsx" file has been created or updated with the dollar exchange rate data.

## Notes
 - This code uses Selenium to automate the Chrome browser. Make sure you have the Chrome WebDriver properly configured.
 - The dollar exchange rate is obtained from the Google search results page. It is possible that the page structure or the CSS class of the exchange rate element may change in the future, requiring an update to the code.
 - The dollar value will vary according to your location and Chrome browser settings.
