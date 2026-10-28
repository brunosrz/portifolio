# Bruno Soares

**Engenheiro de Software autodidata · IA aplicada · Produtos full stack**

São João Batista do Glória, MG · Brasil  
+55 (35) 91017-9164 · [bruno.soarxz@gmail.com](mailto:bruno.soarxz@gmail.com) · [github.com/brunosrz](https://github.com/brunosrz)

## Resumo profissional

Desenvolvedor autodidata e orientado a produto, com experiência prática construindo sistemas completos: interface, backend, agentes de IA, persistência, segurança, testes e operação. Meu principal trabalho é o Vectora, uma plataforma de engenharia de software com agentes e workbenches que desenvolvo continuamente como produto próprio.

Tenho facilidade para aprender tecnologias novas e conectar áreas que normalmente ficam separadas: UX, engenharia de software, modelos de linguagem, automação e confiabilidade. Busco atuar como Software Engineer, AI Engineer, Full Stack Engineer, Backend Engineer ou Developer Tools Engineer em produtos de IA, plataformas internas e automações B2B.

## Experiência profissional

### Vectora — Fundador e Engenheiro de Software
**2026 – atual · Projeto próprio em desenvolvimento contínuo**

- Concepção e desenvolvimento de uma plataforma local-first para desenvolvimento de software assistido por agentes.
- Implementação do runtime nativo de agentes, loop de conversação, function calling, aprovação humana, subagentes, retomada e execução de ferramentas.
- Construção de workbenches para editor, terminal, Git, tarefas, memória, busca web e navegador Chromium integrado ao Electron.
- Definição de contratos entre backend Python e frontend TypeScript, além de persistência auditável com AgentRun, ledger, checkpoints, snapshots, replay e quality gates.
- Implementação de políticas de egress, proteção SSRF, isolamento por workspace, redaction de credenciais e tratamento de conteúdo não confiável.
- Organização de CI/CD, testes unitários, negativos, regressivos, integração e E2E, com validações de lint, tipagem, segurança e drift de contratos.
- Desenvolvimento do pacote `services` com Hono e Cloudflare Workers para gateway, autenticação, releases, licenças, registry, telemetria e jobs assíncronos.

**Estado:** núcleo funcional demonstrável, com capacidades em diferentes níveis de maturidade claramente documentados. O projeto continua em evolução e não apresenta protótipos como produção.

## Competências principais

### IA aplicada e agentes

- Arquitetura de agentes com ferramentas, function calling, aprovação humana e subagentes.
- Memória, recuperação de contexto, RAG, reranking e grafo estrutural de código.
- Integração de modelos remotos e locais, roteamento de providers, fallbacks e diagnósticos.
- Avaliação, replay, evidências estruturadas e quality gates.
- Experiência com LangChain e LangGraph, incluindo trade-offs de orquestração, memória e ferramentas.

### Backend e sistemas distribuídos

- Python, FastAPI, Pydantic, APIs REST, SSE, WebSocket, autenticação, RBAC e contratos versionados.
- TypeScript com Hono e Cloudflare Workers, Durable Objects, D1, R2, KV, Queues e Cron Triggers.
- SQLite/WAL, PostgreSQL, Redis, LanceDB e Qdrant.
- MCP, Docker, GitHub Actions, observabilidade e automação de processos.
- Rust em formação aplicada, com estudo de migração progressiva de componentes do Vectora e avaliação do backend do Delivery como caso real isolado.

### Frontend, desktop e experiência de produto

- TypeScript, React, Vite, TanStack, Zustand e Tailwind.
- Electron, Chromium/CDP, Monaco e xterm.
- Design de produto e prototipação no Figma, com tradução de interfaces para produtos web e desktop.
- Modelagem de fluxos, regras de negócio e experiências B2B.

### Qualidade, segurança e operação

- Testes unitários, negativos, regressivos, integração e E2E.
- Ruff, tipagem Python, TypeScript, Prettier, Bandit, pre-commit e CI/CD.
- SSRF, políticas de egress, isolamento de workspace, redaction e auditoria.
- Contratos canônicos, migrações, recuperação após falhas e evidências reproduzíveis.

## Projetos selecionados

### Vectora — plataforma de engenharia de software com IA

[Repositório](https://github.com/vectora-ltda/vectora)

O Vectora permite que pessoa e agente trabalhem sobre o mesmo projeto, filesystem, terminal, Git, navegador, memória e contexto. O objetivo é reduzir o trabalho operacional de desenvolvimento sem abrir mão de permissões, rastreabilidade e controle humano.

**Principais entregas:** runtime de agentes, workbenches, contexto híbrido, contratos Python/TypeScript, AgentRun persistente, ledger derivado de eventos, checkpoints, snapshots, replay, quality gates e serviços Cloudflare.

**Tecnologias:** Python, FastAPI, Pydantic, TypeScript, React, Vite, Electron, Chromium/CDP, SQLite, PostgreSQL, Redis, LanceDB, Qdrant, BM25, tree-sitter, MCP, Hono, Cloudflare Workers, Docker, GitHub Actions, Nuitka e electron-builder.

**Estado:** desenvolvimento ativo; cada capacidade é apresentada com seu nível real de maturidade e evidências correspondentes.

### Ability System — framework de habilidades para Godot

[Repositório](https://github.com/brunosrz/AbilitySystem)

Framework open source em C++/GDExtension para Godot 4.x, orientado a dados, com hierarquia de tags, fases de habilidade, composição por Resources e suporte a cenários multiplayer com predição e rollback.

**Demonstra:** desenvolvimento de APIs nativas, integração com engine, compatibilidade de versões, empacotamento de plugins, builds multiplataforma e qualidade de software em C++.

**Estado:** preparação para distribuição pública na Godot Asset Library, com CI e compatibilidade em evolução.

### Delivery — produto B2B para restaurantes

[Repositório](https://github.com/brunosrz/Delivery)

Produto de cardápio e pedidos para restaurantes, lanchonetes e operações de delivery. O fluxo inclui categorias, busca, itens, variações, complementos, observações, precificação, sacola, checkout e gestão de pedidos.

O projeto começou com protótipos próprios no Figma e está sendo convertido em uma aplicação demonstrável, com foco mobile, clareza comercial e arquitetura reutilizável para clientes B2B.

**Demonstra:** design de produto, UX mobile, catálogo, regras de preço, carrinho, checkout, acessibilidade, responsividade e integração entre operação comercial e software.

**Estado:** desenvolvimento ativo; o backend Rust é avaliado como caso isolado e mensurável de uso da linguagem.

## Como posso contribuir

- Construir plataformas internas de IA alinhadas aos dados, processos e permissões da empresa.
- Desenvolver copilotos e agentes para engenharia, atendimento, suporte, análise documental e operações B2B.
- Projetar o ciclo completo de um produto: descoberta, protótipo, runtime, segurança, avaliação, observabilidade e deploy.
- Integrar modelos existentes sem aprisionamento a um provider, incluindo execução local quando privacidade ou custo exigirem.
- Automatizar processos administrativos e operacionais com software, dados, relatórios e integrações.
- Atuar como ponte entre engenharia tradicional, UX, produto e IA aplicada.

## Formação e conhecimentos adicionais

- Ensino Médio completo.
- Programação e Web Design autodidatas, com prática contínua desde a adolescência.
- Figma, design de interfaces, modelagem de dados, integração de APIs e automação.
- Conhecimento prático de LangChain e LangGraph.

## Evidências e transparência

O portfólio distingue código publicado, demonstração funcional, beta, protótipo e desenvolvimento ativo. Nenhuma capacidade é apresentada como produção apenas porque existe no código. Repositórios, estado de maturidade e próximos passos são mantidos no [plano do portfólio](PLANO-PORTFOLIO.md).
