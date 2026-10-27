<!-- l10n-sync: source-file="workshop/06-bonus.md" -->
# 🎉 Bônus e extensões

---

Você criou um aplicativo de batalha do GitHub totalmente funcional! Agora é hora de avançar com estes **desafios abertos**.

<!-- track:vscode:start -->
Use o **Agent Mode** para todos os desafios: descreva o que você quer e deixe o Copilot ajudar na implementação.
<!-- track:vscode:end -->

<!-- track:cli:start -->
Use o Copilot CLI para todos os desafios: combine o contexto com `@file`, `/plan`, o modo normal e `/review` quando precisar.
<!-- track:cli:end -->

---

## 🏆 Desafio 1: Anúncio do vencedor

Depois que os gráficos de contribuições dos dois usuários forem carregados, compare os totais e exiba um anúncio dinâmico do vencedor.

**O que criar:**
- Compare o total de contribuições dos dois usuários
- Se houver um vencedor claro, exiba **"🏆 {username} WINS! 🏆"** com um estilo comemorativo
- Se as contribuições forem iguais, exiba **"🤝 IT'S A TIE! 🤝"**
- Adicione uma animação ou confete para dar mais destaque

**Sugestão de prompt:**
> After both users' contribution data loads, compare total contributions and display a winner banner. Show "🏆 {username} WINS! 🏆" if one user has more contributions, or "🤝 IT'S A TIE! 🤝" if equal. Make it visually exciting with CSS animations.

---

## 🏆 Desafio 2: Contador de sequência

Calcule e exiba a sequência de contribuições consecutivas mais longa de cada usuário.

**O que criar:**
- Analise os dados de contribuições dia a dia
- Encontre a sequência mais longa de dias consecutivos com pelo menos uma contribuição
- Exiba em destaque o número de dias da sequência de cada usuário
- Destaque quem tem a sequência mais longa

**Sugestão de prompt:**
> Add a streak counter feature that analyzes each user's contribution data to find their longest consecutive contribution streak. Display "🔥 Longest Streak: X days" for each user below their contribution graph.

---

## 🏆 Desafio 3: Histórico de batalhas

Salve os resultados das batalhas para que os usuários possam consultar os confrontos anteriores.

**O que criar:**
- Salve cada resultado em `localStorage` (nomes de usuário, totais, vencedor e data/hora)
- Adicione uma seção **"Recent Battles"** abaixo da área principal da batalha
- Exiba as últimas 5–10 batalhas com os resultados
- Adicione um botão "Clear History"

**Sugestão de prompt:**
> Save battle results to localStorage after each comparison. Add a "Recent Battles" section that displays the last 10 battles with usernames, contribution totals, the winner, and when the battle happened. Include a "Clear History" button.

---

## 🏆 Desafio 4: Efeitos sonoros

Adicione efeitos sonoros de arcade retrô usando a Web Audio API, sem arquivos externos.

**O que criar:**
- Som de **moeda inserida** quando o botão "Battle!" for clicado
- Som de **power-up** quando os resultados forem carregados com sucesso
- Som de **explosão** quando ocorrer um erro (usuário não encontrado ou falha da API)
- Um botão para silenciar ou ativar o som

**Sugestão de prompt:**
> Add retro arcade sound effects using the Web Audio API (no audio files). Play a coin insert sound on battle start, a power-up sound when results load, and an explosion sound on errors. Generate the sounds programmatically with oscillators and gain nodes. Include a mute toggle.

---

## 🏆 Desafio 5: Sequência de batalha animada

Crie suspense com uma contagem regressiva dramática antes de revelar os resultados.

**O que criar:**
- Ao clicar em "Battle!", exiba uma sobreposição em tela cheia
- Anime: **"3..."** → **"2..."** → **"1..."** → **"⚡ FIGHT! ⚡"**
- Depois, revele os gráficos de contribuições com uma entrada dramática
- Use animações CSS ou temporizadores de JavaScript

**Sugestão de prompt:**
> Add an animated battle sequence when the user clicks "Battle!". Show a countdown overlay: "3..." then "2..." then "1..." then "⚡ FIGHT! ⚡" with each step lasting about 1 second. After the countdown, reveal the results with a slide-in animation.

---

## 🏆 Desafio 6: Legenda de contribuições

Adicione uma legenda de escala de cores que corresponda à paleta do gráfico de contribuições.

**O que criar:**
- Uma legenda horizontal com os níveis de intensidade das contribuições
- Rótulos de **"Less"** a **"More"**
- Use a paleta de cores real da resposta da API de contribuições do GitHub
- Posicione-a perto dos gráficos de contribuições

**Sugestão de prompt:**
> Add a contribution legend below the graphs showing the color scale from the API's color palette. Display a row of colored squares ranging from "Less" (lightest) to "More" (darkest), matching the actual contribution level colors returned by the API.

---

## 🏆 Desafio 7: Compartilhe os resultados

Permita que os usuários compartilhem os resultados de uma batalha com um único clique.

**O que criar:**
- Um botão **"📋 Share Results"** que aparece após uma batalha
- Copie um resumo formatado em texto para a área de transferência
- Inclua os nomes de usuário, o total de contribuições e o vencedor
- Exiba brevemente a confirmação "Copied!"

**Sugestão de prompt:**
> Add a "📋 Share Results" button that copies a formatted battle summary to the clipboard. The summary should include both usernames, their contribution totals, and who won. Use the Clipboard API and show a brief "Copied to clipboard!" confirmation.

---

<!-- track:cli:start -->
## 💻 Extras do CLI

Se quiser explorar mais recursos do Copilot CLI depois do workshop principal:

- Use `copilot -p "Write a conventional commit message for the current git diff"` para gerar uma resposta única que você pode colar no Git.
- Execute `/share file` para salvar a sessão como Markdown e consultar depois.
- Use `/session` e `/session plan` para inspecionar como o CLI acompanha seu trabalho atual.
<!-- track:cli:end -->

## 🎊 Parabéns!

Você concluiu o workshop **Mona Mayhem: GitHub Battle**! Veja o que você realizou:

### O que você criou

- ✅ Um **aplicativo web completo com várias páginas** a partir de uma especificação de design
- ✅ Uma **página inicial** com tema de arcade retrô e layout responsivo
- ✅ Uma **arena de batalha** que busca e compara dados reais de contribuições do GitHub
- ✅ **Gráficos de contribuições interativos** com níveis de atividade diferenciados por cores
- ✅ **Tratamento de erros, estados de carregamento e melhorias de acessibilidade**
- ✅ **Design responsivo** para vários dispositivos

### O que você praticou

| Habilidade | O que você praticou |
|---|---|
| **Engenharia de contexto** | Fornecer ao Copilot os arquivos, as instruções e as restrições adequadas |
| **Planejamento** | Gerar e refinar planos de implementação antes de programar |
| **Programação agêntica** | Delegar ao Copilot tarefas com várias etapas e arquivos |
| **Iteração de design** | Começar com uma direção visual e refiná-la até obter um resultado polido |
| **Disciplina de revisão** | Inspecionar alterações geradas por IA antes de fazer commit |

### 🚀 Continue aprendendo

- 📺 [Canal do YouTube do VS Code](https://www.youtube.com/@code) — Dicas, tutoriais e novidades
- 📖 [Documentação do GitHub Copilot](https://docs.github.com/en/copilot) — Documentação e guias oficiais
- 💻 [Documentação do GitHub Copilot CLI](https://docs.github.com/en/copilot/how-tos/copilot-cli) — Instalação, comandos slash e boas práticas
- 🌟 [Awesome GitHub Copilot](https://github.com/stefanprodan/awesome-github-copilot) — Recursos e exemplos da comunidade
- 🛠️ [Workshops do Copilot Dev Days](https://github.com/github/copilot-dev-days) — Mais workshops práticos

---

## 🙏 Obrigado!

Obrigado por participar deste workshop! Você viu como o GitHub Copilot pode acelerar todas as etapas do desenvolvimento, do planejamento e design à implementação e ao polimento. As técnicas praticadas aqui servem para qualquer projeto, framework e escala. Agora vá criar algo incrível! 🚀
