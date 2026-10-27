# Bruno Soares

**Engenheiro de Software | IA aplicada | Arquitetura de produtos e runtimes confiáveis**

Bragança Paulista, SP · Brasil  
+55 (35) 91017-9164 · [bruno.soarxz@gmail.com](mailto:bruno.soarxz@gmail.com) · [github.com/brunosrz](https://github.com/brunosrz)

## Perfil

Sou um engenheiro de software ambicioso, autodidata e orientado a produto. Construo sistemas completos — da experiência do usuário ao runtime, persistência, segurança, testes e operação — com foco especial em IA aplicada de forma útil, controlável e verificável.

Meu principal projeto é o **Vectora**, uma plataforma de engenharia de software com agentes e workbenches. Ele nasceu como um produto local-first e evoluiu para uma arquitetura que combina execução de agentes, ferramentas, memória, contexto, browser, Git, persistência auditável e serviços distribuídos. O projeto é desenvolvido continuamente; por isso, apresento cada capacidade com seu estado real de maturidade, sem confundir protótipo, beta e produção.

Busco atuar em times que estejam criando produtos de IA, plataformas internas, automações B2B ou soluções que precisem unir software tradicional, modelos de linguagem e engenharia de confiabilidade.

## O que entrego

- Arquitetura e implementação de agentes com ferramentas, function calling, aprovação humana, subagentes, memória e recuperação de contexto.
- Backend Python com FastAPI, Pydantic, APIs REST, SSE, WebSocket, autenticação, RBAC e contratos versionados.
- Frontend TypeScript com React, Vite, TanStack, Zustand, Tailwind, Monaco, xterm e Electron.
- Persistência local e distribuída com SQLite/WAL, PostgreSQL, D1, Redis, LanceDB e Qdrant.
- Integração de LLMs remotos e locais, com roteamento de providers, fallbacks, diagnósticos e limites explícitos.
- Segurança de ferramentas: SSRF, políticas de egress, isolamento por workspace, redaction, credenciais e auditoria.
- Qualidade operacional: testes unitários, negativos, regressivos, integração e E2E; lint, tipagem, contratos, CI/CD e evidências reproduzíveis.
- Produtos B2B: descoberta de requisitos, arquitetura de catálogo, regras de negócio, UX e evolução incremental.

## Projetos selecionados

### Vectora — fundador e principal engenheiro

**Estado:** produto proprietário em desenvolvimento contínuo; núcleo funcional demonstrável, com capacidades individuais em diferentes níveis de maturidade.

O Vectora é um workspace de IA para desenvolvimento de software no qual pessoa e agente trabalham sobre o mesmo projeto, filesystem, terminal, Git, navegador, memória e contexto.

**Contribuições principais**

- Motor nativo de agentes com loop de execução, ferramentas, aprovação humana, subagentes e retomada.
- Contexto híbrido com busca textual, vetores, reranking e grafo baseado em estrutura de código.
- Workbenches para editor, terminal, Git, tarefas, memória, busca web e Browser Workbench sobre Chromium distribuído pelo Electron.
- Contratos canônicos entre backend Python e frontend TypeScript.
- AgentRun persistente, ledger derivado de eventos, checkpoints, snapshots, quality gates, replay e evidências estruturadas.
- Isolamento por workspace, proteção SSRF/egress e tratamento de conteúdo não confiável.
- Modo local-first com SQLite e LanceDB, além de caminhos de escala com PostgreSQL, Qdrant e Redis.
- Pacote `services` executado na Cloudflare: Workers/Hono, Durable Objects, R2, KV, D1, Queues e Cron Triggers para gateway, releases, autenticação, licenças, registry, telemetria e jobs assíncronos.

**Tecnologias:** Python, FastAPI, Pydantic, TypeScript, React, Vite, Electron, Chromium/CDP, SQLite, PostgreSQL, Redis, LanceDB, Qdrant, BM25, tree-sitter, MCP, Hono, Cloudflare Workers, Durable Objects, R2, KV, D1, Queues, Docker, GitHub Actions, Nuitka e electron-builder.

### Ability System — autor

**Estado:** projeto open source em preparação para distribuição pública na Godot Asset Library; branch de compatibilidade e CI em evolução.

Framework em C++/GDExtension para Godot 4.x, orientado a dados, com hierarquia de tags, fases de habilidade, composição por Resources e suporte a cenários multiplayer com predição e rollback.

O projeto demonstra experiência com APIs nativas de engine, compatibilidade de versões, empacotamento de plugins, builds multiplataforma e qualidade de software em C++.

**Tecnologias:** C++, Godot 4.x, GDExtension, SCons, GitHub Actions e networking determinístico.

### Plataforma de delivery — produto B2B em desenvolvimento

**Estado:** produto em desenvolvimento e mantido em repositório próprio; este repositório contém somente a narrativa, o plano e as evidências públicas autorizadas.

Produto de cardápio e pedidos para restaurantes, lanchonetes e operações de delivery. O fluxo cobre categorias, busca, itens, variações, complementos, observações, precificação, sacola e preparação para checkout e gestão de pedidos.

O case começou com protótipos próprios no Figma e será convertido em uma aplicação demonstrável, priorizando uso mobile, clareza comercial e uma arquitetura reutilizável para clientes B2B.

**Demonstra:** design de produto, UX mobile, catálogo, regras de preço, carrinho, checkout, acessibilidade, responsividade e integração entre operação comercial e software.

## Conhecimentos anteriores relevantes

- LangChain e LangGraph: experiência prática e conhecimento de trade-offs para orquestração, memória e ferramentas.
- Engenharia full stack, modelagem de dados, integração de APIs e automação de processos.
- Design e prototipação de interfaces no Figma, com tradução para produtos web e desktop.

## Como posso contribuir

- Construir uma plataforma interna de IA alinhada aos dados, processos e permissões da empresa.
- Desenvolver copilotos e agentes para engenharia, atendimento, suporte, análise documental e operações B2B.
- Projetar o caminho completo de um produto de IA: descoberta, protótipo, runtime, segurança, avaliação, observabilidade e deploy.
- Integrar modelos existentes sem aprisionamento a um provider, incluindo execução local quando privacidade ou custo exigirem.
- Atuar em um time de produto como ponte entre engenharia tradicional, UX e IA aplicada.

## Evidências e transparência

O portfólio não apresenta uma capacidade como pronta apenas porque existe código. Cada case deve apontar para repositório, demo, captura, teste ou documento correspondente e informar suas limitações. O estado atualizado e o plano de evolução estão em [`PLANO-PORTFOLIO.md`](PLANO-PORTFOLIO.md).
