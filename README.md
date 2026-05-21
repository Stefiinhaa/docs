 # 📊 Observatório de Desempenho e Saúde Mental Estudantil

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Fase%201%20Concluída-b20000?style=for-the-badge)

## 📌 Sobre o Projeto
Projeto Integrador Extensionista focado em extrair, tratar e analisar dados educacionais simulando o cenário da nossa região. O objetivo é cruzar métricas de rotina (horas de sono, moradia) com foco e nota final, ajudando instituições de ensino a prevenir o *Burnout* acadêmico.

## 🗂️ Arquitetura e Fluxograma
Abaixo, o fluxo de dados desenhado para este projeto:

```mermaid
graph TD
    A[Base CSV] --> B(Tratamento em Python)
    B --> C[(MySQL)]
    C --> D[Power BI]
