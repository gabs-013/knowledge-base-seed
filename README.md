# Gabriel Martins — Knowledge Base

Base pública, em Markdown e versionada no Git, com o histórico profissional e o portfólio de
Gabriel Martins. Feita para recrutadores lerem diretamente e para IAs consultarem com contexto.

## Por onde começar

- **Recrutadores:** [trilha de começo](views/00_comece-por-aqui.md)
- **Agentes de IA:** [AGENTS.md](AGENTS.md) e [trilha para agentes](views/01_para-agentes.md)
- **Estado atual:** [STATE.md](STATE.md)

## Estrutura

```text
docs/01-base/     fundação: mapa, tese, léxico, entidades
docs/02-conteudo/ histórico profissional e portfólio
docs/09-operacao/ governança da base: schema, camadas, ingestão
views/            trilhas de leitura por público
type/             tipos de nota como lente de navegação
projeto/          operação viva: inbox, decisões, logs, handoffs
scripts/          auditoria e ingestão
STATE.md          estado atual
AGENTS.md         instruções para agentes
CONTRIBUTING.md   fluxo de contribuição
```

## Privacidade

Esta base é pública. Contato (telefone, e-mail, endereço) e documentos pessoais não entram aqui.
Os números apresentados são autorreportados, salvo quando indicado o contrário.

## Atualização

Mudanças entram por Pull Request e passam pela auditoria `python3 scripts/audit-kb.py`.
