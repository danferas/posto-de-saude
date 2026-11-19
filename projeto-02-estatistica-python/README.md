# Projeto 02 — Estatística com Python

## Sobre o projeto

Este é o segundo projeto da sequência com o tema **Posto de Saúde**, desenvolvido como parte do Bootcamp de Análise de Dados da Generation Brasil.

Nesta etapa, o foco foi utilizar estatística descritiva para analisar os dados de atendimentos de um posto de saúde fictício, buscando entender melhor o tempo de espera dos pacientes.

A principal pergunta da análise foi:

**Qual é o tempo médio de espera dos pacientes para serem atendidos no posto de saúde?**

## Sobre os dados

Os dados utilizados foram criados no Projeto 01 — Base de Dados. Eles representam uma simulação de pacientes e atendimentos em um posto de saúde.

A base é organizada em duas tabelas:

### 1. Tabela pacientes

Contém informações fictícias sobre os pacientes cadastrados.

| Coluna | Descrição |
|---|---|
| `paciente_id` | Identificador único do paciente |
| `nome_ficticio` | Nome fictício utilizado na simulação |
| `data_nascimento` | Data de nascimento |
| `sexo` | Sexo informado no cadastro |
| `bairro` | Bairro de residência |
| `tipo_convenio` | Tipo de convênio |

### 2. Tabela atendimentos

Contém informações sobre os atendimentos realizados no posto de saúde. Cada registro representa um atendimento, e um mesmo paciente pode aparecer mais de uma vez.

| Coluna | Descrição |
|---|---|
| `atendimento_id` | Identificador único do atendimento |
| `paciente_id` | Identificador do paciente relacionado ao atendimento |
| `data_hora_chegada` | Data e horário de chegada |
| `sintoma_principal` | Principal sintoma informado |
| `nivel_triagem` | Classificação de prioridade da triagem |
| `tempo_espera_min` | Tempo de espera em minutos |
| `profissional_responsavel` | Profissional responsável pelo atendimento |
| `desfecho` | Resultado ou encaminhamento do atendimento |

As duas tabelas se relacionam por meio da coluna `paciente_id`.

**Para esta análise, a informação principal é o tempo de espera**, registrado na coluna `tempo_espera_min`, da tabela `atendimentos`.

## Análises realizadas

Com Python e Pandas, os dados foram carregados e organizados em DataFrames para a realização das análises estatísticas.

Foram exploradas:

- **Medidas de tendência central:** média, mediana e moda.
- **Medidas de dispersão:** variância, desvio padrão e amplitude.
- **Quartis:** para observar a distribuição dos tempos de espera.
- **Comparação entre média e mediana:** para entender como valores muito altos podem influenciar a média.
- **Distribuição dos dados:** por meio de gráficos.
- **Valores extremos (outliers):** para identificar observações que se distanciam do comportamento geral dos dados.

## Tecnologias e ferramentas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Objetivo da análise

Utilizar estatística descritiva para compreender o comportamento dos tempos de espera, identificar variações entre os atendimentos e transformar os dados em informações que possam auxiliar na avaliação do funcionamento do posto de saúde.

## Observação

Todos os dados utilizados neste projeto são fictícios e foram criados exclusivamente para fins de estudo. Não foram utilizados dados reais de pacientes ou instituições de saúde.

## Status

Em desenvolvimento.

---

Desenvolvido durante o Bootcamp de Análise de Dados — Generation Brasil © 2026
