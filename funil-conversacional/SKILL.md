---
name: funil-conversacional
description: >
  Cria, revisa e otimiza scripts de conversa para funis automatizados via DM, WhatsApp ou chat,
  incluindo mensagens de abertura, qualificação, oferta, follow-up, pós-venda e tratamento de
  objeções. Use esta skill SEMPRE que o usuário pedir para escrever mensagens de funil, criar
  scripts de conversa automatizada, montar o fluxo de mensagens de um bot, escrever DMs de
  captação, criar mensagens de follow-up, ou estruturar a conversa de um agente de IA.
  Também use quando mencionar "script do bot", "mensagens do funil", "o que o agente fala",
  "sequência de mensagens", "conversa automatizada", "DM de abertura", "follow-up automático"
  ou "copy do WhatsApp".
---

# Funil Conversacional

## Filosofia
Funis que convertem não parecem funis. Parecem conversas reais.

## Estratégia de Conexão em 3 Etapas
1. ESPELHO DO POST — referenciar o conteúdo que gerou a interação
2. NOMEAÇÃO DO BLOQUEIO — nomear o que a pessoa está sentindo antes de perguntar
3. PERGUNTA EMOCIONAL — sobre o que ela sente, não sobre histórico clínico

## Estrutura do fluxo
TURNO 1 (bot): conexão + nomeação + pergunta emocional
TURNO 2 (lead): responde sobre situação
TURNO 2 (bot): empatia + validação + qualificação suave
TURNO 3 (lead): mais detalhes
TURNO 3 (bot): validação + produto certo + CTA
TURNO 4+: objeção / reforço / fechamento

## Templates principais

### Abertura — lead frio
"Oi {{nome}} 🌿 Aqui é o Dr. Moacir.
Eu acho inadmissível uma mulher que quer resultado ficar meses tentando
sem ninguém explicar o que está travando seu corpo.
Não é falta de esforço — é emagrecimento bloqueado, e tem solução.
Me conta: o que mais te incomoda hoje?"

### Follow-up 48h
"Oi {{nome}} 👋 Dr. Moacir aqui.
Não quero te encher de mensagem — mas não ia ficar quieto
sabendo que posso ajudar. O que travou? 🌿"

### Pós-compra 7 dias
"Oi {{nome}}! Como está sendo o guia? 🌿
Se tiver dúvida sobre as fórmulas, me chama aqui.
E se quiser um protocolo personalizado, tenho horários essa semana. 📅"

## Regras de escrita
- Máximo 3 parágrafos por mensagem
- Uma pergunta por vez
- Nomear antes de perguntar
- CTA claro e único
- Emojis com moderação: 🌿 💚 📅 👋

## Classificação de lead (para n8n)
[LEAD_STATUS: TOPO | MEIO | FUNDO | CLIENTE | SUPORTE]
