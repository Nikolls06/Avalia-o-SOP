# Avaliação-SOP

Contagem de Produtos por Segmento
Este é um aplicativo web simples feito com Streamlit para visualizar a quantidade de produtos vendidos por segmento, utilizando dados de um arquivo CSV.

Funcionalidades
Carrega os dados do arquivo MS_Financial Sample.csv.

Conta o número de produtos em cada segmento.

Exibe um gráfico de barras com a quantidade de produtos por segmento.

Trata erros de arquivo ausente ou dados faltantes.

Como usar
Certifique-se de ter o Python instalado.

Instale as dependências:

pip install streamlit pandas matplotlib
Coloque o arquivo MS_Financial Sample.csv no mesmo diretório do script.

Execute o aplicativo Streamlit:

streamlit run nome_do_seu_script.py
Acesse o endereço que aparecer no terminal (normalmente http://localhost:8501) para visualizar o gráfico.

Arquivo CSV esperado
O arquivo CSV deve conter, no mínimo, as colunas:

Segmento

País

Produto

Faixa de Desconto

Unidades Vendidas

Preço de Fabricação

Preço de Venda

Vendas Brutas

Descontos

Vendas

CPV

Lucro

Data

Número do Mês

Nome do Mês

Ano

O delimitador esperado é ;.

Tratamento de erros
Se o arquivo não for encontrado, uma mensagem de erro é exibida.

Se não houver dados no segmento, uma mensagem de aviso é mostrada.

Tecnologias
Python

Streamlit

Pandas

Matplotlib

