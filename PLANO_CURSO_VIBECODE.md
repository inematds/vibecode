# PLANO COMPLETO — Curso Vibe Coding
> **Versão:** 1.0 | **Data:** 2026-03-03 | **Status:** Aguardando Aprovação

---

## RESUMO EXECUTIVO

| Item | Detalhe |
|------|---------|
| **Nome do curso** | ⚡ Vibe Coding: Da Ideia ao Produto |
| **Trilhas** | 4 (Fundamentos, Leigos, Executivos, Técnicos) |
| **Total de módulos** | 31 módulos |
| **Total de tópicos** | ~217 tópicos (7 por módulo em média) |
| **Total de arquivos HTML** | 36 (1 landing + 4 índices de trilha + 31 módulos) |
| **Carga horária estimada** | ~16.5h de conteúdo total |
| **Público-alvo** | Todos — do leigo completo ao executivo ao dev sênior |
| **Referência de design** | MASTER_COMPLETO.md + CHECKLIST_REVISAO.md |

---

## FONTES E REFERÊNCIAS

### Conteúdo interno (doc/)
- `Curso_Completo_Vibe_Coding.md` — Estrutura base com 9 módulos (fundamentos ao agentic)
- `Complementos_Curso_Vibe_Coding.md` — 5 grupos de complementos (técnico, aplicações, qualidade, deploy, mercado)

### Pesquisa externa (2025-2026)
- Termo criado por **Andrej Karpathy** em 1 fev 2025 — Collins Word of the Year 2025
- **21%** dos projetos Y Combinator W25 têm 91%+ de código gerado por IA
- **63%** dos usuários de ferramentas vibe coding NÃO são desenvolvedores
- Cursor levantou $900M (valuation $9,9B) | Lovable foi de $1M → $100M ARR em 8 meses
- **19% mais lentos** (devs experientes — estudo METR) vs. **81% mais rápidos** em boilerplate
- **2,74x mais vulnerabilidades** em código gerado por IA (CodeRabbit, dez/2025)
- Karpathy em fev/2026: o futuro é **"Agentic Engineering"**, não mais vibe coding puro

---

## SISTEMA DE CORES POR TRILHA

| Trilha | Cor | Público |
|--------|-----|---------|
| T1 — Fundamentos | **Emerald** | Todos os perfis |
| T2 — Leigos | **Purple** | Não-técnicos, empreendedores, PMs |
| T3 — Executivos | **Amber** | C-level, gestores, líderes de negócio |
| T4 — Técnicos | **Blue** | Desenvolvedores e engenheiros |

---

## ESTRUTURA DE ARQUIVOS

```
vibecode/
├── index.html                          # Landing page do curso
├── curso/
│   ├── fundamentos/                    # T1 — Emerald
│   │   ├── index.html                  # Índice da trilha
│   │   ├── modulo-1-1.html
│   │   ├── modulo-1-2.html
│   │   ├── modulo-1-3.html
│   │   ├── modulo-1-4.html
│   │   ├── modulo-1-5.html
│   │   ├── modulo-1-6.html
│   │   ├── modulo-1-7.html
│   │   └── modulo-1-8.html
│   ├── leigos/                         # T2 — Purple
│   │   ├── index.html
│   │   ├── modulo-2-1.html
│   │   ├── modulo-2-2.html
│   │   ├── modulo-2-3.html
│   │   ├── modulo-2-4.html
│   │   ├── modulo-2-5.html
│   │   ├── modulo-2-6.html
│   │   └── modulo-2-7.html
│   ├── executivos/                     # T3 — Amber
│   │   ├── index.html
│   │   ├── modulo-3-1.html
│   │   ├── modulo-3-2.html
│   │   ├── modulo-3-3.html
│   │   ├── modulo-3-4.html
│   │   ├── modulo-3-5.html
│   │   ├── modulo-3-6.html
│   │   ├── modulo-3-7.html
│   │   └── modulo-3-8.html
│   └── tecnicos/                       # T4 — Blue
│       ├── index.html
│       ├── modulo-4-1.html
│       ├── modulo-4-2.html
│       ├── modulo-4-3.html
│       ├── modulo-4-4.html
│       ├── modulo-4-5.html
│       ├── modulo-4-6.html
│       ├── modulo-4-7.html
│       └── modulo-4-8.html
├── doc/
└── ref/
```

---

## TRILHA 1 — FUNDAMENTOS ⚡ (Emerald)

**Público:** Todos os perfis — ponto de entrada obrigatório antes das trilhas específicas
**Nível:** Básico
**Duração estimada:** ~4h
**Módulos:** 8 | **Tópicos:** ~56

---

### Módulo 1.1 — 🌱 O Que É Vibe Coding (~30 min)
*Introdução ao conceito, origem e contexto histórico*

1. **O termo e sua origem** — Andrej Karpathy, 1 fev 2025, o post que mudou tudo
2. **Definição prática** — "dar as vibes para a IA e aceitar o output"
3. **Por que surgiu agora** — A evolução dos LLMs tornou isso possível
4. **Vibe coding vs. programação tradicional** — diferenças fundamentais
5. **O espectro da IA no código** — autocomplete → assistente → agente → agentic engineering
6. **Quem está usando** — 63% não são devs, cases reais (CNBC reporter, fundador de startup)
7. **Collins Word of the Year 2025** — o reconhecimento cultural do fenômeno

---

### Módulo 1.2 — 🧠 Mentalidade do Vibe Coder (~30 min)
*Shift mental necessário para trabalhar com IA de forma eficaz*

1. **Pensar em resultados, não em código** — o que o sistema deve FAZER, não como fazer
2. **Iteração como método** — pequenos passos validados > grandes blocos aceitos cegamente
3. **Você é o arquiteto** — a IA é o estagiário brilhante que precisa de supervisão
4. **Abraçar a imprecisão inicial** — prototipar rápido, refinar depois
5. **O paradoxo da velocidade** — mais rápido em tarefas simples, mais lento se não supervisionar
6. **Quando confiar e quando questionar** — desenvolvendo senso crítico para output de IA
7. **Do vibe coding ao agentic engineering** — como o mindset evolui com experiência

---

### Módulo 1.3 — 🛠️ Ferramentas: O Ecossistema (~35 min)
*Panorama das principais ferramentas e como escolher a sua*

1. **O mapa das ferramentas** — IDEs, agentes, plataformas no-code
2. **Cursor** — o líder técnico ($9,9B valuation), pontos fortes e como usar
3. **Windsurf** — alternativa com mais agentes inclusos, ideal para times
4. **GitHub Copilot** — o mais adotado, 84% dos devs já usam ou planejam
5. **Claude Code** — poderoso no terminal, MCP, CLAUDE.md como superpoder
6. **Plataformas prompt-to-app** — Lovable, Bolt.new, v0, Replit Agent (visão geral)
7. **Como escolher** — tabela comparativa por perfil e caso de uso

---

### Módulo 1.4 — 🚀 Seu Primeiro Projeto com IA (~35 min)
*Hands-on: do zero ao primeiro resultado funcional*

1. **Setup em 10 minutos** — instalação e configuração mínima necessária
2. **Escolhendo o projeto certo para começar** — MVP simples e bem definido
3. **O primeiro prompt** — como descrever o que você quer de forma eficaz
4. **Iteração na prática** — aceitar, testar, ajustar, repetir
5. **Quando o erro aparece** — copiar e colar erro de volta: a técnica mais subestimada
6. **Salvando o progresso** — commits estratégicos para ter rollback seguro
7. **Resultado final** — critérios para saber quando o primeiro projeto está "pronto"

---

### Módulo 1.5 — 💬 Prompt Engineering Básico (~30 min)
*Como pedir código de forma que a IA entenda e entregue bem*

1. **Por que o prompt importa** — mesma IA, resultados completamente diferentes
2. **Contexto é rei** — a estrutura: contexto + tarefa + restrições + resultado esperado
3. **Especificar entrada e saída** — não "faça uma função", mas "função que recebe X e retorna Y"
4. **Fornecer exemplos no prompt** — o atalho mais eficaz para resultados precisos
5. **Dividir problemas grandes** — nunca pedir tudo de uma vez
6. **Pedir revisão e refatoração** — usando a IA para melhorar o que ela mesma gerou
7. **Os 5 erros mais comuns em prompts de código** — com exemplos do que fazer e não fazer

---

### Módulo 1.6 — 🔄 Ciclo de Desenvolvimento com IA (~30 min)
*O workflow validado: Explore → Plan → Implement → Verify*

1. **O workflow EPIV** — Explore, Plan, Implement, Verify
2. **Fase Explore** — peça para a IA entender o codebase sem modificar nada
3. **Fase Plan** — "me dê um plano antes de escrever qualquer código"
4. **Fase Implement** — execução em partes testáveis e incrementais
5. **Fase Verify** — validação antes de aceitar qualquer mudança
6. **Branches para cada feature** — nunca vibe code direto na main
7. **Documentação automática** — peça ao agente que documente o que fez e por quê

---

### Módulo 1.7 — 🔐 Controle, Qualidade e Segurança Básica (~30 min)
*O que todo vibe coder precisa saber para não se arrepender depois*

1. **O dado que assusta** — 2,74x mais vulnerabilidades em código de IA (CodeRabbit 2025)
2. **Git como rede de segurança** — commits frequentes = histórico de rollback
3. **Variáveis de ambiente** — nunca hardcodar tokens, chaves ou senhas
4. **Revisar o diff antes de commitar** — ler antes de aceitar, sempre
5. **Validação de dados** — o mínimo para não ter dados corrompidos
6. **O que NÃO fazer em produção** — checklist de bloqueadores críticos
7. **Quando chamar um profissional** — sinais de que você precisa de revisão técnica externa

---

### Módulo 1.8 — 🌐 Deploy: Publicando seu Projeto (~25 min)
*Do localhost para o mundo em menos de uma hora*

1. **O que é deploy** — da máquina local para servidor acessível na internet
2. **Vercel** — melhor para projetos Next.js/React, deploy em 1 clique
3. **Render** — ótimo para backends e APIs
4. **Railway** — banco de dados + backend com setup mínimo
5. **Configurando domínio** — DNS e SSL em linguagem acessível
6. **Variáveis de ambiente no deploy** — segredos fora do código
7. **Monitoramento básico** — saber quando algo quebrou em produção

---

## TRILHA 4 — TÉCNICOS 💻 (Blue)

**Público:** Desenvolvedores, engenheiros de software, tech leads
**Nível:** Intermediário/Avançado
**Duração estimada:** ~5h
**Módulos:** 8 | **Tópicos:** ~56
**Pré-requisito:** Trilha 1 — Fundamentos (ou experiência prévia em desenvolvimento)

---

### Módulo 4.1 — ⚙️ Stack Técnico Avançado (~35 min)
*Configuração profissional do ambiente para máxima produtividade*

1. **Escolhendo o IDE certo** — Cursor vs. Windsurf vs. Claude Code: quando usar cada um
2. **`.cursorrules` e `CLAUDE.md`** — a técnica mais eficaz: regras persistentes de projeto
3. **Model Context Protocol (MCP)** — conectando a IA ao seu banco de dados, APIs e filesystem
4. **Configuração de múltiplos modelos** — quando usar Claude Opus vs. Sonnet vs. Haiku
5. **Plugins e extensões essenciais** — o setup que profissionais usam em 2026
6. **Contexto de projeto bem estruturado** — `@arquivo`, `@pasta`, referenciamento preciso
7. **Profiling do ambiente** — medindo onde a IA realmente ajuda e onde atrapalha

---

### Módulo 4.2 — 🎯 Prompt Engineering Avançado (~40 min)
*Técnicas usadas por engenheiros que extraem o máximo dos LLMs*

1. **Chain-of-Thought para código** — "pense passo a passo" aplicado a problemas complexos
2. **Pseudocódigo primeiro** — estratégia para tarefas de alta complexidade
3. **Focar em comportamento, não implementação** — "o usuário deve conseguir fazer X"
4. **Prompting agentico** — objetivos de alto nível com Definition of Done claro
5. **Técnicas de decomposição** — dividir sistemas complexos em subtarefas gerenciáveis
6. **Refactoring por prompt** — como pedir melhorias sem perder funcionalidade
7. **Debug por prompt** — enviando contexto de erro correto para resolução mais rápida

---

### Módulo 4.3 — 🏗️ Arquitetura e Design Patterns com IA (~40 min)
*Como garantir que código gerado por IA respeite padrões arquiteturais*

1. **O problema do patchwork** — codebases inconsistentes gerados por IA sem visão unificada
2. **MVC e separação em camadas** — instruindo a IA sobre o padrão do projeto
3. **Domain-Driven Design assistido por IA** — modelagem de domínio com LLMs
4. **Banco de dados: modelagem e SQL** — pedindo schemas corretos desde o início
5. **Autenticação e autorização** — por que implementar primeiro (JWT, sessões, OAuth)
6. **Escalabilidade: decidindo antes de construir** — como as decisões arquiteturais afetam o futuro
7. **Documentação arquitetural automática** — usando a IA para documentar decisões de design

---

### Módulo 4.4 — 🔒 Segurança em Código Gerado por IA (~40 min)
*Os riscos reais e como mitigá-los profissionalmente*

1. **Os dados: 45% do código de IA tem falhas de segurança** — o que isso significa na prática
2. **OWASP Top 10 para código de IA** — SQL injection, XSS, CSRF e como a IA os cria
3. **Row Level Security (Supabase/PostgreSQL)** — o erro mais comum em apps Lovable e similares
4. **Gestão de secrets** — .env, variáveis de ambiente, nunca hardcodar
5. **SAST: análise estática automatizada** — ferramentas para escanear antes de fazer deploy
6. **Code review focado em segurança** — checklist para revisar output de IA antes de produção
7. **Casos reais de incidentes** — Lovable (18K usuários), Base44, CurXecute CVE-2025-54135

---

### Módulo 4.5 — 🧪 Testes Automatizados com IA (~35 min)
*Usando IA para criar a rede de segurança que permite vibe coding responsável*

1. **Por que testes são o guardrail do vibe coding** — testes permitem agentes operarem com segurança
2. **Testes unitários por prompt** — gerando casos de teste automaticamente
3. **Testes de integração** — testando fluxos completos com IA
4. **Testes E2E** — Playwright/Cypress gerado por IA
5. **TDD invertido** — escrever os testes primeiro, pedir a implementação depois
6. **Cobertura de código** — métricas e como atingi-las com IA
7. **Debugging sistemático** — isolando problemas para o agente resolver com precisão

---

### Módulo 4.6 — 🚢 CI/CD e Deploy Profissional (~35 min)
*Pipeline de entrega contínua para código gerado por IA*

1. **Por que CI/CD é ainda mais importante com vibe coding** — automação como qualidade garantida
2. **GitHub Actions básico** — pipeline de lint + testes + build automatizados
3. **SAST no pipeline** — análise de segurança automática em cada PR
4. **Deploy automático com Vercel/Railway** — integração contínua sem overhead manual
5. **Feature flags** — liberando funcionalidades de IA gradualmente
6. **Rollback automático** — configurando reversão quando métricas degradam
7. **Monitoramento pós-deploy** — Sentry, logs, alertas para código de IA em produção

---

### Módulo 4.7 — 🤖 Agentes Autônomos e Multi-Agent (~45 min)
*O futuro que já chegou: orquestrando múltiplos agentes*

1. **O espectro: autocomplete → agente → multi-agent** — entendendo a evolução
2. **Devin em 2025/2026** — 67% de PRs mergeados, Goldman Sachs e Nubank usando
3. **Claude Code como agente autônomo** — sessões longas, operações complexas
4. **Arquitetura multi-agent** — planejamento, implementação, revisão e teste em paralelo
5. **MCP na prática** — conectando agentes a bancos de dados, APIs e ferramentas
6. **OpenHands/OpenDevin** — alternativa open-source para experimentação
7. **Você como orquestrador** — o novo papel do engenheiro sênior em 2026

---

### Módulo 4.8 — 👥 Vibe Coding em Times (~35 min)
*Integrando IA no fluxo de trabalho de equipes de engenharia*

1. **O dev sênior como reviewer** — IA gera, humano revisa arquitetura e segurança
2. **Múltiplas ferramentas por papel** — IDE para dev diário, terminal para automação, enterprise para compliance
3. **PRs obrigatórios** — nenhum código de IA vai para main sem review humano
4. **Padronização de prompts e regras** — `.cursorrules` compartilhados no repo
5. **Testes de segurança no processo** — SAST/DAST integrado ao pipeline de time
6. **Medindo produtividade** — métricas que realmente importam (não só velocidade)
7. **O que deu errado** — 16 dos 18 CTOs reportaram desastres: lições documentadas

---

## TRILHA 2 — LEIGOS 🎨 (Purple)

**Público:** Empreendedores, product managers, designers, marketers, qualquer pessoa sem background técnico
**Nível:** Básico — sem jargão desnecessário
**Duração estimada:** ~3.5h
**Módulos:** 7 | **Tópicos:** ~49
**Pré-requisito:** Nenhum

---

### Módulo 2.1 — 🌟 Programar Sem Saber Programar (~30 min)
*A revolução que permite não-técnicos construírem produtos digitais*

1. **O que mudou em 2025** — por que agora é diferente de todas as promessas anteriores de no-code
2. **Casos reais** — reporter da CNBC construiu produto em 2 dias, fundador economizou $500K
3. **O que você PODE construir** — apps, automações, landing pages, MVPs, ferramentas internas
4. **O que você NÃO PODE (ainda)** — sistemas críticos, apps com milhões de usuários sem suporte técnico
5. **Quanto custa** — ferramentas gratuitas vs pagas, comparativo real
6. **Quanto tempo leva** — expectativas realistas para não-técnicos
7. **Seu roadmap pessoal** — do primeiro app ao primeiro produto monetizado

---

### Módulo 2.2 — 🔧 Escolhendo sua Ferramenta (~25 min)
*Guia sem jargão para encontrar a ferramenta certa para seu objetivo*

1. **Lovable** — melhor para apps com backend, interface linda, deploy incluído
2. **Bolt.new** — melhor para experimentar rápido direto no navegador
3. **v0 (Vercel)** — melhor para sites e apps Next.js com banco de dados
4. **Replit Agent** — melhor para automações, bots e integrações
5. **ChatGPT/Claude com código** — quando usar IA de chat ao invés de ferramenta especializada
6. **Tabela de decisão** — "Quero construir X, uso Y"
7. **Como testar antes de pagar** — free tiers e como aproveitar ao máximo

---

### Módulo 2.3 — 🛠️ Construindo seu Primeiro App (~40 min)
*Passo a passo prático para criar algo funcional do zero*

1. **Definindo o que construir** — a importância de começar pequeno e bem definido
2. **Escrevendo o briefing** — como descrever seu app para a IA de forma eficaz
3. **O primeiro prompt** — template que funciona para não-técnicos
4. **Interpretando o resultado** — como avaliar o que foi gerado sem saber código
5. **Pedindo ajustes** — "mude o botão de azul para verde" e variações mais complexas
6. **Testando funcionalidades** — como garantir que funciona antes de mostrar para outros
7. **Salvando versões** — conceito de "snapshot" para não perder progresso

---

### Módulo 2.4 — 🎯 Do Protótipo ao Produto (~35 min)
*Como transformar o primeiro app em algo que outras pessoas usam*

1. **A diferença entre protótipo e produto** — funcional vs. pronto para usuários reais
2. **Feedback de usuários** — como coletar e traduzir em ajustes de prompt
3. **Design sem designer** — pedindo para a IA melhorar a UX/UI com instruções simples
4. **Banco de dados** — armazenando informações de usuários (sem saber SQL)
5. **Login e cadastro** — autenticação para apps com usuários
6. **Performance básica** — quando o app fica lento e como pedir para a IA otimizar
7. **Quando contratar um desenvolvedor** — sinais claros de que chegou a hora

---

### Módulo 2.5 — 🔌 Integrações: Conectando Tudo (~30 min)
*APIs, pagamentos, emails e outras conexões sem escrever código*

1. **O que é uma API** — a explicação mais simples possível
2. **Pagamentos** — integrando Stripe ou Mercado Pago com linguagem natural
3. **WhatsApp e email** — notificações automáticas por mensagem
4. **Google Sheets** — usando planilhas como banco de dados simples
5. **Zapier/n8n** — quando a IA não consegue, a automação low-code resolve
6. **OpenAI/Claude na sua aplicação** — adicionando IA dentro do seu produto
7. **Testando integrações** — como verificar que os dados estão indo e voltando certo

---

### Módulo 2.6 — 💰 Publicando e Monetizando (~30 min)
*Colocando no ar e gerando receita com seu produto digital*

1. **Deploy com um clique** — Vercel, Lovable, Render: opções e diferenças
2. **Domínio personalizado** — comprando e configurando seu .com.br
3. **Modelos de monetização** — assinatura, freemium, pagamento único, ads
4. **Stripe para recorrência** — mensalidade com checkout pronto
5. **Precificação** — como definir o valor sem ser dev nem designer
6. **Primeiros usuários** — onde encontrar os primeiros 100 clientes
7. **Do $0 ao primeiro $1.000 MRR** — o caminho que empreendedores já percorreram

---

### Módulo 2.7 — ⚠️ O Que Pode Dar Errado (e Como Evitar) (~25 min)
*Os riscos reais para não-técnicos que precisam conhecer*

1. **Apps que expuseram dados** — o caso Lovable com 18K usuários (em linguagem acessível)
2. **O problema das senhas e chaves** — por que você NUNCA deve compartilhar o código público com segredos
3. **Dados de usuários** — LGPD em 5 minutos: o mínimo que você precisa saber
4. **Quando o app cai** — plano de contingência para produto em produção
5. **Backup** — como garantir que seus dados não desaparecem
6. **Checklist antes de lançar** — 10 perguntas para validar antes de ir ao ar
7. **Seguro técnico** — quando e como contratar revisão profissional

---

## TRILHA 3 — EXECUTIVOS 📊 (Amber)

**Público:** CEOs, CTOs, VPs, diretores, gerentes de produto e negócios
**Nível:** Estratégico + Prático — teoria com mãos na massa
**Duração estimada:** ~4h
**Módulos:** 8 | **Tópicos:** ~56
**Pré-requisito:** Nenhum

---

### Módulo 3.1 — 📈 O Impacto Real nos Negócios (~35 min)
*Dados, cases e o que isso significa para sua empresa*

1. **O momento de inflexão** — de brincadeira no Twitter a Collins Word of the Year em 10 meses
2. **Os números que importam** — Cursor $9,9B, Lovable $1M→$100M ARR em 8 meses, Replit $2,8M→$150M
3. **21% das startups YC com 91%+ de código por IA** — o que isso significa para o mercado
4. **Casos enterprise** — Goldman Sachs, Santander, Nubank, Accenture, IBM usando Devin
5. **Times menores, output maior** — "times de 10 vibe coders fazendo o trabalho de 50-100 engenheiros" (YC CEO)
6. **O que é hype vs. o que é real** — separando narrativa de evidência
7. **Sua empresa está atrasada?** — diagnóstico de maturidade em IA para desenvolvimento

---

### Módulo 3.2 — 💹 ROI, Métricas e Como Avaliar (~30 min)
*Como medir se o investimento em vibe coding vale a pena*

1. **O paradoxo da velocidade** — 55% mais rápido em tarefas simples, 19% mais lento em tarefas complexas (METR 2025)
2. **Onde o ROI é real** — boilerplate (81% mais rápido), CRUD, APIs, landing pages
3. **Onde o ROI é questionável** — sistemas legacy, código crítico, compliance
4. **Métricas que realmente importam** — não só velocidade (velocidade, qualidade, segurança, dívida técnica)
5. **Custo total da adoção** — ferramentas + treinamento + retrabalho + revisão de segurança
6. **Framework de avaliação** — como fazer um piloto e medir resultados corretamente
7. **O custo de NÃO adotar** — o risco competitivo de ficar para trás

---

### Módulo 3.3 — 🗺️ Estratégia de Adoção na sua Empresa (~35 min)
*Do piloto à escala: como implementar sem criar caos*

1. **Os 3 modelos de adoção** — gradual (mais seguro), paralelo (mais rápido), total (mais arriscado)
2. **Começando pelo MVP interno** — ferramentas internas são o piloto mais seguro
3. **Quem treinar primeiro** — seniors como multiplicadores vs. juniors como early adopters
4. **Selecionando as ferramentas corretas** — Cursor para devs, Lovable para PMs, Claude Code para automação
5. **Governança de uso** — políticas de code review, aprovação de PRs, dados sensíveis
6. **Change management** — como lidar com resistência da equipe técnica
7. **Roadmap de 90 dias** — do piloto ao processo padrão

---

### Módulo 3.4 — 🛡️ Riscos, Governança e Segurança (~30 min)
*O que todo executivo precisa saber antes de autorizar vibe coding em produção*

1. **Os dados de risco** — 16 de 18 CTOs reportaram desastres em produção, 2,74x mais vulnerabilidades
2. **Os incidentes reais** — Lovable 18K usuários expostos, Base44, casos de código deletado por agente
3. **Propriedade intelectual** — quem é dono do código gerado por IA?
4. **LGPD e código de IA** — responsabilidades jurídicas ao usar dados de usuários em prompts
5. **Política de uso seguro** — o que deve e o que não deve ser enviado para LLMs externos
6. **Arquitetura de governança** — aprovações, checklists, SAST obrigatório
7. **Quando NÃO usar vibe coding** — sistemas financeiros, saúde, infraestrutura crítica

---

### Módulo 3.5 — 🔭 O Futuro: Do Vibe Coding ao Agentic Engineering (~30 min)
*Para onde estamos indo e como se preparar*

1. **Karpathy em fevereiro de 2026** — "vibe coding já está ultrapassado, o futuro é agentic engineering"
2. **O que é agentic engineering** — múltiplos agentes em paralelo, humano como orquestrador
3. **40% do software enterprise via agentes até 2026** — a projeção que está se confirmando
4. **O novo perfil de engenheiro** — orquestrar e supervisionar, não mais escrever
5. **Impacto no mercado de trabalho** — juniores em risco, seniors mais valiosos, habilidades de IA +28% no salário
6. **Posicionamento estratégico** — como sua empresa pode liderar a transição
7. **O investimento que vale** — treinar revisão crítica de código de IA > treinar geração de código

---

### Módulo 3.6 — 📊 Criando Dashboards a partir de Dados e Planilhas (~35 min)
*Transforme planilhas e bases de dados em dashboards visuais sem saber programar*

1. **O que é possível** — do Excel/Google Sheets a um dashboard interativo em minutos
2. **Preparando seus dados** — como estruturar a planilha para a IA entender e usar
3. **Descrevendo o dashboard que você quer** — template de prompt para executivos
4. **Gráficos, tabelas e KPIs** — pedindo os componentes visuais certos
5. **Conectando dados reais** — integração com Google Sheets, Airtable e CSV
6. **Filtros e interatividade** — dashboards que o time consegue usar sozinho
7. **Publicando e compartilhando** — deixando o dashboard acessível para a equipe

---

### Módulo 3.7 — 🔄 Criando Soluções de Fluxo e Automação (~35 min)
*Automatize processos repetitivos do seu negócio com IA como orquestradora*

1. **O que é um fluxo** — da aprovação de despesas ao onboarding de clientes
2. **Mapeando o processo atual** — como descrever um fluxo de negócio para a IA
3. **Automação de notificações** — email, WhatsApp e Slack disparados por eventos
4. **Fluxo de aprovação** — formulário → notificação → registro automático
5. **Integrações com sistemas existentes** — conectando CRM, ERP e planilhas
6. **Monitoramento do fluxo** — como saber se a automação está funcionando
7. **Caso real** — onboarding de colaborador automatizado do início ao fim

---

### Módulo 3.8 — 🤖 Criando um Assistente Personalizado (~40 min)
*Construa um assistente com a inteligência do seu negócio — sem saber programar*

1. **O que é um assistente personalizado** — diferença entre ChatGPT genérico e um assistente treinado no seu contexto
2. **Definindo o escopo** — assistente de RH, vendas, suporte, onboarding ou jurídico
3. **Alimentando com conhecimento** — como fornecer documentos, políticas e dados internos
4. **Criando a interface** — chat simples que qualquer colaborador consegue usar
5. **Integrando com o WhatsApp ou Slack** — onde seu time já está
6. **Testando e ajustando** — validando respostas antes de liberar para o time
7. **Governança do assistente** — controle de acesso, atualização de base e limites de uso

---

## LANDING PAGE (index.html)

### Seções Obrigatórias

1. **Hero** — Título impactante com dados reais (Collins Word of the Year 2025)
2. **O que é Vibe Coding** — definição curta e direta
3. **As 4 Trilhas** — cards visuais com público-alvo claro
4. **Por que agora** — urgência baseada em dados de mercado
5. **O que você vai aprender** — benefícios concretos por trilha
6. **CTA** — botão para cada trilha

---

## CONTAGENS FINAIS

| Trilha | Módulos | Tópicos | Duração |
|--------|---------|---------|---------|
| T1 — Fundamentos | 8 | 56 | ~4h |
| T2 — Técnicos | 8 | 56 | ~5h |
| T3 — Leigos | 7 | 49 | ~3.5h |
| T3 — Executivos | 8 | 56 | ~4h |
| **TOTAL** | **31** | **217** | **~16.5h** |

**Arquivos HTML:** 33 (1 landing + 4 trilhas + 28 módulos)

---

## ORDEM DE PRODUÇÃO SUGERIDA

1. `index.html` — Landing page (referência visual para todo o resto)
2. `curso/fundamentos/index.html` + módulos 1.1–1.8 (template base)
3. `curso/leigos/index.html` + módulos 2.1–2.7 (público mais amplo)
4. `curso/executivos/index.html` + módulos 3.1–3.8 (decisores impactam adoção)
5. `curso/tecnicos/index.html` + módulos 4.1–4.8 (mais denso, por último)

---

## PADRÕES DE DESIGN (conforme MASTER_COMPLETO.md)

- **Framework:** TailwindCSS via CDN
- **Fonte:** Inter (Google Fonts)
- **Dark mode:** padrão, com toggle para light mode
- **Topicos expansíveis:** 3 seções obrigatórias (O que é / Por que / Conceitos-chave)
- **Botões:** sempre alinhados à ESQUERDA (`justify-start`)
- **Números:** em círculo, NUNCA setas
- **Modal:** iframe carregando página do módulo
- **Link obrigatório:** INEMA.CLUB em sky-400 em todas as páginas

---

*Plano gerado em 2026-03-03 — pronto para aprovação antes do início da produção*
