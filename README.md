# 🤖 Predictmaint-ai

> Projeto de Inteligência Artificial para previsão de falhas mecânicas em máquinas industriais.

## 📖 Sobre o projeto

O **PredictMaint AI** foi desenvolvido para demonstrar como a Inteligência Artificial pode ser aplicada na manutenção preditiva de máquinas industriais.

A partir da análise de dados coletados por sensores, o projeto busca identificar padrões que indiquem uma possível falha antes que ela aconteça. Essa abordagem pode ajudar empresas a reduzir paradas inesperadas, diminuir custos de manutenção e apoiar a tomada de decisões.

Durante o desenvolvimento foram realizadas todas as etapas de um projeto de Ciência de Dados, desde a exploração da base até o treinamento e a avaliação dos modelos de Machine Learning.

## 🎯 Problema que o software resolve

Em uma indústria, a parada inesperada de uma máquina pode gerar prejuízos financeiros, atrasos na produção e comprometer todo o processo produtivo.

Pensando nesse cenário, este projeto utiliza dados operacionais para prever possíveis falhas mecânicas. Em vez de agir somente quando o problema acontece, a proposta é utilizar a Inteligência Artificial para apoiar uma manutenção mais preventiva e eficiente.

## 🚀 Objetivos

- Explorar e compreender a base de dados.
- Identificar e tratar valores ausentes.
- Criar uma nova variável para enriquecer a análise.
- Treinar modelos de classificação.
- Comparar os resultados e identificar o modelo com melhor desempenho.

## 📂 Dataset

O projeto utiliza uma base de dados com **10.000 registros** e **14 colunas**, contendo informações sobre o funcionamento de máquinas industriais.

Entre os dados disponíveis estão características operacionais, como temperatura, velocidade de rotação, torque e desgaste da ferramenta, além da indicação de ocorrência de falhas.

A variável utilizada como alvo é **`falha_maquina`**, em que:

- **0** representa funcionamento normal;
- **1** representa ocorrência de falha mecânica.

## 🛠️ Tecnologias e Ferramentas utilizadas

O projeto foi desenvolvido utilizando **Python 3.14.3**, juntamente com ferramentas e bibliotecas voltadas para Ciência de Dados e Machine Learning.

### Ferramentas

- Python 3.14.3
- Visual Studio Code
- Jupyter Notebook
- Git
- GitHub
- Trello

### Bibliotecas

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn

## 🔧 Técnicas utilizadas

Durante o desenvolvimento foram aplicadas as seguintes técnicas:

- Análise Exploratória de Dados (EDA);
- Tratamento de valores ausentes;
- Identificação de outliers com Boxplot;
- Feature Engineering com criação da variável `potencia`;
- Divisão entre treino e teste utilizando `stratify`;
- Balanceamento das classes;
- Padronização dos dados com `StandardScaler`;
- Treinamento do modelo KNN;
- Treinamento do modelo Árvore de Decisão;
- Ajuste de hiperparâmetros;
- Comparação dos modelos por meio da acurácia.

## 🧠 Modelos de Machine Learning utilizados

Foram avaliados dois modelos de classificação:

- **K-Nearest Neighbors (KNN)**
- **Árvore de Decisão**

Após os experimentos e os ajustes realizados, os modelos foram comparados utilizando a acurácia no conjunto de teste.

## 🌐 Como a Internet é utilizada no projeto

Durante o desenvolvimento, a internet foi utilizada como apoio para consultar a documentação oficial das bibliotecas, pesquisar conceitos relacionados à Ciência de Dados e esclarecer dúvidas sobre Python e Machine Learning.

Essas consultas serviram como suporte ao aprendizado e contribuíram para a implementação das soluções adotadas no projeto.

## 🔗 Repositório

O código-fonte deste projeto está disponível no GitHub:

<https://github.com/acaciarosar/predictmaint-ai>

## 📁 Estrutura do projeto

```text
predictmaint-ai/
├── data/
│   └── manutencao_preditiva.csv
├── predictmaint_ai.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```
## ▶️ Como executar

1. Clone este repositório.

```bash
git clone https://github.com/acaciarosar/predictmaint-ai.git
```

2. Acesse a pasta do projeto.

```bash
cd predictmaint-ai
```

3. Instale as dependências.

```bash
pip install -r requirements.txt
```

4. Certifique-se de que o arquivo `manutencao_preditiva.csv` esteja dentro da pasta `data`.

5. Execute o Jupyter Notebook.

```bash
jupyter notebook
```

6. Abra o arquivo `predictmaint_ai.ipynb` e execute as células em ordem.

---

## 📊 Resultado do projeto

Foram avaliados dois modelos de Machine Learning.

### KNN

- K = 3 → **0.926**
- K = 5 → **0.917**
- K = 7 → **0.909**

### Árvore de Decisão

- max_depth = 3 → **0.9030**
- max_depth = 5 → **0.9375**
- max_depth = None → **0.9470**

Após comparar os resultados, a **Árvore de Decisão** apresentou a melhor acurácia (**0.9470**) e foi escolhida como o modelo de melhor desempenho para este projeto.

---

## 🔮 Melhorias futuras

Como próximos passos, o projeto pode ser ampliado com:

- utilização de outros algoritmos de classificação;
- análise de métricas como Precisão, Recall e F1-Score;
- validação cruzada;
- seleção de variáveis;
- criação de dashboards para visualização dos resultados;
- integração com APIs para receber dados em tempo real.

---
## 🎥 Vídeo de Demonstração

O vídeo de apresentação do projeto pode ser acessado no link abaixo:

**(Adicionar o link após a publicação.)**

---

## 👩‍💻 Autora

Projeto desenvolvido por **Acacia Rosar**.