# Projeto Python IA: Score de Crédito dos Clientes

## Descrição
Este projeto tem como objetivo analisar o perfil dos clientes de um banco e prever o score de crédito de cada um deles.  
Com base em dados históricos, a Inteligência Artificial consegue classificar os clientes em três categorias: Ruim, Ok e Bom.  
O modelo foi desenvolvido utilizando Python, pandas e scikit-learn, com foco em aprendizado supervisionado.

Arquivos utilizados no projeto: [Link para dataset](https://drive.google.com/drive/folders/1FbDqVq4XLvU85VBlVIMJ73p9oOu6u2-J?usp=drive_link)

---

## Tecnologias Utilizadas
- Python 3
- pandas
- scikit-learn
- joblib (opcional, salvar modelos)
- parquet (opcional, manipulação de dados)

---

## Passo a Passo do Projeto
1. Importar a base de dados (clientes.csv).  
2. Preparar a base de dados (conversão de variáveis categóricas em numéricas com LabelEncoder).  
3. Separar dados em treino e teste (train_test_split).  
4. Criar e treinar modelos de IA (RandomForestClassifier e KNeighborsClassifier).  
5. Avaliar o desempenho dos modelos (accuracy_score).  
6. Escolher o melhor modelo (Random Forest obteve melhor resultado).  
7. Fazer previsões com novos clientes (novos_clientes.csv).  

---

## Exemplo de Saída
Após treinar e avaliar os modelos, o sistema gera previsões como:
Cliente 1 -> Score: Bom
Cliente 2 -> Score: Ok
Cliente 3 -> Score: Ruim


E adiciona a coluna `score_credito` no arquivo de novos clientes.

---


