graph TD
    A[Dataset CSV] -->|Extração| B(Python / Pandas)
    B -->|Limpeza e Transformação| C{Tratamento de Dados}
    C -->|Carga / Insert| D[(MySQL - Data Warehouse)]
    D -->|Conexão DirectQuery/Import| E[Power BI]
    E -->|Visualização| F(Dashboard e KPIs Regionais)
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#e6e6e6,stroke:#b20000,stroke-width:2px
    style D fill:#b20000,stroke:#fff,stroke-width:2px,color:#fff
