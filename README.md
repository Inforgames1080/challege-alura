📊 Análise de Vendas — Projeto com Pandas e Matplotlib
🎯 Propósito da Análise

O objetivo deste projeto é realizar uma análise exploratória de dados de vendas para identificar padrões de consumo, desempenho de categorias, estados e vendedores, além de calcular métricas importantes como o faturamento total e o ticket médio. A análise utiliza ferramentas como Pandas para manipulação de dados e Matplotlib para visualização.
📦 projeto_analise_vendas/
├── data/
│   └── vendas.csv               # Arquivo com os dados de vendas (caso exista)
├── img/
│   └── *.png                    # Imagens dos gráficos gerados (opcional)
├── notebook/
│   └── analise_vendas.ipynb     # Jupyter Notebook com toda a análise
├── README.md                   # Instruções e descrição do projeto
└── requirements.txt            # Dependências do projeto (pandas, matplotlib, etc.)
📈 Exemplos de Gráficos e Insights Obtidos
🔹 Faturamento por Categoria

    Destaque para a categoria Eletrodomésticos, que lidera em faturamento.

    Categorias como Brinquedos e Eletrônicos possuem menor volume de vendas.

🔹 Faturamento por Vendedor

    O vendedor João Souza é o que mais gerou receita, com vendas em dois estados diferentes.

    Outros vendedores possuem vendas pontuais e menor ticket médio.

🔹 Faturamento por Estado

    O estado RS concentrou o maior faturamento entre os locais de compra.

    Estados como DF e SP tiveram participações menores.

🔹 Ticket Médio

    O ticket médio por venda foi de aproximadamente R$467,06.

Exemplo de gráfico:

▶️ Instruções para Executar o Notebook

    Clone o repositório:

git clone https://github.com/seu-usuario/projeto_analise_vendas.git
cd projeto_analise_vendas

Crie um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

Instale as dependências:

pip install -r requirements.txt

Execute o Jupyter Notebook:

jupyter notebook notebook/analise_vendas.ipynb
