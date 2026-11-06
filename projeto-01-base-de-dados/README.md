# Projeto 01 — Base de Dados

## Tema: Posto de Saúde

Este projeto é a primeira etapa de uma sequência de cinco projetos com o tema Posto de Saúde, desenvolvidos durante o Bootcamp de Análise de Dados da Generation Brasil.

O objetivo desta etapa é organizar uma base de dados fictícia sobre pacientes e atendimentos, preparando as informações para serem utilizadas em atividades futuras de análise de dados.

## Objetivo

Criar e organizar tabelas relacionadas aos pacientes e seus atendimentos, garantindo que as informações estejam estruturadas corretamente.

## Estrutura da base de dados

A base é composta por duas tabelas:

### 1. Pacientes

Tabela que reúne informações fictícias sobre os pacientes.

Principais informações:
- ID do paciente
- Nome ou código fictício
- Data de nascimento
- Sexo
- Bairro
- Tipo de convênio

### 2. Atendimentos

Tabela que reúne informações sobre os atendimentos realizados.

Principais informações:
- ID do atendimento
- ID do paciente
- Data e hora de chegada
- Sintoma principal
- Nível de triagem
- Tempo de espera
- Profissional responsável
- Desfecho do atendimento

## Relacionamento entre as tabelas

Um paciente pode ter vários atendimentos, mas cada atendimento está relacionado a um único paciente.

## Ferramentas utilizadas

- Python
- Google Colab
- Google Sheets
- Pandas
- Faker
- Gspread

## Etapas desenvolvidas

- [x] Preparação do ambiente no Google Colab.
- [x] Conexão com o Google Sheets.
- [x] Organização das tabelas.
- [x] Importação dos arquivos CSV.
- [x] Envio dos dados para o Google Sheets.
- [x] Validação da quantidade de registros e dos cabeçalhos.

## Cuidados com os dados

Todos os dados utilizados são fictícios. Nenhuma informação real de pacientes é utilizada neste projeto.

## Status

Em desenvolvimento.

---

Projeto desenvolvido como parte do Bootcamp de Análise de Dados — Generation Brasil © 2026
