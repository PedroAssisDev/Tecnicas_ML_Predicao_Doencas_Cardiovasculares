# Técnicas de Aprendizado de Máquina para Predição de Doenças Cardiovasculares

Repositório do Trabalho de Conclusão de Curso (TCC) sobre predição de doenças cardiovasculares com aprendizado de máquina.

## Estrutura

| Arquivo | Descrição |
|---------|-----------|
| [TCC.ipynb](TCC.ipynb) | Notebook com pré-processamento, treino e avaliação |
| [requirements.txt](requirements.txt) | Dependências Python |
| `TCC_UFJF_Texto_Pedro_Assis_VF.pdf` | Texto do TCC |

## Dados

O CSV **não está versionado** neste repositório. Baixe o [Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) no Kaggle e salve como:

- Local: `data/cardio_train.csv`
- Google Colab: `/content/cardio_train.csv`

O notebook tenta esses caminhos automaticamente.

## Como executar

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
mkdir data
# Coloque cardio_train.csv em data/
jupyter notebook TCC.ipynb
```

No Colab, faça upload de `cardio_train.csv` para `/content/` e execute as células do notebook.

## Modelos

- Regressão Logística
- K-Nearest Neighbors (KNN) com `GridSearchCV`
- Random Forest com `GridSearchCV`

## Requisitos

- Python 3.x
- Dependências em `requirements.txt`: pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter

## Palavras-chave

_Doença Cardiovascular, Aprendizado de Máquina, Pré-processamento de Dados, Treinamento de Modelo, Avaliação de Modelo, Jupyter Notebook, Python, Kaggle._

---

# Machine Learning Techniques for Cardiovascular Disease Prediction

Repository for a thesis on cardiovascular disease prediction using machine learning.

## Structure

| File | Description |
|------|-------------|
| [TCC.ipynb](TCC.ipynb) | Notebook with preprocessing, training, and evaluation |
| [requirements.txt](requirements.txt) | Python dependencies |
| `TCC_UFJF_Texto_Pedro_Assis_VF.pdf` | Thesis text |

## Data

The CSV is **not** included in this repository. Download the [Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) from Kaggle and save it as:

- Local: `data/cardio_train.csv`
- Google Colab: `/content/cardio_train.csv`

The notebook resolves these paths automatically.

## How to run

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
mkdir data
# Place cardio_train.csv under data/
jupyter notebook TCC.ipynb
```

On Colab, upload `cardio_train.csv` to `/content/` and run the notebook cells.

## Models

- Logistic Regression
- K-Nearest Neighbors (KNN) with `GridSearchCV`
- Random Forest with `GridSearchCV`

## Requirements

- Python 3.x
- Dependencies in `requirements.txt`: pandas, numpy, matplotlib, seaborn, scikit-learn, jupyter

## Keywords

_Cardiovascular Disease, Machine Learning, Data Preprocessing, Model Training, Model Evaluation, Jupyter Notebook, Python, Kaggle._
