# TransiÃ§Ã£o para o Claude Code â€” Plano do Curso

**courseId:** `claude-code`
**Emoji:** ðŸ¤–
**Formato:** ARCKHÉ v2 (dark premium + camada de aprendizagem)
**Base:** infogrÃ¡fico "Track Your Transition Into Claude Code" (12 semanas, 234 tasks)

---

## Estrutura: 5 Trilhas Ã— 6 MÃ³dulos = 30 MÃ³dulos = 180 TÃ³picos

### Trilha 1: CLI e ConfiguraÃ§Ã£o (Emerald) â€” Semanas 1-2

| MÃ³dulo | TÃ­tulo | TÃ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 1.1 | InstalaÃ§Ã£o e Primeiro Comando | InstalaÃ§Ã£o (npm/brew), primeiro `claude`, modos interativo/one-shot, navegando o help, flags essenciais, diagnÃ³stico de problemas | PrÃ¡tico |
| 1.2 | Navegando o CLI como um Pro | Atalhos de teclado, slash commands, modelo e contexto, sessÃµes e /resume, leitura de imagens, output formatado | PrÃ¡tico |
| 1.3 | CLAUDE.md â€” O CÃ©rebro do Projeto | O que Ã©, hierarquia (global/projeto/pasta), sintaxe e convenÃ§Ãµes, instruÃ§Ãµes eficazes, exemplos reais, manutenÃ§Ã£o | Fundamento |
| 1.4 | ConfiguraÃ§Ã£o AvanÃ§ada | settings.json, .claudeignore, permissÃµes e allowedTools, variÃ¡veis de ambiente, perfis de projeto, model override | PrÃ¡tico |
| 1.5 | Memory e Contexto Persistente | Como a memÃ³ria funciona, /memory, context window, compaction, session handoff, checkpoint strategies | Fundamento |
| 1.6 | Seu Workflow Pessoal | Aliases de shell, scripts wrapper, integraÃ§Ã£o com editor (VS Code), tmux/screen, dotfiles, daily driver setup | PrÃ¡tico |

### Trilha 2: Plan e Loop Modes (Blue) â€” Semanas 3-4

| MÃ³dulo | TÃ­tulo | TÃ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 2.1 | Plan Mode â€” Pense Antes de Codar | O que Ã© plan mode, quando usar, anatomia de um plano, approval flow, iterando no plano, anti-patterns | Fundamento |
| 2.2 | Planos que Funcionam | Plano de feature, plano de refactor, plano de bug fix, decomposiÃ§Ã£o, dependÃªncias, estimativa de esforÃ§o | PrÃ¡tico |
| 2.3 | Loop Mode â€” AutomaÃ§Ã£o Iterativa | O que Ã©, quando usar, loop vs interativo, guardas de seguranÃ§a, monitoramento, parar no ponto certo | Fundamento |
| 2.4 | Patterns de Loop na PrÃ¡tica | Loop de testes, loop de lint/format, loop de migraÃ§Ã£o, loop de dados, loop de docs, loop composto | PrÃ¡tico |
| 2.5 | Combinando Plan + Loop | Plan para definir, loop para executar, pipeline planâ†’loopâ†’review, handoff entre modos, escalando complexidade, case studies | AvanÃ§ado |
| 2.6 | Agentic Coding â€” O Novo Normal | Filosofia agentic, delegaÃ§Ã£o eficaz, revisÃ£o vs micro-management, trust calibration, velocity metrics, mindset shift | Conceitual |

### Trilha 3: MCP Servers (Purple) â€” Semanas 5-6

| MÃ³dulo | TÃ­tulo | TÃ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 3.1 | O que sÃ£o MCP Servers | Protocolo MCP, client-server, tool discovery, por que importa, ecosystem overview, analogia com APIs | Fundamento |
| 3.2 | Seus Primeiros MCPs | Filesystem, Git, SQLite, configuraÃ§Ã£o no settings.json, testando ferramentas, troubleshooting | PrÃ¡tico |
| 3.3 | MCPs de Produtividade | Slack, Google Calendar, Gmail, Notion, Linear, combinando mÃºltiplos MCPs | PrÃ¡tico |
| 3.4 | MCPs de Database e APIs | PostgreSQL, Redis, HTTP/REST, GraphQL, conectando a serviÃ§os reais, seguranÃ§a de credenciais | PrÃ¡tico |
| 3.5 | Criando seu PrÃ³prio MCP Server | Anatomia de um server, SDK (TypeScript/Python), definindo tools, input schemas, testing, packaging | AvanÃ§ado |
| 3.6 | Ecossistema e Marketplace | Awesome MCP, Smithery, community servers, avaliando qualidade, composiÃ§Ã£o de servers, futuro do MCP | Conceitual |

### Trilha 4: Subagentes e Git (Amber) â€” Semanas 7-10

| MÃ³dulo | TÃ­tulo | TÃ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 4.1 | Subagentes â€” Conceitos | O que sÃ£o, Task tool, tipos de agente, comunicaÃ§Ã£o pai-filho, isolamento, quando usar vs nÃ£o usar | Fundamento |
| 4.2 | Paralelismo Real | LanÃ§ando mÃºltiplos agents, independÃªncia vs dependÃªncia, worktrees, background tasks, coletando resultados | PrÃ¡tico |
| 4.3 | Patterns de Multi-Agent | Fan-out/fan-in, pipeline, exploreâ†’planâ†’execute, specialist agents, error handling, cost control | AvanÃ§ado |
| 4.4 | Git com IA â€” Versionamento | Commits semÃ¢nticos, staging inteligente, diff review, merge conflicts, branching strategy, .gitignore | PrÃ¡tico |
| 4.5 | Pull Requests e Code Review | Criar PRs com gh, review automatizado, CI checks, addressing feedback, squash/rebase, best practices | PrÃ¡tico |
| 4.6 | CI/CD e GitHub Actions | Actions basics, workflow com Claude, testes automatizados, deploy contÃ­nuo, security scanning, monitoring | AvanÃ§ado |

### Trilha 5: Python e Ship (Teal) â€” Semanas 11-12

| MÃ³dulo | TÃ­tulo | TÃ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 5.1 | Python + Claude Code | Setup Python, venvs, pip/uv, scripts de automaÃ§Ã£o, debugging, type hints com IA | PrÃ¡tico |
| 5.2 | AutomaÃ§Ã£o de Scripts | Web scraping, file processing, data transforms, scheduling, APIs de terceiros, error handling robusto | PrÃ¡tico |
| 5.3 | FastAPI e Web Services | API REST com FastAPI, modelos Pydantic, endpoints, middleware, docs automÃ¡ticas, deploy | PrÃ¡tico |
| 5.4 | Testing Automatizado | pytest basics, fixtures, mocks, coverage, TDD com Claude, CI integration | PrÃ¡tico |
| 5.5 | Deploy e Infraestrutura | Docker basics, Docker Compose, cloud deploy (Railway/Fly.io), env management, monitoring | AvanÃ§ado |
| 5.6 | Ship Your Product | MVP mindset, priorizaÃ§Ã£o, launch checklist, feedback loop, iteraÃ§Ã£o, o que vem depois | Conceitual |

---

## Regras de ProduÃ§Ã£o

- Cada mÃ³dulo: 500-800 linhas HTML, â‰¥6 tÃ³picos, â‰¥1 SVG futurista, variados componentes
- MÃ³dulos prÃ¡ticos: â‰¥1 exemplo copy-run real
- MÃ³dulos fundamento: definir cada termo inline
- Manifesto completo em todas as pÃ¡ginas
- Anti-FOUC + learn.css + learn.js + ARCKHÉ.init()
- Cores: T1=Emerald, T2=Blue, T3=Purple, T4=Amber, T5=Teal
