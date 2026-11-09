# Smart Operations Analytics 🚧

> **Status:** em desenvolvimento | *in progress*

Projeto de análise de dados de ponta a ponta para uma **indústria fictícia do setor automotivo** que enfrenta atrasos nas entregas, custos logísticos crescentes, falta ou excesso de estoque e pouca visibilidade sobre seus indicadores operacionais.

O objetivo é centralizar dados de pedidos, produção, estoque, fornecedores e clientes para identificar gargalos, monitorar KPIs e antecipar problemas com previsão de demanda.

**Ferramentas:** Python · pandas · SQL · Power BI · DAX

<details>
<summary>🌎 <b>English</b></summary>
<br>

End-to-end data analytics project for a **fictional automotive manufacturer** facing late deliveries, rising logistics costs, stockouts or overstock, and low visibility of its operational KPIs. The goal is to bring together orders, production, inventory, supplier and customer data to identify bottlenecks, monitor KPIs and anticipate problems with demand forecasting.

**Tools:** Python · pandas · SQL · Power BI · DAX

</details>

---

## 🗺️ Etapas do projeto

- [ ] **Tratamento dos dados (Python):** leitura, análise de nulos, duplicidades e inconsistências *(em andamento)*
- [ ] **Modelagem (SQL):** modelo dimensional com fato de pedidos e dimensões de produtos, clientes, fornecedores e calendário
- [ ] **Dashboard (Power BI):** visão executiva, operações e análise detalhada
- [ ] **Previsão de demanda:** sazonalidade, risco de ruptura de estoque e previsto vs. real

## 📈 KPIs planejados

| Indicador | Objetivo |
|---|---|
| OTIF (%) | Entregas no prazo e completas |
| Lead Time | Tempo entre pedido e entrega |
| Inventory Turnover | Eficiência do estoque |
| Stockout Rate | Falta de produtos |
| Forecast Accuracy | Precisão da previsão de demanda |
| Cost per Order | Custo operacional por pedido |

---

## 📂 Dados

Base **sintética**, criada para fins de portfólio. Não contém dados reais de empresas ou pessoas.

- Período: 01/01/2024 a 31/12/2025
- `dim_products.csv`: atributos dos produtos/SKUs
- `dim_suppliers.csv`: fornecedores e lead time
- `dim_customers.csv`: segmentos e regiões dos clientes
- `fact_orders.csv`: pedidos e entregas
- `fact_production.csv`: produção planejada vs. realizada
- `fact_inventory_monthly.csv`: posição mensal de estoque
- `data_dictionary.xlsx`: dicionário de dados

Algumas tabelas têm, de propósito, problemas de qualidade (valores ausentes, capitalização inconsistente, quantidades zeradas e pedidos duplicados). O tratamento de cada um será documentado no projeto.

> Como os dados são sintéticos, os resultados não representam uma operação real.
