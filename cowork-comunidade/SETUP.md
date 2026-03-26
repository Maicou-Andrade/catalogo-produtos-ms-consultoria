# Como Configurar no Cowork — Passo a Passo

## 1. Preparar a Pasta Local

Clone o repositório ou copie a pasta `cowork-comunidade` para um local no seu computador, por exemplo:

```
C:\Users\SeuNome\Documents\comunidade-whatsapp\
```

ou no Mac:

```
/Users/SeuNome/Documents/comunidade-whatsapp/
```

A pasta deve conter:
```
comunidade-whatsapp/
├── SKILL.md              ← Instruções para o Cowork
├── controle.md           ← Controle de postagens (pendente/enviado)
├── SETUP.md              ← Este arquivo
└── postagens/
    ├── semana01-terca.txt
    ├── semana01-quinta.txt
    ├── semana02-terca.txt
    ├── ...
    └── semana12-quinta.txt
```

## 2. Criar o Projeto no Cowork

1. Abra o **Claude Desktop App**
2. Vá na aba **Cowork**
3. Clique em **Projects** (barra lateral esquerda)
4. Clique em **Novo Projeto**
5. Nome: **Comunidade WhatsApp — Supermercados**
6. Aponte para a pasta que você criou no passo 1
7. O Cowork vai ler automaticamente o SKILL.md

## 3. Ajustar o Nome da Comunidade

Antes de agendar, abra o arquivo `SKILL.md` e altere a linha:

```
NOME_DA_COMUNIDADE=Comunidade Supermercados MS
```

Coloque o **nome exato** da sua comunidade no WhatsApp.

## 4. Garantir que o WhatsApp Web está Conectado

1. Abra o Chrome
2. Acesse https://web.whatsapp.com
3. Escaneie o QR Code se necessário
4. Deixe a sessão ativa (o Chrome pode ficar aberto em segundo plano)

## 5. Criar as Tarefas Agendadas

No Cowork, dentro do projeto, crie **2 tarefas agendadas**:

### Tarefa 1 — Terça-feira

No Cowork, clique em **Tarefas Agendadas** e configure:

**Nome:** Postagem Terça — Comunidade WhatsApp
**Quando:** Toda terça-feira às 07:00
**Instrução:**

```
Leia o SKILL.md para entender o processo. Depois leia o controle.md e identifique a próxima postagem de TERÇA com status "pendente". Abra o arquivo correspondente na pasta postagens/. Copie o texto. Abra o Chrome, acesse o WhatsApp Web, busque a comunidade pelo nome configurado no SKILL.md, e envie a mensagem. Depois atualize o controle.md marcando como "enviado" com a data e hora.
```

### Tarefa 2 — Quinta-feira

**Nome:** Postagem Quinta — Comunidade WhatsApp
**Quando:** Toda quinta-feira às 12:00
**Instrução:**

```
Leia o SKILL.md para entender o processo. Depois leia o controle.md e identifique a próxima postagem de QUINTA com status "pendente". Abra o arquivo correspondente na pasta postagens/. Copie o texto. Abra o Chrome, acesse o WhatsApp Web, busque a comunidade pelo nome configurado no SKILL.md, e envie a mensagem. Depois atualize o controle.md marcando como "enviado" com a data e hora.
```

## 6. Requisitos para Funcionar

- O computador precisa estar **ligado e acordado** nos horários agendados
- O **Claude Desktop App** precisa estar **aberto**
- O **Chrome** precisa ter **WhatsApp Web conectado**
- O **plano Max** garante uso suficiente para as 2 tarefas semanais

## 7. Acompanhamento

A cada envio, o Cowork atualiza o `controle.md`. Você pode abrir esse arquivo a qualquer momento pra ver o que já foi enviado e o que está pendente.

Após as 12 semanas (24 postagens), o ciclo termina. Aí você pode:
- Reiniciar com novos textos e ângulos diferentes
- Repetir o mesmo ciclo com ajustes baseados no engajamento
- Me pedir para criar um novo ciclo de 12 semanas
