# Telco Customer Churn
### Índice

- [Telco Customer Churn](#telco-customer-churn)
    - [Índice](#índice)
    - [Contextualização:](#contextualização)
    - [Metodologia Aplicada:](#metodologia-aplicada)
  - [Entendimento do Negócio:](#entendimento-do-negócio)
  - [Entendimento dos Dados:](#entendimento-dos-dados)
    - [Variáveis:](#variáveis)
    - [Verificando as Dimensões do DataFrame:](#verificando-as-dimensões-do-dataframe)
    - [Describe:](#describe)
    - [Verificando Valores Nulos:](#verificando-valores-nulos)
    - [Verificando Tipos:](#verificando-tipos)
    - [Verificando Duplicados:](#verificando-duplicados)
    - [Verificando Ditribuição:](#verificando-ditribuição)
  - [Preparação dos Dados:](#preparação-dos-dados)
    - [Separando features:](#separando-features)
    - [Separando X e Y:](#separando-x-e-y)
    - [Train-test split:](#train-test-split)
    - [Tratando os nulos:](#tratando-os-nulos)
    - [Construção do pipeline de pré-processamento:](#construção-do-pipeline-de-pré-processamento)
  - [Modelagem:](#modelagem)
    - [Pipeline:](#pipeline)
    - [Modelos:](#modelos)
    - [Buscando os melhores modelos:](#buscando-os-melhores-modelos)
    - [Melhor modelo:](#melhor-modelo)
  - [Avaliação:](#avaliação)
  - [Implantação:](#implantação)
  - [Pré-requisitos para executar o projeto:](#pré-requisitos-para-executar-o-projeto)
    - [Ambiente virtual e Dependências:](#ambiente-virtual-e-dependências)


### Contextualização:
Uma empresa fictícia de telecomunicações que ofereceu serviços de telefone residencial e internet para 7043 clientes na Califórnia no terceiro trimestre

### Metodologia Aplicada:
A análise foi realizada utilizando o modelo CRISP-DM, o CRISP-DM (Cross Industry Standard Process for Data Mining) é um modelo padrão de processo para projetos de mineração de dados que define um conjunto de fases e tarefas que devem ser executadas para desenvolver soluções de mineração de dados efetivas.

![CRISP-DM](/core/img/CRISP-DM.png)

O modelo CRISP-DM é uma abordagem sistemática e estruturada para a mineração de dados que ajuda as empresas a desenvolver soluções de mineração de dados de maneira eficiente e eficaz, reduzindo o tempo e os custos do projeto.

## Entendimento do Negócio:
Este projeto tem como objetivo prever o custo do seguro de saúde.

## Entendimento dos Dados:
### Variáveis:
| Campo             | Descrição                                     |
|-------------------|-----------------------------------------------|
| CustomerID        | ID do cliente                                |
| Latitude          | Latitude geográfica da localização do cliente |
| Longitude         | Longitude geográfica da localização do cliente|
| Gender            | Gênero do cliente                            |
| Senior Citizen    | Indicação se o cliente é idoso               |
| Partner           | Indicação se o cliente tem parceiro          |
| Dependents        | Indicação se o cliente possui dependentes   |
| Tenure Months     | Número de meses de permanência do cliente    |
| Phone Service     | Indicação se o cliente possui serviço telefônico|
| Multiple Lines    | Indicação se o cliente possui múltiplas linhas telefônicas|
| Internet Service  | Tipo de serviço de internet do cliente       |
| Online Security   | Indicação se o cliente possui segurança online|
| Online Backup     | Indicação se o cliente possui backup online  |
| Device Protection | Indicação se o cliente possui proteção de dispositivo|
| Tech Support      | Indicação se o cliente possui suporte técnico|
| Streaming TV      | Indicação se o cliente possui serviço de streaming de TV|
| Streaming Movies  | Indicação se o cliente possui serviço de streaming de filmes|
| Contract          | Tipo de contrato do cliente                  |
| Paperless Billing | Indicação se o cliente utiliza fatura eletrônica|
| Payment Method    | Método de pagamento do cliente               |
| Monthly Charges   | Valor mensal cobrado ao cliente              |
| Total Charges     | Valor total cobrado ao cliente               |
| CLTV              | Tempo de vida do cliente como valor do cliente|
| Churn Value       | Indicação de se o cliente cancelou o serviço|



### Verificando as Dimensões do DataFrame:
![Data Frame](/core/img/shape.png)

### Describe:
![Data Frame](/core/img/describe.png)

### Verificando Valores Nulos:
![Data Frame](/core/img/nulos.png)

### Verificando Tipos:
![Data Frame](/core/img/tipos.png)

### Verificando Duplicados:
![Data Frame](/core/img/duplicados.png)

### Verificando Ditribuição:
![Data Frame](/core/img/verificando_ditribuicao.png)

## Preparação dos Dados:

### Separando features:
![Data Frame](/core/img/separando_features.png)

### Separando X e Y:
![Data Frame](/core/img/separando_x_e_y.png)

### Train-test split:
![Data Frame](/core/img/train_test_split.png)

### Tratando os nulos:
![Data Frame](/core/img/tratando_os_nulos.png)

### Construção do pipeline de pré-processamento:
![Data Frame](/core/img/pre_processamento.png)


## Modelagem:
### Pipeline:
![Data Frame](/core/img/pipeline.png)

### Modelos:
![Data Frame](/core/img/modelos.png)

### Buscando os melhores modelos:
![Data Frame](/core/img/seeking_the_best_model.png)

### Melhor modelo:
![Data Frame](/core/img/the_best_model.png)

## Avaliação:
...

## Implantação:
Iniciando a etapa de implementação do modelo em produção.

## Pré-requisitos para executar o projeto:
Abaixo, listarei os requisitos necessários para que o projeto funcione corretamente.

### Ambiente virtual e Dependências:
Criando ambiente virtual:
```
python3 -m venv core/.venv python=3.10.6
```

Entrando no ambiente virtual:
```
source core/.venv/bin/activate
```

Instale as dependências:
```
pip install -r core/requirements.txt
```

---
Linkedin: <https://www.linkedin.com/in/samuel-barbosa-dev/> 

E-mail: <samueloficial@protonmail.com>