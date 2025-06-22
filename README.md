
## 🧩 Clusterização de Clientes com K-means

### 📌 Descrição

Este projeto realiza a **segmentação de clientes** com base em três variáveis principais: **idade**, **renda mensal** e **pontuação de gastos**. O objetivo é identificar **perfis distintos de consumidores** usando o algoritmo **K-means**, uma técnica de aprendizado não supervisionado amplamente usada em marketing e análise de comportamento do cliente.

---

### 🧠 Técnicas Utilizadas

* Padronização com `StandardScaler`
* Definição do número ideal de clusters pelo **método do cotovelo**
* **K-means Clustering** com `scikit-learn`
* Visualização interativa com `Plotly`

---

### 📁 Dados

Um conjunto de dados **sintético** foi gerado contendo 500 registros com as seguintes colunas:

| Coluna             | Descrição                              |
| ------------------ | -------------------------------------- |
| `Idade`            | Idade do cliente (18 a 70 anos)        |
| `Renda_Mensal`     | Renda mensal estimada em reais         |
| `Pontuacao_Gastos` | Score entre 0 e 100 baseado em consumo |

📄 Arquivo CSV: [`clientes_segmentacao.csv`](./clientes_segmentacao.csv)

---

### 📊 Resultado Esperado

O modelo identifica automaticamente **4 clusters de clientes**, agrupando-os com base em similaridades numéricas. A visualização dos grupos mostra padrões claros, como:

* Clientes jovens com baixa renda e alta pontuação de gastos
* Clientes mais velhos com alta renda e baixa pontuação
* E outros perfis de comportamento de compra

---

### 📎 Como Executar

1. Baixe o arquivo `clientes_segmentacao.csv`.
2. Abra o notebook `clusterizacao_clientes.ipynb` no Google Colab ou Jupyter.
3. Faça upload do CSV para o ambiente.
4. Execute todas as células para visualizar os resultados e gráficos.

---

### 💡 Possíveis Extensões

* Adicionar mais variáveis como frequência de compra ou fidelidade
* Aplicar PCA para visualização dimensional
* Exportar clusters para análise em um dashboard com Streamlit ou Dash

---

### 📚 Tecnologias e Bibliotecas

* Python 3.10
* pandas
* scikit-learn
* matplotlib
* plotly

