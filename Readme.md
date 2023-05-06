# PetLove Talents Data Case

- Programa: PetLove Talents
- Case: Dados
- Objetivo: Análise de churn de clientes
- Empresa: PetLove

#### **Introdução**

A Petlove&CO é a maior plataforma voltada para animais de estimação da América Latina. O papel da empresa é cuidar de toda a experiência do animal de estimação, incluindo a cadeia de suprimentos (por Petlove), cuidados de saúde (por Vet Smart), gestão empresarial (ERP por Vetus) e cuidados diários (por DogHero). Nesse cenário diverso, o grupo Petlove criou esquadrões de dados cuidadosamente planejados para reunir diferentes habilidades para incrementar o desempenho de cada iniciativa.

#### **O que você deve levar em consideração**

Seu desafio é participar da equipe de Assinatura, serviço onde o dono do animal programa a entrega de um conjunto de itens dentro de um período customizado, recebendo descontos e brindes exclusivos para assinantes.

#### **Prazo de entrega**

* 05/05/2023 às 23:59

#### **Objetivo**

A equipe de assinaturas tem como objetivo reduzir a perda de assinantes. O conceito de “Churn” refere-se a perda de qualquer usuário que assinou o serviço de assinatura da Petlove e o cancelou em algum momento após a contratação. Ao analisar os dados dos últimos meses, apesar de todas as melhorias de usabilidade da plataforma, o churn vem aumentando.


Seu trabalho será apresentar um resultado final com DOIS pontos principais: Quais são os Aprendizados da sua análise dos dados e o que sugere como Próximos Passos. Lembre-se de que os insights precisam ficar claros para todos, desde o diretor da área até a equipe de tecnologia que verá sua apresentação.


## Conteúdo
- Tecnologias
- Base de dados
- Instalação
- Organização do projeto
- Commits
- Contribuições

## Tecnologias
- Python
- Conda
- Jupyter
- Numpy
- Pandas
- Matplotlib
- Seaborn

## Base de dados
Neste projeto iremos analisar um dataset em formato de csv disponibilizado pelo time de PetLove. Seus metadados estão dispostos da seguinte maneira:

| Nome               | Descrição                                          |
|--------------------|----------------------------------------------------|
| id                 | Identificação do cliente                           |
| created_at         | Data de criação da assinatura                      |
| updated_at         | Data da última modificação da assinatura           |
| deleted_at         | Data de cancelamento da assinatura                 |
| name_hash          | Nome do usuário (criptografado)                    |
| address_hash       | Email (criptografado)                              |
| birth_date         | Data de aniversário do cliente                     |
| status             | Status da assinatura                               |
| version            | Versão da assinatura                               |
| city               | Cidade do cliente                                  |
| state              | Estado do cliente                                  | 
| neighborhood       | Bairro do cliente                                  | 
| last_date_purchase | Data do último pedido que ocorreu pela assinatura  | 
| average_ticket     | Média de gasto por pedido                          | 
| items_quantity     | Média de itens na assinatura                       | 
| all_revenue        | Total de receita realizado pelo cliente            | 
| all_orders         | Total de pedidos realizado pelo cliente            | 
| recency            | Tempo desde a última compra do cliente             | 
| marketing_source   | Canal de marketing que converteu a assinatura      | 

## Instalação
Foi utilizado o [Python](https://www.python.org/) v3.11.3.

### Conda
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://docs.conda.io/en/latest/). Portanto para prosseguir necessita-se de sua instalação.

Navegar até a pasta de destino
```sh
cd utils
```

Instalar dependências
```sh
conda env create -f environment.yml
```

Ativar
```sh
conda activate petlove_talents_case_venv
```

Desativar
```sh
conda deactivate
```

### Requirements
Pode-se utilizar o arquivo requirements.txt para criar o ambiente virtual.

Criar ambiente virtual
```sh
python -m venv petlove_talents_case_venv
```

Ativar
```sh
source ./petlove_talents_case_venv/bin/activate
```

Navegar até a pasta de destino
```sh
cd utils
```

Instalar dependências
```sh
pip install -r requirements.txt
```

Desativar
```sh
deactivate
```

## Organização do projeto
```sh
.
├── License
├── main
│   ├── datasets
│   │   ├── processed
│   │   │   └── data-test-analytics.pkl
│   │   └── raw
│   │       └── data-test-analytics.csv
│   ├── notebooks
│   │   ├── eda.ipynb
│   │   └── tratative.ipynb
│   └── outputs
│       └── Readme.md
├── Readme.md
└── utils
    ├── environment.yml
    └── requirements.txt
```

## Commits
Neste projeto foi adotado o uso de Commits Semânticos para padronização:

- Feat: Nova feature do projeto
- Refactor: Refatoração de alguma parte do código
- Fix: Correção de erros que estão causando bugs
- Chore: Mudanças que não influenciam o sistema nem arquivos de testes
- Style: Mudanças de formatação ou estilos de códigos que não influenciam na lógica do sistema
- Test: Criação ou alteração de algum código de teste
- Perf: Alterações feitas para melhorar a performance do projeto
- Docs: Alterações na documentação do projeto

## Contribuições
...