<!-- l10n-sync: source-file="workshop/00-overview.md" -->
# 🎮 Mona Mayhem — Workshop de GitHub Copilot

---

> **Duração:** ~1 hora  
> **Nível:** Intermediário  
> **Stack:** Astro / Node.js / TypeScript

Crie um aplicativo de arcade retrô para comparar contribuições do GitHub — **Mona Mayhem** — enquanto aprende toda a variedade de fluxos de trabalho do GitHub Copilot. O workshop oferece **duas trilhas**: uma experiência com VS Code e outra com GitHub Copilot CLI.

---

## 🎯 Escolha sua trilha

- **Trilha do VS Code** — trabalhe dentro do editor e pratique Chat, Plan Mode, Agent Mode, agentes em segundo plano e o ciclo de revisão integrado.
- **Trilha do CLI** — trabalhe no terminal e pratique `copilot`, contexto com `@file`, `/plan`, edições autônomas, `/fleet`, `/delegate` e `/review`.

Siga a trilha que combina com seu fluxo de trabalho.

---

## 📋 Lista rápida de verificação

Antes de começar, verifique se:

- [ ] O GitHub Copilot está habilitado na sua conta
- [ ] O Node.js está instalado
- [ ] O Git está instalado e configurado
- [ ] Seu navegador e terminal estão prontos

<!-- track:vscode:start -->
- [ ] VS Code **v1.107+** (sem atualizações pendentes)
- [ ] Você entrou na extensão do **GitHub Copilot**
- [ ] O painel de Chat está aberto e o Agent está pronto
<!-- track:vscode:end -->

<!-- track:cli:start -->
- [ ] O GitHub Copilot CLI está instalado e disponível como `copilot`
- [ ] Você se autenticou no CLI com `/login`
- [ ] Você está à vontade com comandos slash como `/help`, `/plan` e `/review`
<!-- track:cli:end -->

> 💡 **Dica:** Use o DevContainer para começar rapidamente com um ambiente pré-configurado no VS Code.

---

## 🧠 O que você vai aprender

| # | Habilidade | Descrição |
|---|------------|-----------|
| 1 | **Engenharia de contexto** | Ensinar ao Copilot sobre sua base de código com instruções, referências e restrições claras |
| 2 | **Planejar primeiro** | Projetar a arquitetura antes da implementação |
| 3 | **Implementação agêntica** | Deixar o Copilot realizar tarefas de programação em várias etapas sob sua supervisão |
| 4 | **Design iterativo** | Usar o Copilot para transformar o visual e refinar detalhes de interação |
| 5 | **Fluxos de trabalho paralelos** | Dividir o trabalho entre agentes, sessões ou tarefas delegadas |

<!-- track:vscode:start -->
### Foco nos recursos do VS Code

- **Chat + modo Ask** para exploração
- **Plan Mode** para prompts de arquitetura e design
- **Agent Mode** para implementação em vários arquivos
- **Agentes em segundo plano e na nuvem** para polimento em paralelo
<!-- track:vscode:end -->

<!-- track:cli:start -->
### Foco nos recursos do Copilot CLI

- **Sessões interativas do CLI** com `copilot`
- **`/plan` e Shift+Tab** para planejamento estruturado
- **Edições autônomas** com aprovações inline e `/diff`
- **`/fleet`, `/delegate` e `/review`** para paralelismo e verificações de qualidade
<!-- track:cli:end -->

---

## 📚 Partes do workshop

| Parte | Título | Descrição |
|------|-------|-----------|
| [**01**](01-setup.md) | Configuração e engenharia de contexto | Crie seu repositório, prepare seu ambiente e forneça o contexto adequado ao Copilot |
| [**02**](02-plan-and-scaffold.md) | Planejamento e scaffold | Projete a API e a arquitetura de páginas antes de implementar |
| [**03**](03-agent-mode.md) | Construção do jogo | Conecte a página de batalha e os gráficos de contribuições com ajuda agêntica |
| [**04**](04-design-vibes.md) | Design em primeiro lugar | Transforme a estrutura inicial em uma experiência de arcade retrô |
| [**05**](05-polish.md) | Polimento e trabalho paralelo | Use fluxos multiagente para melhorar UX, resiliência e qualidade |
| [**06**](06-bonus.md) | Bônus e extensões | Explore funcionalidades abertas, fluxos de compartilhamento e experimentos extras |

---

## 💡 Dicas profissionais

1. **Mantenha o navegador aberto** — acompanhe as atualizações em tempo real enquanto programa.
2. **Faça commits com frequência** — salve pontos de controle limpos enquanto itera.
3. **Refine o plano antes de implementar** — planos melhores levam a resultados melhores.
4. **Revise as alterações do Copilot** — use a visualização de diff ou as ferramentas de revisão do CLI em vez de aceitar sem conferir.

<!-- track:vscode:start -->
5. **Use pontos de controle e Desfazer** no chat se uma iteração sair do rumo.
<!-- track:vscode:end -->

<!-- track:cli:start -->
5. **Use `/session`, `/context` e `/share file`** para inspecionar ou preservar seu trabalho.
<!-- track:cli:end -->
