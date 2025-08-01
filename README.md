# Titanic Challenge - Pattern Recognition (Assignment 2)


Este repositório apresenta um notebook completo de Análise Exploratória de Dados, Engenharia de Features, Comparação de Modelos e Geração de Submission para o desafio Titanic do Kaggle.

---

## :trophy: Objetivo

Prever quais passageiros sobreviveram ao naufrágio do Titanic, utilizando atributos como idade, gênero, classe, porto de embarque, tamanho da família, entre outros, além de recursos derivados e engenharia de variáveis.

---

## :mag: Principais Etapas e Metodologia

- **Análise Exploratória Detalhada:** Visualização de taxa de sobrevivência por faixa etária, gênero, classe social, título (ex. 'Mrs', 'Miss'), tamanho da família, porto de embarque, entre outros.
- **Pré-processamento:**  
  - Preenchimento de valores faltantes (idade, tarifa, porto)
  - Conversão de variáveis categóricas para numéricas
  - Extração e agrupamento de títulos do nome (Sr, Sra, etc.)
  - Criação de atributos como Tamanho da Família, Se estava sozinho, Se era criança, Faixa Etária e Faixa de Tarifa
- **Comparação de Modelos:**  
  Avaliação de Random Forest, Regressão Logística, Decision Tree e KNN usando validação holdout
- **Seleção automática do melhor modelo** (com maior acurácia)
- **Geração de arquivo `submission.csv`** para upload no Kaggle

---

## :books: Organização dos arquivos

- `titanic_assignment2.ipynb` — Notebook Jupyter com todo o código comentado, análises, gráficos e resultados.
- `submission.csv` — Arquivo gerado para submissão no Kaggle.
- `README.md` — Este arquivo.
- **Obs:** Os arquivos `train.csv` e `test.csv` devem ser baixados diretamente do [Kaggle Titanic Challenge](https://www.kaggle.com/competitions/titanic/data).

---

## :rocket: Como Executar

1. **Clone este repositório**  
   ```sh
   git clone https://github.com/seuusuario/titanic-pattern-recognition.git
   cd titanic-pattern-recognition
