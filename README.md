# Grupo de Estudos de Raspagem de Dados do Raul Hacker Club
## Index
1. [Sobre o LabCidadania](#sobre)
2. [Sobre o projeto](#projeto)
3. [Como funciona](#encontros)
4. [Como participar](#participe)
5. [Contribuindo com o projeto](#contribuindo)
6. [Tutorial](#tutorial)

## Sobre
O Laboratório de Dados para Cidadania Hacker é um laboratório colaborativo surgido para realização experimental, a partir da cultura hacker, de processos digitais sobre dados públicos, ressignificando a transparência da administração pública e visando a promoção da cidadania.

Este grupo de estudos iniciou-se em maio de 2017 voltado a [Jornalismo de Dados e seguindo o curso online do Knight Center](https://lists.riseup.net/www/arc/raulhc/2017-06/msg00024.html), cresceu e como demanda de seus membros tornou-se o Laboratório de Dados.

## Projeto
Abrigado pelo Raul Hackerspace e relacionado com o Observatório Social do Brasil, está inicialmente focado nas bases de dados dos órgãos públicos baianos. 

As práticas de raspagem, mineração e visualização dos dados públicos, feitas pelo Laboratório de Dados para Cidadania Hacker, colocam em debate a reconfiguração dos conceitos de desobediência civil e a transparência da administração pública.

Como fonte de partida são utilizados os dados do Tribunal de Contas do Município e Tribunal de Contas do Estado para raspagem e análise.

## Encontros
*Como funciona*
Assim como todos os grupos de estudos, não há ensino (formal) ou aulas. As pessoas aprendem juntas. 
  
## Participe 
*Saiba como participar*
Atualmente, os encontros são realizados no [Raul Hackerspace](http://raulhc.cc) aos sábados a partir das 14h. Fique atento a agenda do [RaulHC](http://raulhc.cc/Agenda).

### Contatos
Github: https://github.com/RaspagemDeDados

Telegram: https://t.me/raspagemRaulHC

## Contribuindo
Caso você seja novato e queira aprender sobre raspagem de dados, recomendamos os seguintes materiais gratuitos:

   * Cursos do Fernando Masanori
   1. [Python para Zumbis](https://github.com/fmasanori/PPZ)
   2. [Treinamento Raspagem de Dados](https://github.com/fmasanori/treinamento)
   3. [Datascience Pizza](http://datascience.pizza) - Repositório para juntar informações sobre materiais de estudo em análise de dados e áreas afins, empresas que trabalham com dados e dicionário de conceitos

   * [Escola de Dados](https://escoladedados.org/manual/cursos/)
   * mais indicações virão
   
## Tutorial

### Para acompanhar nossos tutoriais pelo github, siga os seguintes passos:

#### Passos:
1. Criar a pasta do projeto
2. Clonar o repositório
3. Instalar o Virtualenv
4. Criar um environment para o projeto
5. Ativar o environment
6. Instalar o módulo beautifulsoup


## 1. Criar o repositório do projeto

Cria a pasta

``` mkdir Raspagem ```

Entre na pasta

``` cd Raspagem```

## 2. Clonar o repositório
```git clone https://github.com/Edely/raspagem-de-dados-rhc.git```

## 3. Instalar o Virtualenv
``` sudo apt-get install virtualenv ```

## 4. Criar um environment para o projeto
``` virtualenv raspagem ```

## 5. Ativar o environment

Após criar o virtualenv do projeto, toda vez que for rodar o script, é preciso ativar o virtualenv
``` source raspagem/bin/activate ```

## 6. Instalar o módulo BeautifulSoup
pip install beautifulsoup4
