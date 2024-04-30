# Aquisição de clínicas

![cover](img\cover.jpg)

## 📌 Visão Geral

Este projeto visa análisar os dados do periodo de teste (trial) da empresa Real, a fim de análisar possiveis melhorias, além de criar um dashboard para a equipe de produtos - aquisição. 

Foram utilizadas técnicas estatísticas como testes de hipótese, de visualização de dados no Python e Power BI e Figma para a criação do dashboard.

## 💼 Entendimento do Negócio

A Real constrói uma plataforma de trabalho (SaaS - Software as a Service) **focada especificamente em clínicas odontológicas**, onde os dentistas e proprietários de clínica encontram todos os serviços necessários para gerir suas operações. Nosso software oferece uma agenda moderna, prontuário eletrônico e ficha de pacientes, além de acesso a gestão financeira e muito mais.

[📘 Contexto do desafio](notebooks\contexto.ipynb)

**Principais indicadores Chave de Desempenho:**

- Taxa de conversão
- Taxa de churn
- Credenciamentos aprovados
- Engajamento com o produto

## 📊 Análise exploratória de dados

![Distribuição dos motivos de interesse](image.png)

[📘 Notebook - Análise exploratória de dados](notebooks\analise_exploratoria.ipynb)

Foram feitas análises completas das variaveis das tabelas disponibilizadas, avaliando seus por menores e realizando o tratamento necessário.

Ao fim da análise os dados tratados foram salvos em arquivos .xlsx para futura utilização no Power BI.

## 🤔 Testes de hipótese

![Gráfico da média de atividade das clínicas](img\plot_media_atividades.png)

[📘 Notebook - Testes de hipótese](notebooks\testes_hipotese.ipynb)

Os testes de hipótese sanaram duas duvidas:

- A média de atividades das clinicas é relevante para sua assinatura?

- A aprovação do credenciamento é relevante para sua assinatura?

Ambas hipóteses foram testadas e suas resoluções implicaram no produto final, o dashboard.

## 🎯 Dashboard
![Dashboard](img\dashboard.jpg)

As principais análises foram sintetizadas no dashboard destinado a equipe de Produto - Aquisição.

Ela conta com: 

- As assinaturas convertidas para um overview dos clientes.

- Taxa de conversão para avaliar a eficácia do trial em converter as clínicas a se tornarem assinantes.

- Taxa de churn para entender o possivel descontentamento após a assinatura. Uma baixa taxa de churn também indica uma retenção dos clientes.

- Campanhas de marketing para que sejam avaliados possiveis gaps em campanhas, e saber onde será destinado os maiores valores de investimento.

- Credenciamentos aprovados e seu tempo médio de processo em dias. Como foi identificado por meio do teste de hipótese, a aprovação dos credenciamentos é uma fator determinante para a aquisição das clínicas, logo entender como está seu processo é de suma importância.

- Atividade média das clinicas, pois de acordo com o teste de hipótese, uma clínica que engaja mais com o produto tem uma maior tendência em se tornar um assinante.
