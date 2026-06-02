# 💻 Dashboard de Manutenção de Equipamentos - Setor de TI (Power BI)

## 📌 Sobre o Projeto
Este projeto foi desenvolvido como **objeto de estudo em Power BI**, com o objetivo de simular uma solução analítica para uma empresa fictícia no setor de TI, com foco no acompanhamento da manutenção de equipamentos.

O dashboard foi estruturado para consolidar indicadores operacionais importantes e oferecer uma visão gerencial sobre falhas, tempo de parada e desempenho da equipe responsável pelas ocorrências.

A proposta do relatório é transformar dados de chamados e manutenções em informações visuais que apoiem o monitoramento da confiabilidade dos equipamentos e da eficiência dos reparos. Para isso, foram utilizados indicadores como quantidade de paradas, total de equipamentos com falha, MTBF e MTTR.

## 🎯 Objetivos do Dashboard
O dashboard foi desenvolvido para atender às seguintes necessidades de análise:

- Monitorar a quantidade de paradas registradas nos equipamentos
- Identificar quantos equipamentos apresentaram falhas no período analisado
- Avaliar o MTBF (Mean Time Between Failures), indicador que mede o tempo médio entre falhas
- Avaliar o MTTR (Mean Time To Repair), indicador que mede o tempo médio necessário para reparar um equipamento após uma falha
- Permitir análises por equipamento, ocorrência, operador e período

## 🖼️ Preview do Dashboard

<img width="1793" height="1006" alt="image" src="https://github.com/user-attachments/assets/71871e61-1929-42ca-9bd4-7e6b5e5487c3" />

## 📊 Principais Análises

### 📉 Paradas e Falhas
O dashboard apresenta indicadores voltados ao volume de paradas e à quantidade de equipamentos que falharam, permitindo identificar ativos com maior recorrência de ocorrência.

### ⏱️ MTBF e MTTR
O relatório inclui os indicadores **MTBF** e **MTTR**, amplamente usados em manutenção para acompanhar confiabilidade e eficiência operacional.

### 📅 Linha do Tempo das Ocorrências
Os gráficos temporais permitem acompanhar a evolução das falhas e das horas paradas ao longo do tempo, facilitando a identificação de períodos críticos e padrões de recorrência.

### 🏷️ Detalhamento por Equipamento e Operador
O dashboard também organiza informações por ID e tag de equipamento, além de apresentar falhas por tipo e por operador em tabela analítica.

### 🔎 Filtros e Escalabilidade
O painel conta com filtros por ano, mês, equipamento, ocorrência e operador. Atualmente, a base contém registros de 2020, mas a estrutura foi pensada para comportar anos subsequentes, permitindo escalabilidade conforme o histórico operacional evoluir.

## 🛠️ Tecnologias Utilizadas
- Power BI
- Power Query
- Modelagem de Dados
- DAX

## 📂 Estrutura do Repositório
Este repositório contém:
- Arquivo `.pbix` com o dashboard completo
- Base de dados em Excel utilizada para coleta e estruturação das informações
- Arquivo `.svg` com o background aplicado no relatório

## 🔗 Acesse ao Dashboard
Você pode visualizar o dashboard completo através do link abaixo:

[https://app.powerbi.com/view?r=eyJrIjoiZmI5ODhlNGMtNDIzOS00MGY2LTlkYjAtNzAwODI5OWEzMzdiIiwidCI6IjA1NWY2NTI1LWE1MjQtNGRiNi04NjE4LThiOGRjZjgzODE1YSJ9](https://app.powerbi.com/view?r=eyJrIjoiZmI5ODhlNGMtNDIzOS00MGY2LTlkYjAtNzAwODI5OWEzMzdiIiwidCI6IjA1NWY2NTI1LWE1MjQtNGRiNi04NjE4LThiOGRjZjgzODE1YSJ9)

## 💡 Aprendizados Aplicados
Este projeto permitiu aprofundar a aplicação de conceitos de análise de dados voltados à manutenção e confiabilidade de ativos, especialmente na construção de indicadores usados para monitorar falhas, tempo de reparo e disponibilidade operacional.

Também reforçou a prática de desenvolver dashboards com foco em leitura executiva, segmentação de dados e estrutura escalável para crescimento futuro da base analisada.
