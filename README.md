
# Projeto de regressão linear para prever o preço de casas em Ames, Iowa

## Dupla

- [Marcelo Rabello Barranco](https://github.com/Maraba23)
- [Marcelo Marchetto](https://github.com/marchettomarcelo)

## Descrição do projeto

O objetivo deste projeto é prever o preço de casas em Ames, Iowa, utilizando regressão linear. O dataset utilizado é o [Ames Housing dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data), disponível no Kaggle.


## Como executar o projeto

Primeiramente, clone o repositório:

```bash
git clone https://github.com/marchettomarcelo/Ames-MM.git
```

Em seguida, entre na pasta do projeto:

```bash
cd Ames-MM
```

### Configurando o ambiente

É possível executar o projeto de 2 maneiras:

1. Utilizando o Conda, com o arquivo `environment.yml` para instalar as dependências

2. Utilizando um ambiente virtual do Python, com o arquivo `requirements.txt` para instalar as dependências


### Preparando os dados

Dentro da pasta `notebooks`, execute o notebook `01_reading_raw_data`, em seguida o notebook `02_analysis_and_preprocessing`.

- Esses dois notebooks foram feitos pelo professor da matéria, [Fabio Ayres](https://github.com/FabioAyresInsper/ames). Nao foram feitas quaisquer alterações nesses notebooks. Optamos por deixar a feature engeneering e a análise dos dados feita pelo professor, pois achamos a analise muito boa e completa, e a feature engeneering muito bem feita e como nao tinhamos muita experiencia com isso, acreditamos que seja mais benéfico preservar o trabalho realizado pelo professor.

### Executando o projeto

Dentro da pasta `notebooks`, execute o notebook `entrega`. Este notebook contém o a análise feita pela dupla e a implementação do modelo de machine learning.

- O arquivo `entrega.ipynb` em sua primeira parte foi copiada a regressão linear simples e analise dos dados do professor, a parte realizada pela dupla vem logo após a regressão linear simples. (Explicito conforme os markdowns do notebook). Explicações e Conclusões sobre o que foi feito estão no notebook em formato markdown antes e depois do código.