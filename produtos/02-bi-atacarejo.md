# 📊 Produto 2 — BI para Atacarejo

> **Apresentação MS Consultoria**
> Business Intelligence completo para gestão de supermercados e atacarejos

---

## Contexto

Projeto que promoveu uma virada cultural baseada no conceito de **compra consciente orientada por dados**. A lógica anterior era comprar com base no que o RP mostrava naquele momento. A nova premissa: para comprar bem, é preciso entender profundamente o que se vende, como se vende e por que se vende.

Estruturado para operações de grande volume — empresas que faturam cerca de **R$ 90 milhões/mês (~R$ 1 bilhão/ano)**, com ticket médio em torno de R$ 250. Arquitetura baseada em **data warehouse** com extração de madrugada, sem impactar a operação.

**100% automatizado**, sem custo adicional e sem necessidade de equipe dedicada.

---

## Módulos

### PERFORMANCE

#### Evolução de Performance
- Acompanhamento mês a mês (ano anterior vs ano atual) com variação
- Indicadores selecionáveis: Cesta Média, Cupom, Itens/M², Lucro, Margem, RCV, Ticket Médio, Venda
- Gráfico com barras comparativas + linha de variação percentual

#### Dashboard de Performance
- **Receita Bruta**: R$ 3.096.263 (Meta: R$ 3.650.207 | YoY: -1,7%)
- **Margem Sem Oferta**: 35,50% (Meta: 37% | YoY: 5,40%)
- **Lucro Bruto**: R$ 956.030 (Meta: R$ 1.204.004 | YoY: 3,92%)
- **Cupons**: 64.272 (Meta: 82.539 | YoY: -14,34%)
- **Índice de Perdas**: -1158,57% (Meta: 1,00%)
- **Compras**: R$ 2.290.596 (Meta: R$ 2.140.233 | YoY: -4,98%)
- **Margem Com Oferta**: 16,76% (Meta: 19%)
- **Venda/M²**: R$ 2.064,18 (M²: 1.500 | Meta: 3.000)
- **Qtd. Vendida**: 407.378 (Meta: 472.311)
- **Cobertura Estoque**: 33,57 dias (Meta: 25 dias)
- **RCV**: 73,98% (Meta: 69,12%)
- **Venda Sem Oferta**: R$ 2.332.224 (Part. 75,32%)
- **Itens Vendidos/M²**: 5,08 (Meta: 10)
- **Ticket Médio**: R$ 48,17 (Meta: R$ 46,15 | YoY: 14,8%)
- **Ruptura Curva AB**: 9,90% (Meta: 3,50%)
- **Margem Sobre Venda**: 30,88% (Meta: 31,87%)
- **Venda Com Oferta**: R$ 764.039 (Part. 24,68%)
- **Venda/Funcionário**: R$ 6.881 (Func.: 450 | Meta: 35.000)
- **Cesta Média**: 6,34 (Meta: 6,29)
- **Sem Venda +30 Dias**: R$ 346.906 (3.161 itens)

---

### VENDAS

#### Checkout
- Indicadores por loja (cupons, variação anual, qtd vendida, ticket médio, cesta média)
- Distribuição por faixa de ticket (até R$20: 22.542 | R$20-50: 21.093 | R$50-80: 9.332 | etc.)
- Comportamento semanal (ticket médio, vendas R$, volume, cesta média por dia da semana)

#### Comparativo
- Período anterior vs atual com variação:
  - Venda R$: R$ 3.100.787 → R$ 2.966.357 (-4,3%)
  - Margem: 30,8% → 31,9% (+3,6%)
  - Lucro: R$ 955.849 → R$ 947.085 (-0,9%)
  - Ticket Médio: R$ 42 → R$ 47 (+11,4%)
  - Cupons: 73.391 → 63.002 (-14,2%)
- Detalhamento por setor com venda, margem, lucro e variações

#### Rentabilidade
- Impacto das ofertas: Total R$ 3.096.263 | Sem Oferta R$ 2.332.224 (35,5%) | Com Oferta R$ 764.039 (16,8%)
- Desempenho por setor e por produto
- Análise por curva (A: 29,08% margem | B: 37,83% | C: 38,94% | D: 42,81%)

#### Vendas
- Análise completa com meta por setor
- Performance de venda, diferença de meta, variação ano
- Margem vs meta de margem
- Lucro vs meta de lucro
- Venda sem oferta e com oferta por setor

---

### ESTOQUE

#### Compras
- Valor Venda: R$ 3.096.263
- CMV: R$ 2.140.233
- Margem: 30,88%
- Valor Compra: R$ 2.290.596
- Performance Orçado: 7,0%
- RCV: 73,98%
- Compra sobre Custo (RCC): 107,03%
- Detalhamento por setor e por fornecedor

#### Excesso
- Excesso Total: R$ 1.215.272 (54,89% do estoque)
- Excesso Perecíveis: R$ 140.007 (28,9%)
- Excesso Não Perecíveis: R$ 890.167 (51,5%)
- Detalhamento por setor com DDV, giro diário, custo unitário

#### Ruptura
- GAP Venda: R$ 547.279
- GAP Lucro: R$ 193.061
- Ruptura por curva (A: 3,6% | B: 5,5% | C: 6,8% | D: 5,1%)
- Meta ruptura: 4,25%
- Detalhamento por setor com giro diário, pedidos, última venda/entrada

#### Sem Giro
- GAP Venda: R$ 917.004
- GAP Lucro: R$ 266.039
- Estoque Valor: R$ 898.458
- 4.347 itens sem venda
- DSV (Dias Sem Venda) >10: R$ 432.070
- Detalhamento por setor

#### Reposição
- Alerta de Reposição: 2.124 itens
- 254 fornecedores envolvidos
- Sugestão de Compras: 61.683 unidades (R$ 325.072)
- Alertas por curva (A: 368 | B: 459 | C: 329 | D: 968)
- Detalhamento por setor e por fornecedor com sugestão

#### Prevenção
- Quebra/Perda: R$ -120.661 (Part. -3,90%)
- Ajuste Inventário: R$ -39.087.158
- Perda Total: R$ -35.872.401 (Meta: 1,00%)
- Consumo Interno: R$ 1.451
- Acuracidade: 0,2% (Meta: 95,0%)
- Detalhamento por categoria

---

### GESTÃO
- Controle de usuários com limitação de dados por perfil

---

## Filtros Disponíveis (todos os módulos)
- Oferta, Loja, Mercadológico, Curva, Tipo de Venda, Fornecedor, Comprador, Custo (NF)
- Período personalizável

---

## Dor que Resolve
- Compras no achismo sem análise de dados
- Capital parado em excesso de estoque
- Ruptura sem visibilidade do impacto financeiro
- Falta de indicadores para tomada de decisão
- Perdas e quebras sem rastreabilidade

## Argumento para Comunidade
> "Quanto de dinheiro parado você tem em estoque agora sem saber? Um atacarejo descobriu R$ 1,2 milhão em excesso e R$ 917 mil em produtos sem giro — tudo invisível antes do BI."
