# 📞 Produto 3 — Sistema de Gerenciamento de Chamados

> **Sistema de chamados técnicos** com chat em tempo real, avaliação via WhatsApp e dashboards de performance

---

## Propósito

Transformar demanda em dado e dado em decisão. O sistema permite entender quando ocorrem picos de atendimento, quais demandas são mais recorrentes, quais setores mais acionam suporte e se são dúvidas operacionais, erros, falhas de processo ou falta de treinamento.

---

## Módulos

### Login
- Acesso via Google (equipe TI)
- Email e senha (usuários externos)
- Modo visitante (somente leitura)

### Dashboard de Indicadores
- **Atendimentos Internos**: 311 total | 307 finalizados | 2 pendentes | 1 agendado
- **Atendimentos Externos**: 6 total | 0 fila | 0 atendendo | 6 finalizados
- **Métricas por Setor Solicitante**: Frente de Loja (80), CRM/Fidelidade (36), Administrativo (32), Infraestrutura TI (19), Tecnologia (16), Padaria (15), Fiscal/Tributário (14)
- **Métricas por Setor Atendente**: Tecnologia (315 chamados, 1m espera, 4h25m conclusão)
- **Performance por Atendente**: Luciana (66, 100%), Maria Fernanda (57, 100%), Francisco (40, 100%)
- Filtro: Hoje | Semana | Mês

### Registro de Atendimento
- Abertura de chamados com status, ID, setor, solicitante, atendente
- Tempos rastreados: abertura, assumido, tempo espera, conclusão, lead time
- Chat em tempo real entre atendente e solicitante
- Opções: continuar conversa ou finalizar interação

### Avaliação (via WhatsApp)
- Link enviado automaticamente via WhatsApp após finalização
- Formulário com:
  - Nota geral do atendimento (1-5 estrelas)
  - Problema resolvido? (Sim/Não)
  - Velocidade do atendimento (Rápido/Normal/Lento)
  - Cordialidade do atendente (1-5 estrelas)
  - Observações (opcional)

### Dashboard de Avaliações e Rankings
- **NPS Score**: 60 (Excelente)
- **Satisfação Média**: 4.6/5
- **Taxa de Resposta**: 45%
- **Problemas Resolvidos**: 100%
- **Atendente mais Veloz**: ranking por tempo médio de conclusão
- **Atendente mais Gente Boa**: ranking por cordialidade
- **Top 3 do Mês**: ranking geral

### Análise por Hora/Dia/Semana/Ano
- Atendimentos por hora (pico: 14h, média: 1.6/hora)
- Atendimentos por dia da semana (total: 317, média: 45.3/dia)
- Atendimentos por mês (média: 26.4/mês)
- Distribuição por origem (98% internos, 2% externos)
- Distribuição por status (99% finalizado)
- Top 10 setores solicitantes

---

## Dor que Resolve
- Atendimento desorganizado e sem rastreabilidade
- Avaliação subjetiva da equipe de TI
- Falta de dados para justificar promoções ou ampliação de equipe
- Demandas recorrentes que poderiam virar treinamento

## Argumento para Comunidade
> "Você sabe quanto tempo sua equipe de TI demora pra resolver um chamado? Com dados, você para de apagar incêndio e começa a prevenir."
