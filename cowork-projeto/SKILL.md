# SKILL.md — Comunidade WhatsApp Supermercados

## Objetivo
Publicar automaticamente postagens na comunidade de WhatsApp de donos de supermercado, seguindo o calendário editorial de 12 semanas (24 postagens no total).

## Frequência
- **Terça-feira** às 7h da manhã
- **Quinta-feira** às 12h (meio-dia)

## Como funciona

### 1. Identificar a próxima postagem
- Leia o arquivo `controle.txt` nesta pasta
- Identifique a primeira linha que tenha status `PENDENTE`
- O arquivo de postagem correspondente está na pasta `postagens/`

### 2. Preparar a postagem
- Abra o arquivo da postagem (ex: `postagens/semana01-terca.txt`)
- O conteúdo já está pronto para envio — NÃO altere o texto
- Se a postagem indica `[IMAGEM: caminho]`, localize a imagem na pasta `imagens-postagens/`

### 3. Enviar no WhatsApp
- Abra o WhatsApp Web ou WhatsApp Desktop (já deve estar logado)
- Navegue até a **Comunidade** chamada "Supermercados — MS Consultoria" (ou o nome que o Maicou definiu)
- Clique no canal de avisos/anúncios da comunidade
- Se a postagem tem imagem: envie a imagem primeiro, depois cole o texto como legenda
- Se a postagem é só texto: cole o texto e envie
- Aguarde confirmação de envio (tique azul ou confirmação visual)

### 4. Atualizar o controle
- Volte ao arquivo `controle.txt`
- Altere o status da postagem enviada de `PENDENTE` para `ENVIADO`
- Adicione a data e hora real do envio

## Regras importantes
- NUNCA envie mais de 1 postagem por vez
- NUNCA altere o texto das postagens
- NUNCA envie fora da comunidade (não enviar em grupos ou conversas individuais)
- Se o WhatsApp não estiver logado, NÃO tente fazer login — apenas informe o Maicou
- Se não encontrar a comunidade, NÃO crie uma nova — apenas informe o Maicou
- Após enviar, sempre atualize o controle.txt

## Estrutura de arquivos
```
cowork-projeto/
├── SKILL.md (este arquivo)
├── controle.txt (controle de postagens — qual foi enviada, qual é a próxima)
├── postagens/
│   ├── semana01-terca.txt
│   ├── semana01-quinta.txt
│   ├── semana02-terca.txt
│   ├── ... (24 arquivos no total)
│   └── semana12-quinta.txt
└── imagens-postagens/
    ├── semana01-quinta-excesso.png
    ├── semana02-quinta-acompanhamento-cliente.png
    ├── ... (imagens que acompanham as postagens)
```

## Sobre o projeto
- **Dono:** Maicou Andrade — MS Consultoria
- **Público:** Donos de supermercado e atacarejo no Nordeste
- **Tom:** Direto, prático, com dados reais. Sem enrolação.
- **Objetivo:** Gerar interesse nos produtos da MS Consultoria através de conteúdo de valor
