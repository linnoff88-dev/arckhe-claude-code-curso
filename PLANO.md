# TransiêÂ§êÂ£o para o Claude Code ê¢â¬â Plano do Curso

**courseId:** `claude-code`
**Emoji:** ê°Å¸Â¤â
**Formato:** ARCKHê v2 (dark premium + camada de aprendizagem)
**Base:** infogrêÂ¡fico "Track Your Transition Into Claude Code" (12 semanas, 234 tasks)

---

## Estrutura: 5 Trilhas êâ 6 MêÂ³dulos = 30 MêÂ³dulos = 180 TêÂ³picos

### Trilha 1: CLI e ConfiguraêÂ§êÂ£o (Emerald) ê¢â¬â Semanas 1-2

| MêÂ³dulo | TêÂ­tulo | TêÂ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 1.1 | InstalaêÂ§êÂ£o e Primeiro Comando | InstalaêÂ§êÂ£o (npm/brew), primeiro `claude`, modos interativo/one-shot, navegando o help, flags essenciais, diagnêÂ³stico de problemas | PrêÂ¡tico |
| 1.2 | Navegando o CLI como um Pro | Atalhos de teclado, slash commands, modelo e contexto, sessêÂµes e /resume, leitura de imagens, output formatado | PrêÂ¡tico |
| 1.3 | CLAUDE.md ê¢â¬â O CêÂ©rebro do Projeto | O que êÂ©, hierarquia (global/projeto/pasta), sintaxe e convenêÂ§êÂµes, instruêÂ§êÂµes eficazes, exemplos reais, manutenêÂ§êÂ£o | Fundamento |
| 1.4 | ConfiguraêÂ§êÂ£o AvanêÂ§ada | settings.json, .claudeignore, permissêÂµes e allowedTools, variêÂ¡veis de ambiente, perfis de projeto, model override | PrêÂ¡tico |
| 1.5 | Memory e Contexto Persistente | Como a memêÂ³ria funciona, /memory, context window, compaction, session handoff, checkpoint strategies | Fundamento |
| 1.6 | Seu Workflow Pessoal | Aliases de shell, scripts wrapper, integraêÂ§êÂ£o com editor (VS Code), tmux/screen, dotfiles, daily driver setup | PrêÂ¡tico |

### Trilha 2: Plan e Loop Modes (Blue) ê¢â¬â Semanas 3-4

| MêÂ³dulo | TêÂ­tulo | TêÂ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 2.1 | Plan Mode ê¢â¬â Pense Antes de Codar | O que êÂ© plan mode, quando usar, anatomia de um plano, approval flow, iterando no plano, anti-patterns | Fundamento |
| 2.2 | Planos que Funcionam | Plano de feature, plano de refactor, plano de bug fix, decomposiêÂ§êÂ£o, dependêÂªncias, estimativa de esforêÂ§o | PrêÂ¡tico |
| 2.3 | Loop Mode ê¢â¬â AutomaêÂ§êÂ£o Iterativa | O que êÂ©, quando usar, loop vs interativo, guardas de seguranêÂ§a, monitoramento, parar no ponto certo | Fundamento |
| 2.4 | Patterns de Loop na PrêÂ¡tica | Loop de testes, loop de lint/format, loop de migraêÂ§êÂ£o, loop de dados, loop de docs, loop composto | PrêÂ¡tico |
| 2.5 | Combinando Plan + Loop | Plan para definir, loop para executar, pipeline planê¢â âloopê¢â âreview, handoff entre modos, escalando complexidade, case studies | AvanêÂ§ado |
| 2.6 | Agentic Coding ê¢â¬â O Novo Normal | Filosofia agentic, delegaêÂ§êÂ£o eficaz, revisêÂ£o vs micro-management, trust calibration, velocity metrics, mindset shift | Conceitual |

### Trilha 3: MCP Servers (Purple) ê¢â¬â Semanas 5-6

| MêÂ³dulo | TêÂ­tulo | TêÂ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 3.1 | O que sêÂ£o MCP Servers | Protocolo MCP, client-server, tool discovery, por que importa, ecosystem overview, analogia com APIs | Fundamento |
| 3.2 | Seus Primeiros MCPs | Filesystem, Git, SQLite, configuraêÂ§êÂ£o no settings.json, testando ferramentas, troubleshooting | PrêÂ¡tico |
| 3.3 | MCPs de Produtividade | Slack, Google Calendar, Gmail, Notion, Linear, combinando mêÂºltiplos MCPs | PrêÂ¡tico |
| 3.4 | MCPs de Database e APIs | PostgreSQL, Redis, HTTP/REST, GraphQL, conectando a serviêÂ§os reais, seguranêÂ§a de credenciais | PrêÂ¡tico |
| 3.5 | Criando seu PrêÂ³prio MCP Server | Anatomia de um server, SDK (TypeScript/Python), definindo tools, input schemas, testing, packaging | AvanêÂ§ado |
| 3.6 | Ecossistema e Marketplace | Awesome MCP, Smithery, community servers, avaliando qualidade, composiêÂ§êÂ£o de servers, futuro do MCP | Conceitual |

### Trilha 4: Subagentes e Git (Amber) ê¢â¬â Semanas 7-10

| MêÂ³dulo | TêÂ­tulo | TêÂ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 4.1 | Subagentes ê¢â¬â Conceitos | O que sêÂ£o, Task tool, tipos de agente, comunicaêÂ§êÂ£o pai-filho, isolamento, quando usar vs nêÂ£o usar | Fundamento |
| 4.2 | Paralelismo Real | LanêÂ§ando mêÂºltiplos agents, independêÂªncia vs dependêÂªncia, worktrees, background tasks, coletando resultados | PrêÂ¡tico |
| 4.3 | Patterns de Multi-Agent | Fan-out/fan-in, pipeline, exploreê¢â âplanê¢â âexecute, specialist agents, error handling, cost control | AvanêÂ§ado |
| 4.4 | Git com IA ê¢â¬â Versionamento | Commits semêÂ¢nticos, staging inteligente, diff review, merge conflicts, branching strategy, .gitignore | PrêÂ¡tico |
| 4.5 | Pull Requests e Code Review | Criar PRs com gh, review automatizado, CI checks, addressing feedback, squash/rebase, best practices | PrêÂ¡tico |
| 4.6 | CI/CD e GitHub Actions | Actions basics, workflow com Claude, testes automatizados, deploy contêÂ­nuo, security scanning, monitoring | AvanêÂ§ado |

### Trilha 5: Python e Ship (Teal) ê¢â¬â Semanas 11-12

| MêÂ³dulo | TêÂ­tulo | TêÂ³picos (6) | Tipo |
|--------|--------|-------------|------|
| 5.1 | Python + Claude Code | Setup Python, venvs, pip/uv, scripts de automaêÂ§êÂ£o, debugging, type hints com IA | PrêÂ¡tico |
| 5.2 | AutomaêÂ§êÂ£o de Scripts | Web scraping, file processing, data transforms, scheduling, APIs de terceiros, error handling robusto | PrêÂ¡tico |
| 5.3 | FastAPI e Web Services | API REST com FastAPI, modelos Pydantic, endpoints, middleware, docs automêÂ¡ticas, deploy | PrêÂ¡tico |
| 5.4 | Testing Automatizado | pytest basics, fixtures, mocks, coverage, TDD com Claude, CI integration | PrêÂ¡tico |
| 5.5 | Deploy e Infraestrutura | Docker basics, Docker Compose, cloud deploy (Railway/Fly.io), env management, monitoring | AvanêÂ§ado |
| 5.6 | Ship Your Product | MVP mindset, priorizaêÂ§êÂ£o, launch checklist, feedback loop, iteraêÂ§êÂ£o, o que vem depois | Conceitual |

---

## Regras de ProduêÂ§êÂ£o

- Cada mêÂ³dulo: 500-800 linhas HTML, ê¢â°Â¥6 têÂ³picos, ê¢â°Â¥1 SVG futurista, variados componentes
- MêÂ³dulos prêÂ¡ticos: ê¢â°Â¥1 exemplo copy-run real
- MêÂ³dulos fundamento: definir cada termo inline
- Manifesto completo em todas as pêÂ¡ginas
- Anti-FOUC + learn.css + learn.js + ARCKHê.init()
- Cores: T1=Emerald, T2=Blue, T3=Purple, T4=Amber, T5=Teal
