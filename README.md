# larson_exercices
📊 Análise Estatística e Histograma com Python

Este projeto realiza uma análise estatística básica de um conjunto de dados numéricos e gera um gráfico de frequência por intervalos (histograma) utilizando Python, Pandas e Matplotlib.

🚀 Funcionalidades
Cálculo de:
Valor mínimo e máximo
Amplitude
Média
Mediana
Moda
Criação de classes (intervalos)
Cálculo de:
Frequência absoluta
Frequência relativa
Frequência acumulada
Geração de gráfico com:
Intervalos no eixo X
Frequência no eixo Y
Valores exibidos acima das barras
📂 Estrutura dos Dados

Exemplo de entrada:

lista_numerica = [
    128, 100, 180, 150, 200, 90, 340, 105, 85, 270,
    200, 65, 230, 150, 150, 120, 130, 80, 230, 200,
    110, 126, 170, 132, 140, 112, 90, 340, 170, 190
]
📈 Exemplo de Saída

O código gera um gráfico de barras com:

Intervalos como:

65-105, 105-145, 145-185...
Frequência de cada intervalo
Valores exibidos acima de cada barra
🧠 Conceitos Utilizados
Distribuição de frequência
Agrupamento em classes
Histogramas
Estatística descritiva
🛠️ Tecnologias Utilizadas
Python 3
Pandas
Matplotlib
▶️ Como Executar
Instale as dependências:
pip install pandas matplotlib
Execute o script:
python seu_arquivo.py
📌 Observações
O uso de include_lowest=True garante que o menor valor seja incluído corretamente nos intervalos.
O gráfico foi feito com plt.bar() para maior controle visual (cores, rótulos, etc).
📷 Possível melhoria
Adicionar cores personalizadas para cada barra
Exportar gráfico como imagem (.png)
Criar interface simples (ex: Streamlit)
👨‍💻 Autor

Projeto desenvolvido para estudo de estatística e visualização de dados em Python.