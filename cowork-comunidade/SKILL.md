# SKILL.md — Comunidade WhatsApp de Donos de Supermercado

## Objetivo
Publicar automaticamente as postagens da comunidade de WhatsApp para donos de supermercado e atacarejo, seguindo o calendário editorial de 12 semanas.

## Frequência
- **Terça-feira às 7h**: postagem tipo Provocação (gera identificação com a dor)
- **Quinta-feira às 12h**: postagem tipo Case/Bastidor/Oferta (mostra a prova ou solução)

## Como Executar

### Passo 1 — Identificar a próxima postagem
1. Leia o arquivo `controle.md` nesta pasta
2. Identifique qual é a próxima postagem com status `pendente`
3. Anote o número da semana, o dia (terça ou quinta) e o arquivo correspondente

### Passo 2 — Ler o conteúdo da postagem
1. Abra o arquivo da postagem na pasta `postagens/` (ex: `semana01-terca.txt`)
2. O conteúdo já está pronto para envio — NÃO modifique o texto

### Passo 3 — Publicar no WhatsApp Web
1. Abra o Chrome e acesse o WhatsApp Web (https://web.whatsapp.com)
2. Aguarde carregar completamente
3. Na barra de pesquisa de conversas, busque pelo nome da comunidade: **"Comunidade Supermercados MS"**
4. IMPORTANTE: Verifique que está abrindo a COMUNIDADE (canal de difusão), não um grupo ou conversa individual
5. Clique na comunidade para abrir
6. Cole o texto da postagem no campo de mensagem
7. Envie a mensagem

### Passo 4 — Atualizar o controle
1. Abra o arquivo `controle.md`
2. Mude o status da postagem enviada de `pendente` para `enviado`
3. Adicione a data e hora do envio
4. Salve o arquivo

## Regras Importantes
- NUNCA envie mais de 1 postagem por vez
- NUNCA modifique o texto das postagens
- Se o WhatsApp Web pedir QR Code, PARE e notifique o usuário
- Se a comunidade não for encontrada, PARE e notifique o usuário
- Se houver qualquer erro, registre em `controle.md` na coluna de observações e notifique o usuário
- O nome da comunidade pode ser ajustado pelo usuário no campo abaixo

## Configuração

```
NOME_DA_COMUNIDADE=Comunidade Supermercados MS
```

> **IMPORTANTE**: O usuário deve alterar o nome acima para o nome exato da sua comunidade no WhatsApp antes de agendar a primeira tarefa.
