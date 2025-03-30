
# Varredor de Site - Coleta de Produtos e Preços

Este é um projeto simples que utiliza o Selenium WebDriver para extrair informações de produtos e preços de uma página da web e salvar essas informações em um arquivo CSV.

📦 Requisitos
Antes de executar o projeto, você precisa ter o seguinte instalado:

Python

Selenium

ChromeDriver

O ChromeDriver precisa ser compatível com a versão do seu navegador Chrome.

Instalação do Selenium
No seu terminal, execute o comando abaixo para instalar o Selenium:

bash
Copiar
Editar
pip install selenium
Instalação do ChromeDriver
Baixe o ChromeDriver de acordo com a versão do seu navegador Chrome:

Download do ChromeDriver

Extraia o arquivo baixado e coloque o executável em um diretório acessível (ex: C:\chromedriver).

Caso queira facilitar, adicione o caminho do ChromeDriver ao seu PATH do sistema.

⚙️ Como Usar
Clone ou baixe o repositório:

bash
Copiar
Editar
git clone https://github.com/usuario/varredor-de-site.git
cd varredor-de-site
Execute o script Python:

bash
Copiar
Editar
python app.py
O script irá:

Abrir o Chrome utilizando o ChromeDriver.

Acessar o site especificado: https://devaprender-play.netlify.app/.

Coletar os produtos e preços exibidos.

Salvar essas informações no arquivo preços.csv.

O arquivo CSV será gerado na pasta do script e terá o formato:

csv
Copiar
Editar
Produto1, R$ 100,00
Produto2, R$ 200,00
🛠️ Tecnologias Utilizadas
Python: Linguagem utilizada para o script.

Selenium WebDriver: Biblioteca usada para automatizar a navegação no navegador.

ChromeDriver: Necessário para o Selenium controlar o Google Chrome.

CSV: Formato utilizado para salvar os dados extraídos.

🔧 Como Funciona
O script utiliza o Selenium WebDriver para acessar a página web.

Ele busca os elementos da página que contêm os nomes dos produtos e os preços, utilizando XPath.

As informações coletadas são salvas em um arquivo CSV, onde cada linha representa um produto e seu respectivo preço.

🚧 Melhorias Futuras
Adicionar mais validações de erro e exceções.

Implementar coleta de mais dados, como descrições e imagens dos produtos.

Melhorar a performance com técnicas como WebDriverWait para evitar o uso de sleep().

