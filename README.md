# 📈 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Este projeto tem como objetivo oferecer uma ferramenta prática desenvolvida em Excel para simular investimentos em Fundos Imobiliários (FIIs). A planilha permite ao usuário inserir dados como aporte inicial, aportes mensais, taxa de rendimento e tempo de investimento, retornando o valor investido, o patrimônio acumulado e os dividendos mensais estimados.

## 🎯 Objetivo

Facilitar o planejamento financeiro e a tomada de decisões de investidores interessados em Fundos Imobiliários, automatizando cálculos financeiros e visualizando resultados projetados ao longo do tempo.

## 📌 Funcionalidades

- Entrada de dados personalizada:
  - Aporte inicial
  - Aporte mensal
  - Taxa de rendimento mensal (%)
  - Duração do investimento (em meses)

- Cálculos automáticos:
  - Total investido
  - Patrimônio acumulado com reinvestimento
  - Dividendos mensais estimados

- Gráficos:
  - Evolução do patrimônio
  - Evolução dos dividendos mensais

## 🧠 Fórmulas Utilizadas no Excel

- **Valor Futuro (VF):**  
  ```excel
  =VF(taxa; períodos; -aporte_mensal; -aporte_inicial)
