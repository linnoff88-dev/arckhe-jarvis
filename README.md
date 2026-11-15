# ðŸ¤– Jarvis â€” Seu Sistema Operacional de IA

Curso aberto, em portuguÃªs e **para leigos**, sobre Jarvis e sistemas operacionais de IA. Do "o que Ã©, afinal?" atÃ© montar o seu â€” no computador, no celular e atÃ© num brinquedo educativo.

**No ar:** https://inematds.github.io/jarvis/ Â· Parte do **[INEMA.CLUB](https://inema.club)**.

## As 6 trilhas

| # | Trilha | O que cobre |
|---|--------|-------------|
| ðŸŒ± T1 | **Fundamentos** | O que Ã© um Jarvis, o que Ã© um LLM, e quando a IA passa a agir. Sem prÃ©-requisitos. |
| ðŸ—ºï¸ T2 | **O Panorama** | Os sistemas que existem â€” OpenClaw, GravityClaw, Hermes, Intelecto, AIOS â€” e qual Ã© o caminho. |
| ðŸ§¬ T3 | **Anatomia** | As 6 camadas: canais, identidade, ferramentas, skills, agentes e cÃ©rebros (uma por mÃ³dulo). |
| ðŸ› ï¸ T4 | **Construir um Jarvis eficaz** | Da receita mÃ­nima Ã  arquitetura robusta (as 4 camadas: Context Â· Connections Â· Capabilities Â· Cadence). |
| ðŸ“± T5 | **Jarvis no celular** | Canais (Telegram/WhatsApp), voz (STT/TTS) e modelo local. Sem app de loja. |
| ðŸ§¸ T6 | **Jarvis para crianÃ§as** | Tutor socrÃ¡tico, persona, voz â€” e a seguranÃ§a inegociÃ¡vel. |

**21 mÃ³dulos Â· 126 tÃ³picos Â· ~18h.**

## Como foi construÃ­do

Pesquisa estruturada (web + dezenas de projetos reais) â†’ arquitetura â†’ 27 pÃ¡ginas no **formato-curso-v2** do INEMA, com verificaÃ§Ã£o por pÃ¡gina. Tudo documentado em **[doc/metodologia.html](doc/metodologia.html)** e no `_build/BIBLE.md`.

## Estrutura

```
index.html                 landing (as 6 trilhas + progresso do curso)
doc/metodologia.html       como o curso foi pesquisado e construÃ­do (transparÃªncia)
curso/trilhaN/index.html   Ã­ndice de cada trilha (mapa + mÃ³dulos)
curso/trilhaN/modulo-N-M.html  os 21 mÃ³dulos
assets/learn.css|js        camada de aprendizagem (progresso, jornada, temas) â€” self-contained
_build/                    kit de construÃ§Ã£o (templates + bible) â€” documentaÃ§Ã£o interna
```

100% estÃ¡tico (Tailwind via CDN + JS inline). Abre direto no navegador, sem build nem servidor.

---

Feito com â¤ï¸ pela comunidade **INEMA.CLUB**.

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe