# web-scraping-nota-fiscal👮
# Automação do preenchimento de dados para emissão de nota fiscal
Esse projeto consiste  em fazer a automação de um site para preencher notas fiscais de uma empresa fictícia.
- Usando a biblioteca Selenium como principal fonte para navegar e intergir com a página web.
- primeiro criamos a conexão com o navegador(Chrome) através da função 'selenium.webdriver.chrome.service'.
- Já com a conexão feita, podemos linkar a nossa página web pelo navegador.get() que ira abrir o Chrome e a a página solicitada.
- Na página usamos métodos do Selenium para navegar e preencher os campos em questão com o 'inspecionar', nos campos selecionados podemos pegar suas referências pelos ID, XPATH, TAG_NAME...)
- Por fim utilizamos uma base de dados em excel para criar as notas fiscais de maneira autonoma pela biblioteca Pandas.
- 
- 
- 
