---
name: n8n-workflow-builder
description: >
  Cria, documenta e estrutura fluxos (workflows) completos para o n8n, prontos para importar via JSON.
  Use esta skill SEMPRE que o usuário pedir para criar, montar, estruturar ou documentar um fluxo no n8n,
  automação de Instagram, WhatsApp, webhook, integração com Supabase, Evolution API, OpenAI/GPT,
  Kiwify, Cal.com ou qualquer outro serviço. Também use quando o usuário mencionar "fluxo", "workflow",
  "automação", "n8n", "webhook", "integração entre sistemas", "bot de atendimento", "agente de IA no n8n",
  "funil automatizado" ou "montar o fluxo". O output padrão é um JSON válido pronto para importar no n8n,
  acompanhado de explicação em linguagem simples de cada etapa.
---

# n8n Workflow Builder

## Stack padrão do usuário
- n8n self-hosted em VPS Hostinger (Ubuntu 22.04, Docker)
- Supabase como banco de dados
- Evolution API para WhatsApp
- Instagram Graph API para comentários e DMs
- OpenAI GPT-4o como modelo de IA
- Kiwify para produtos digitais
- Cal.com para agendamentos

## Estrutura padrão de workflow
GATILHO → VALIDAÇÃO/FILTRO → LÓGICA/IA → AÇÃO → REGISTRO

## Variáveis de ambiente padrão
OPENAI_API_KEY, EVOLUTION_API_URL, EVOLUTION_INSTANCE, EVOLUTION_API_KEY,
SUPABASE_URL, SUPABASE_KEY, LINK_KIWIFY, LINK_AGENDA

## Fluxos mapeados para o Dr. Moacir Maia
- instagram-comentarios
- instagram-dm
- whatsapp-mensagem
- follow-up-48h
- pos-compra-kiwify
- auditoria-periodica
