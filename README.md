# Machine Learning: classificação por trás dos panos

Neste curso, vamos:

- Aplique machine learning na sua empresa
- Pratique com diversos exemplos
- Veja como algoritmos de classificação estão por todos os lados no nosso dia a dia
- Analise resultados com a mente de um cientista de dados
- Compare o resultado de algoritmos lineares e não lineares
- Entenda por trás dos panos o que é o tal do aprendizado de máquina para classificação
- Faça estudos replicáveis, com estratégias de testes
- Veja Support Vector Machines, Árvores de Decisão e Dummy Classifiers


## Dataset

A base de dados utilizada durante o curso é da plataforma Kaggle e pode ser
encontrada neste link:

- [Telecom Churn Dataset](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets?select=churn-bigml-20.csv)

Para utilização no curso, esta base de dados do     Kaggle passou por alguns tratamentos, por isso está levemente diferente da disponibilizada pelo Kaggle.

Baixar o arquivo Customer-Churn.csv do repositório: [ML: Classificação por trás dos panos](https://github.com/alura-cursos/ML_Classificacao_por_tras_dos_panos/tree/main/Dados)

## Ambiente de desenvolvimento

1. Criar e ativar o ambiente virtual.

   - É muito importante que o ambiente virtual seja salvo em uma pasta com um nome DIFERENTE de .env. Uma sugestão é .venv.

    ```shell
    conda create -p .venv python=3.8.1
    ```

    - Ativando o ambiente virtual.

    ```shell
    conda activate ../.venv
    ```

2. Ativando o terminal python.

    ```shell
    python
    ```

Pronto! o ambiente está pronto!!!

## Requerimentos extras

- Instalar pacotes no projeto
  - Basta colocar no arquivo 'requeriments.txt' o nome do pacote quer instalar

    ```python
    pip install -r requirements.txt
    ```
