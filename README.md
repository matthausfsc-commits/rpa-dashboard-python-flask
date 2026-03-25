# rpa-dashboard-python-flask
Dashboard web para monitoramento de robôs de automação. Integração dinâmica entre scripts Python, processamento de dados com Pandas e interface Flask.
# 📈 RPA Dashboard Monitor

Este projeto é um ecossistema de monitoramento para robôs de automação. Ele resolve o problema de visualização de dados brutos (Excel), transformando planilhas geradas por bots em um Dashboard Web acessível e dinâmico.

## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Flask** (Framework Web)
* **Pandas** (Manipulação de dados)
* **HTML5/CSS3** (Interface visual)

## ⚙️ Como Funciona
1. O robô de automação (RPA) captura os dados e salva no arquivo `relatorio_vendas.xlsx`.
2. O servidor Flask lê o arquivo em tempo real usando a biblioteca Pandas.
3. Os dados são tratados e injetados no template HTML via Jinja2 para exibição no navegador.

## 🚀 Como Executar
1. Instale as dependências: `pip install flask pandas openpyxl`
2. Rode o gerador de dados: `python gerar_dados.py`
3. Inicie o servidor: `python testeflaskwebsitetoday.py`
4. Acesse: `http://127.0.0.1:5000`
