# 🏨 Produto 8 — Sistema de Controle de Hospedagem

> Gestão completa de hospedagem corporativa com controle de hotéis, alocação de quartos, aprovações e custos

---

## Módulos

### Painel Geral
- 10 hotéis | 1 casa | 26 colaboradores
- Status dos pedidos: Pendentes (0) | Em Andamento (1) | Concluídos (3) | Rejeitados (0)
- Atividades recentes: alocações e reversões de quartos com log completo

### Cadastros

#### Colaboradores
- 26 cadastrados (16 masculino, 10 feminino)
- Dados: nome, CPF, sexo, nascimento, telefone, email
- Vínculo profissional: setor, cargo, loja
- Flag "Gestor da Área" (aprovam pedidos de hospedagem)
- Autenticação: Email+Senha ou Google

#### Operadores
- Responsáveis pela alocação de quartos

#### Setores
- Departamentos da empresa

#### Lojas
- Unidades da rede

#### Hotéis
- 10 hotéis ativos em 7 cidades (RN e CE):
  - Hertz Hotel (Pau dos Ferros-RN)
  - Hotel Anízio (Pau dos Ferros-RN)
  - Hotel Bezerra (Limoeiro do Norte-CE)
  - Hotel Classic (Limoeiro do Norte-CE)
  - Hotel Mariana (Morada Nova-CE)
  - Hotel Posto Santa Rita (São Miguel-RN)
  - Hotel Serrano (São Miguel-RN)
  - Monólitos (Quixadá-CE)
  - Pousada Nascer do Sol (Açu-RN)
- Categorias de quartos com preço/noite:
  - Simples Dup (2 pessoas): R$ 180
  - Simples Ind (1 pessoa): R$ 120
  - Simples Trip (3 pessoas): R$ 240
  - Suíte Dup (2 pessoas): R$ 210
  - Suíte Ind (1 pessoa): R$ 150
  - Suíte Tri (3 pessoas): R$ 270

#### Casas
- Imóveis próprios para hospedagem

### Lançamento de Hospedagem

#### Pedido de Hospedagem
- Abertura de pedido com colaborador, destino, datas, dias

#### Painel do Operador
- Fluxo: Aguardando → Aprovação Gestor → Em Contato → Alocar → Reservas
- Alocação: seleção de hotel, categoria do quarto, nº reserva, operador responsável, observações
- Verificação de ocupação no período antes de alocar

#### Ocupação Visual
- Visualização gráfica da ocupação dos quartos

### Acompanhamentos
- Rastreamento completo do fluxo de hospedagem

### Relatórios e Indicadores
- Total de Pedidos: 4
- Pedidos Concluídos: 3 (75%)
- Pedidos Urgentes: 0
- Custo Total de Quartos: R$ 4.171,05 (3 reservas, 15 diárias)
- Distribuição por status (pizza)
- Top destinos (gráfico de barras)
- Evolução mensal de pedidos (12 meses)
- Filtros: 30d | 90d | 180d | 365d | Tudo

### Relatório Swile (Alimentação)
- 20 diárias totais
- Controle por colaborador: cargo, dias hotel, dias casa
- Diária hotel e diária casa por cargo
- Total hotel + total casa + total geral
- Resumo por status: Aguardando Gestor | Aprovado | Rejeitado | Em Andamento | Concluído

---

## Dor que Resolve
- Hospedagem corporativa sem controle de custos
- Reservas feitas por telefone sem rastreabilidade
- Falta de aprovação gerencial para gastos com diárias
- Sem visibilidade de quanto cada colaborador/setor gasta

## Argumento para Comunidade
> "Quanto sua empresa gasta com hospedagem por mês? Sem controle, o custo escala sem ninguém perceber. Esse sistema dá visibilidade total com aprovação gerencial."
