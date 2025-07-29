# 📊 Análise de Dados com Pandas – Desafios do Curso

Este projeto foi desenvolvido como parte do curso **"Pandas: conhecendo a biblioteca"** da Alura. O notebook contém a resolução dos desafios propostos ao final de cada aula, com foco em manipulação e análise de dados utilizando a biblioteca **Pandas** no Python.

---

## 📚 Conteúdo abordado

O projeto está dividido em quatro aulas, com foco progressivo nas principais funcionalidades do Pandas:

---

### Aula 1 – Conhecendo a Base de Dados
- Leitura de arquivo `.csv` com `pd.read_csv()`.
- Visualização com `head()` e `tail()`.
- Análise estrutural com `shape`, `columns`, `info()` e `describe()`.

---

### Aula 2 – Análise Exploratória dos Dados
- Leitura de nova base de imóveis.
- Filtragem com `query()` (remoção de imóveis comerciais).
- Cálculo de médias com `mean()` e `groupby()`.
- Contagem de valores com `value_counts()` e `nunique()`.
- Criação de gráficos com `plot()`.

---

### Aula 3 – Tratamento de Dados Nulos e Filtragem
- Verificação e preenchimento de nulos com `isnull()` e `fillna()`.
- Remoção de registros com `drop()`.
- Filtros com condições booleanas e `query()`.
- Salvamento de DataFrames com `to_csv()` e leitura com `read_csv()`.
- Substituição de valores com `replace()`.

---

### Aula 4 – Novas Colunas e Lógica Condicional
- Criação de colunas novas com `apply()` e `lambda`.
- Cálculo de pontos extras com base percentual.
- Verificação de aprovação final com base nas notas finais.
- Filtragem de alunos que mudaram de status de aprovação.

---

## 🛠️ Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Google Colab](https://colab.research.google.com/)
- [Matplotlib (via Pandas)](https://matplotlib.org/)

---

## 📁 Estrutura do Projeto

```bash
.
├── notebook.ipynb             # Notebook com os desafios resolvidos
├── alunos_aprovados.csv       # Exportação dos alunos aprovados (Aula 3)
└── README.md                  # Este arquivo
