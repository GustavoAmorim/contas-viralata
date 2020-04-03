![Banner_Contas-ViraLata](https://user-images.githubusercontent.com/38081852/75180453-00f4d400-571b-11ea-85a7-d3a83f830352.png)

![GitHub issues](https://img.shields.io/github/issues-raw/x0n4d0/contas-viralata?color=green) ![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/x0n4d0/contas-viralata?color=red) ![GitHub](https://img.shields.io/github/license/x0n4d0/contas-viralata?color=yellow) ![GitHub last commit](https://img.shields.io/github/last-commit/x0n4d0/contas-viralata) ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/x0n4d0/contas-viralata) ![Server](https://img.shields.io/badge/server-Node%20%7C%20TypeScript-informational) ![Client](https://img.shields.io/badge/client-React-blueviolet) [![Build Status](https://travis-ci.org/x0n4d0/contas-viralata.png?branch=master)](https://travis-ci.org/x0n4d0/contas-viralata) ![Node Version](https://img.shields.io/badge/node-12.16.1-critical)

<!--
![Netlify](https://img.shields.io/netlify/id)

[![Heroku CI Status](https://{deployed app name}.herokuapp.com/last.svg)](https://dashboard.heroku.com/pipelines/{pipeline ID}/tests)
-->

## **OBJETIVO**

O objetivo do projeto é realizar as contas da casa de forma símples, possibilitando a qualquer morador ser capaz de fazer todas as contas caso seja necessário. Solucionando o problema atual de complexidade das planilhas do Excel e a dificuldade de ensinar algum morador como utilizá-las e não cometer erro na hora de fechar as contas. O sistema também será útil para controlar as alocações e disponibilidades dos quartos.

## **FUNCIONALIDADES**

- **Gerência dos Quartos:**

  - Inserir, Remover e Realocar moradores dos quartos;
  - Informar se _Existem Quartos Vazios? Quais os Tipos de Quartos Disponíveis e Quais os Valores?_;
  - Informar _Quantas Vagas Estão Disponíveis?_;
  - Calcular o valor de cada quarto com base nos pesos e no aluguel, dividindo o valor do aluguel pelo total da soma de m² de todos os quartos. Veja a [Tabela Dos Quartos](./docs/notes/README.bedrooms.md) para informações mais detalhadas sobre os quartos.

- **Gerência das Contas:**

  - Gerênciar o valor pago pelo(s) calouro(s);
  - Inserir o valor das contas básicas: **Aluguel, Luz, Água, Internet/Telefone, Compra Básica e Depósito na Caixinha** (Valor que será distribuído para todos os moradores para efetuar a compra básica da casa);
  - Controlar as Notinhas: Inserir notinha com informações (Nome Da Notinha, Valor, Morador que Pagou e Data);
  - Controlar a Caixinha: (Valor Atual, Notinhas Pagas com a Caixinha e Valor Que Foi Depositado);

- **Saída dos Dados:**

  - Após o fechamento das contas do mês referente, será possível exibir em tela as informações detalhadas das contas e o valor de cada morador, além de ter a opção de baixar um PDF com essas informações. O PDF deverá ter um nome padrão de arquivo: **Contas-Viralata_2020-03-02.pdf** (Título_Ano-Mês-Dia). [Clique Aqui](./docs/notes/README.pdf.md) e veja um exemplo de como ficará o PDF.

    \* A data contida no nome do arquivo PDF será organizada como **Ano-Mês-Dia** para facilitar na hora de armazenar em algum diretório, dado que a maioria dos diretórios é organizado por nome. Colocando automaticamente os arquivos de contas mais recentes no início.

    \* O documento PDF possui no final uma parte para assinaturas, permitindo que ao ser impresso, possa ser autenticado (assinado) pelos moradores e armazenado (grampeado) junto com o recibo das contas e notinhas do mês referente, facilitando assim a organização dos arquivos físicos das contas.

## **LICENÇA**

Esse repositório está licenciado pela **MIT LICENSE**. Para informações detalhadas sobre essa licença, leia o arquivo [LICENSE](./LICENSE) presente neste repositório.
