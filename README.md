# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
Anotações relevantes a respeito do papel dos bancos de dados relacionais e não relacionais na Engenharia de Dados

## O que são bancos de dados?

Banco de dados pode ser definido, de forma ampla e generalista,  como uma coleção de palavras, que dentre elas há relacionamentos entre dados, constituindo então um banco de dados, com sua estrutura e significado atrelado.

## O que é SQL e NoSQL?

SQL - Structured Query Language são bancos de dados relacionais, utilizados para armazenar dados relacionados entre si.
- Modelo transacional (vendas, e-commerce);
- OLTP;
- Propriedades ACID (Atomicidade, Consistência, Isolamento, Durabilidade);
- Normatização de Informação;
- Esquema de Dados rígido;
- Integridade de Dados;

NoSQL - Not Only Structured Query Language são bancos de dados não relacionais
- Surgiu pela necessidade de escalabilidade horizontal;
- Capacidades adicionais aos bancos de dados relacionais;
- Grande fluxo e armazenamento de dados;
- Paradigma BIG DATA;
- Dados não estrturados (fotos, vídeos, etc);

### OBSERVAÇÕES:
NoSQL não veio para substituir o banco de dados relacional, mas para complementar;
NoSQL trouxe tecnologias e capacidades que os modelos relacionais não possuem;
NoSQL foram criados para resolver problemas que os bancos relacionais não conseguiam resolver;

## Como são feitas as consultas de dados armazenados em NoSQL?
- Modelagem de informações é essencial. Modele seus documentos, colunas, chave-valor, etc;
- Saiba que tipos de informações se pode e não se pode desprezar dentro de uma consulta;
- Defina as chaves e as formas como serão feitas as consultas;
- Não ser estruturado nõa significa ser bagunçado.

## Conhecer um SGBD de cada tipo é suficiente para começar?
- Entenda que não é preciso conhecer tudo, uma vez que é inviável;
- Saiba porquê cada banco de dados foi feito;
- Entenda o conceito de cada um para quando precisar usar;
- Conheça os tipos de bancos de dados e seus propósitos;
- Saiba que apenas com a prática você fará a melhor escolha do banco de dados para seu contexto;
- Analise: quais são os critérios que preciso? Quais as opções que tenho? Quais podem atender minhas necessidades?
- Entenda questões técnicas, custo benefício, etc;

No ambiente de dados existem (minimamente) 5 capacidades básicas:
- Ingestão;
- Armazenamento;
- Processamento;
- Disponibilidade da informação para consumo;
- Segurança;

## Datalake vs Databricks

Datalake: repositório centralizado que permite armazenar todos os seus dados estruturados e não estruturados em qualquer escala;
Databricks: plataforma de análise de dados unificada para engenharia de dados, machine learning e ciência de dados colaborativa;

## O tipo de banco de dados influencia na complexidade?
  Não necessariamente. A parte mais complexa é a definição da arquitetura do banco de dados, uma vez que isso pode implicar em
em problemas nas etapas posteriores.

## Engenheiro de Dados X Cientista de Dados

Engenheiro de Dados: 
- Focado no desenho e construção de uma solução; 
- Persistência das soluções de dados;
- Extração de dados de fontes heterogêneas;
- Disponibilizar os dados para serem consumidos pelos analistas e cientistas;

Cientista de Dados:
- Modelagem;
- Reconhecimento de Padrões / Predição;
- Busca responder perguntas atreladas ao contexto do negócio, buscando insights através de técnicas de modelagem;


### Sobre o Desafio
Neste desafio, você terá a missão de compreender o papel dos Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL) no contexto de um Engenheiro de Dados. Para isso, anote todos os conceitos, definições e insights que julgar relevantes em um novo repositório Git, aumentando assim seu portfolio de conhecimentos.

Super Dica: Organize tudo em seu README.md, é uma alternativa bem rápida e efetiva, pois, o GitHub provê uma interface bem simples e intuitiva para isso. Além de ampliar seu portifólio de projetos no GitHub!

Pré-requisitos:
- Conhecimento Avançados(SQL, NoSQL);
- Computador com SO de sua preferência(Windows, Linux, Mac OS);
