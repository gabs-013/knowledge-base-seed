---
type: map
title: Mapa da Knowledge Base
description: Porta de entrada da base — estrutura, ordem de leitura e as decisões fundadoras.
tags: [mapa, navegacao]
timestamp: 2026-11-16
related:
  - 01_tese.md
  - 02_lexico.md
  - ../09-operacao/00_schema.md
  - ../../STATE.md
---

# Mapa da KB — Gabriel Martins

> Comece por aqui. Este é o documento canônico de navegação da base.

## As decisões fundadoras

- **Objeto:** histórico profissional e portfólio de Gabriel Martins.
- **Públicos:** recrutadores e contratantes; IAs que consultam a base para responder sobre o perfil.
- **Camadas:** duas. A base pública alimenta outras IAs; o que entra nelas segue a regra de
  promoção de [separação de camadas](../09-operacao/02_separacao-de-camadas.md).
- **Privacidade:** pública — nunca entra: telefone, e-mail, endereço, documentos (CPF/RG,
  currículos em PDF, contratos), pretensão salarial e dados pessoais de terceiros sem consentimento.
- **Manutenção:** PR por sessão; merge automático dentro do escopo do portfólio, após
  `scripts/audit-kb.py` passar (ver `AGENTS.md`).
- **Agentes:** Claude e Codex.
- **Frontmatter:** rico (ver [schema](../09-operacao/00_schema.md)).
- **Ingestão de calls:** sim, usa `projeto/`.

## Estrutura

- `01-base/` — fundação: tese, léxico, entidades
- `02-conteudo/` — histórico profissional e portfólio
- `09-operacao/` — governança da própria base: schema, camadas, ingestão
- `views/` — trilhas de leitura por público
- `type/` — tipos de nota como lente
- `projeto/` — operação viva: inbox, decisões, logs, handoffs

## Ordem de leitura sugerida

1. Este mapa
2. [Estado atual](../../STATE.md)
3. [Tese](01_tese.md)
4. [Léxico](02_lexico.md)
5. [Entidades](03_entidades.md)
6. [Histórico profissional](../02-conteudo/historico/00_mapa.md)
7. [Portfólio](../02-conteudo/portfolio/00_mapa.md)
