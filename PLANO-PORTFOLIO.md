# Plano de implementação do portfólio

## Objetivo

Transformar este repositório em uma vitrine profissional funcional, verificável e atualizável, capaz de vender o trabalho de Bruno Soares para:

- times que constroem produtos de IA;
- empresas que precisam de uma plataforma interna de IA;
- empresas B2B que precisam entregar automações e software para seus clientes.

O portfólio deve provar capacidade técnica e de produto sem esconder o que ainda está em desenvolvimento.

## Escopo

### Incluído neste repositório

- currículo em português e, depois, uma versão em inglês;
- site público do portfólio e seus dados editoriais;
- páginas dos cases Vectora, Ability System e delivery;
- matriz de estado das capacidades e registro de evidências;
- decisões de conteúdo, privacidade, copyright e publicação;
- testes e validações do próprio portfólio.

### Fora deste repositório

- código da plataforma de delivery, que terá repositório próprio;
- código do Vectora, que continua em `vectora-ltda/vectora`;
- código do Ability System, que continua em `brunosrz/AbilitySystem`;
- qualquer material de cliente não autorizado para publicação;
- uso de marca, imagens ou métricas de terceiros sem permissão.

## Estado atual

| Área | Estado | Evidência atual | Lacuna |
| --- | --- | --- | --- |
| Currículo textual | iniciado | `CURRICULO.md`, `CURRICULO-DEV.md` | revisão editorial, versão em inglês e alinhamento entre os dois públicos |
| Repositório do portfólio | iniciado | este repositório | site navegável e deploy |
| Vectora | em desenvolvimento contínuo | repositório e histórico técnico | demo pública curada, screenshots e estados por recurso |
| Ability System | em preparação para publicação | repositório open source e CI | release público, documentação de instalação e demo estável |
| Delivery | em desenvolvimento, repositório separado | protótipos Figma | MVP demonstrável e evidências de regras de negócio |
| Terceiro case | definido como Ability System | repositório próprio | página editorial e vídeos/capturas |
| Hotel | não é case principal | protótipo visual sem contrato | não publicar como trabalho de cliente; pode permanecer como material privado |

## Fases

### Fase 0 — Inventário e autorização

1. Catalogar links, screenshots, demos, commits, testes e vídeos de cada projeto.
2. Classificar cada afirmação como `publicado`, `demonstrável`, `beta`, `em desenvolvimento`, `protótipo` ou `não publicar`.
3. Remover dados pessoais, chaves, endpoints privados, screenshots com credenciais e material de terceiros sem autorização.
4. Registrar copyright e permissão de uso para imagens, marcas e assets.

**Aceite:** toda afirmação do currículo aponta para uma evidência ou está marcada como limitação; nenhum case de cliente é apresentado como contrato fechado sem prova.

### Fase 1 — Fundação editorial e visual

1. Definir identidade visual, tipografia, cores, grid, navegação e tom de voz.
2. Criar modelo de dados para cases: problema, contribuição, stack, estado, evidências, limitações e links.
3. Criar componentes de `StatusBadge`, `EvidenceCard`, `CaseStudy`, `Timeline` e `ContactCTA`.
4. Garantir versão mobile, contraste, navegação por teclado, textos alternativos e links semânticos.

**Aceite:** a home apresenta quem sou, o que construo, três cases e uma chamada de contato em menos de três interações; o estado de cada case é visível sem linguagem ambígua.

### Fase 2 — Case Vectora

1. Publicar uma narrativa curta do problema, arquitetura e responsabilidades individuais.
2. Separar capacidades por estado: núcleo funcional, beta, experimental e planejado.
3. Exibir diagramas de runtime, services/Cloudflare, persistência, segurança e avaliação.
4. Linkar commits, issues, PRs, testes e screenshots que sustentem cada afirmação.
5. Criar uma demo ou vídeo sem credenciais, com dados sintéticos e aviso de limitações.

**Aceite:** um recrutador consegue entender em cinco minutos o problema, a contribuição pessoal, a arquitetura e o que ainda não está pronto.

### Fase 3 — Case Ability System

1. Aguardar a publicação estável na Godot Asset Library antes de marcar o projeto como lançado.
2. Criar página com motivação, API, exemplo mínimo, multiplayer, compatibilidade Godot e processo de release.
3. Linkar documentação, pacote, changelog, CI e testes.
4. Publicar uma demo curta mostrando uma habilidade do início ao fim.

**Aceite:** uma pessoa consegue instalar o plugin seguindo apenas a página do case e reproduzir o exemplo em uma versão suportada da Godot.

### Fase 4 — Case delivery no repositório próprio

1. Criar o repositório do produto e manter aqui somente links e material autorizado.
2. Converter os protótipos Figma em MVP mobile navegável.
3. Implementar catálogo, busca, item, complementos, observação, sacola e cálculo de preço.
4. Adicionar testes unitários, negativos e regressivos para preço, estoque, quantidade, descontos e carrinho.
5. Criar dados de demonstração e uma jornada sem checkout real.

**Aceite:** o visitante consegue concluir uma jornada de pedido com dados sintéticos, e cada regra financeira relevante possui teste visível no repositório do produto.

### Fase 5 — Site público e distribuição

1. Implementar o site estático ou híbrido neste repositório.
2. Adicionar SEO, Open Graph, sitemap, política de privacidade e página de contato.
3. Configurar CI com formatação, lint, tipagem, testes, verificação de links, acessibilidade e build.
4. Publicar preview por pull request e deploy de produção com domínio próprio quando disponível.
5. Adicionar analytics apenas com consentimento e sem coletar dados desnecessários.

**Aceite:** cada pull request gera preview; o deploy só ocorre com todos os gates passando; links quebrados e regressões visuais bloqueiam a publicação.

### Fase 6 — Manutenção e prova contínua

1. Revisar mensalmente links, versões, screenshots, dependências e estado dos projetos.
2. Atualizar o currículo somente a partir de mudanças comprovadas nos repositórios dos cases.
3. Registrar toda mudança editorial importante em `DECISOES.md`.
4. Medir conversão por contato qualificado, não por vaidade de visitas.

**Aceite:** o portfólio nunca afirma que uma capacidade está pronta quando a evidência está desatualizada ou classificada como beta.

## Matriz mínima de testes

- **Conteúdo:** links válidos, ausência de segredos, encoding UTF-8, consistência entre currículo e páginas.
- **Visual:** snapshots ou inspeção automatizada de home, cases, mobile e desktop.
- **Acessibilidade:** headings, foco, contraste, alt text, teclado e `prefers-reduced-motion`.
- **Segurança:** formulários sem exposição de credenciais, sanitização e política de privacidade.
- **Regressão:** toda mudança de navegação, case ou estado deve preservar as rotas e os badges existentes.
- **Deploy:** build limpo em CI, preview reproduzível e verificação pós-publicação.

## Critério de conclusão do portfólio

O portfólio só será considerado pronto quando houver site publicado, currículo em português e inglês, três cases com estado explícito, evidências navegáveis, testes automatizados, acessibilidade básica, política de privacidade e um processo de atualização que impeça afirmações sem prova.
