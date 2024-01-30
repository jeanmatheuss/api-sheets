# Integração do Python com o Google Sheets para armazenar os valores das ações


## Resumo
Neste projeto usaremos a integração do Python com o Google Sheets, através da API fornecida pelo google. E assim fazer o update diário na planilha do sheets com os valores das ações obtidas pelo Yahoo Finance.

Para isso precisamos:
- Autorizar a API do google;
- Criar uma planilha no sheets;
- Gerenciar e autenticar a conexão da API com o programa;
- Executar o programa.

## Objetivo

O objetivo desse projeto é facilitar/automatizar o processo de armazenar os dados dos valores das principais ações do Brasil e dos Estados Unidos (com maiores volumes de ações) na abertura (open) e no fechamento (close) e o volume de ações no dia da execução do programa.

## Configuração 

1. Clone o repositório para sua máquina local.
```
git clone https://github.com/jeanmatheuss/api-sheets.git
```
2. Configure as credenciais da API do Google no console dos  [desenvolvedores](https://console.cloud.google.com/).

3. Crie uma planilha no google sheets. Como esta:

![sheets](https://github.com/jeanmatheuss/api-sheets/blob/main/imgs/sheets.jpeg?raw=true)

4. Modifique as áreas dentro do programa 'SAMPLE_SPREADSHEET_ID', 'SAMPLE_RANGE_NAME' com as da sua planilha.

5. Execute o [programa](https://github.com/jeanmatheuss/api-sheets/blob/main/program.ipynb) e se caso for o primeiro será necessário autorizar no navegador.

>OBS: Não disponibilize os arquivos 'client_secret.json' e 'token.json'.

>Para mais infos sobre a API do google, este é o [link](https://developers.google.com/sheets/api/quickstart/python?hl=pt-br).


## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.


<details>
<summary>Link utéis</summary>

- https://console.cloud.google.com/ 
- https://developers.google.com/sheets/api/quickstart/python?hl=pt-br 
- https://pypi.org/project/yfinance/ 
- https://www.hashtagtreinamentos.com/integracao-do-python-com-google-sheets-python

</details>