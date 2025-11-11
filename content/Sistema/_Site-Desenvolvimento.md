---
title: 🚧 Site Em Desenvolvimento
aliases:
  - 🚧 Site Em Desenvolvimento
  - 🚧 Site Implementação
  - 🚧 Implementação Site
---

⬆ 

---

# ℹ Intro

Este documento registra o processo contínuo de criação e aprimoramento do meu site — que é uma mistura entre  🌐 Wiki, 🌱 Jardim Digital e 💼 Portfólio.

%% 

#link-note acima!

%%

Nada aqui está “pronto”. 

Tudo está em constante movimento, como um organismo vivo em transformação.  

> [!seealso]- Curiosidade
> Escolhi tornar isso (planejamento de desenvolvimento) também público, para que eu evite de ficar trabalhando *offiline* esperando o site “ficar pronto”; perseguindo uma perfeição que nunca vai acontecer.


--- 

# 🌟 Destaques

Os marcos mais significativos do desenvolvimento do site — incluindo decisões de design, aprendizados e reviravoltas conceituais.  

Aqui entram também pensamentos, dúvidas e pequenas epifanias do processo.

> [!note]- 25/10/2025
> Construir em público exige vulnerabilidade — mas também traz uma tranquilidade, como se o site respirasse junto comigo.
> Sim, a transparência demanda mais organização, mas recompensa com clareza: consigo “ver” o começo, o meio e o fim dos projetos e tarefas.
> E olha que ainda nem públiquei… Mas já observo meu pensamento (e Obsidian) em maior ressoância.

> [!note]- 29/10/2025
> Enfim implementei o site. Com toda certeza não esta do jeito que eu gostaria, mas está online.
> E só esta online porque eu decidi deixar toda a alteração de HTML/CSS para depois.
> “Primeiro o esqueleto, depois a moda” é o que “mantralizo” pra mim continuar em movimento…


--- 

# 📌 Commits

Este guia define o padrão de commits adotado no desenvolvimento do site.

O objetivo é manter clareza, consistência e facilidade de navegação.

O formato é o seguinte:

`<tipo>(<escopo opcional>): <mensagem breve opcional>`

Eu separei em duas “linhas” de trabalho:

- **🌼 Linha Criativa**
	- Envolve conteúdo, projetos e tarefas 
	- → `Content`
- **⚙️ Linha Técnica**
	- Envolve sistema, estruturas, design, correções e automações.  
	→ `System`, `Meta`, `Fix`, `Refactor`, `Design`, `Structure`

E sigo essas boas práticas:

> [!hint]- Dicas
> - Use **mensagens curtas e descritivas** (preferencialmente em português).
> - Se fizer várias mudanças pequenas do mesmo tipo, prefira **um commit por contexto** (não por arquivo).
> - Evite mensagens genéricas como “update” ou “ajustes”.

Enfim, o resumo do padrão de *commits*:

| Tipo         | Uso                                                                     | Exemplo                                                      |
| ------------ | ----------------------------------------------------------------------- | ------------------------------------------------------------ |
| 📝 Content   | Criação, edição ou exclusão de notas e conteúdos textuais.              | `📝 Content(Prisma): adiciona nova nota sobre álbum do dia.` |
| 🎨 Design    | Mudanças visuais — cores, tipografia, layout, espaçamento, imagens.     | `🎨 Design(Theme): melhora legibilidade dos títulos.`        |
| ⚙️ System    | Ajustes técnicos — build, deploy, scripts, automações, Quartz, plugins. | `⚙️ System(Quartz): corrige bug na navegação do menu.`       |
| 📁 Structure | Alterações de organização — pastas, rotas, hierarquia de notas.         | `📁 Structure: move notas de backlog para /projects.`        |
| 🐞 Fix       | Correções pontuais de bugs, erros de digitação, links, sintaxe.         | `🐞 Fix: corrige link quebrado na timeline.`                 |
| 🔧 Refactor  | Melhorias internas no código sem alterar o comportamento.               | `🔧 Refactor(HTML): simplifica estrutura do header.`         |

%% 

- 🧩 0.0.3  | 📝 Content(Implementação): Implementa espaço Olympia e subespaço Atletismo.
- 📝 Content(geral): Atualização.
- 🧩 0.0.4  | ⚙️ System(Conteúdo): altera a licença para CC BY-NC-SA 4.0 e atualiza footer.
%%

--- 

# 🧩 Changelog

%% 

> [!info]- Info
> → [[ba83ec703f]]
> → [[TPE - Site Unificado - Versionamento|Template]]

> [!todo]- A Fazer
> 🔷 Filtrar com dataview em nota *hash*, e criar lista estática com o plugin [Serializer](https://developassion.gitbook.io/obsidian-dataview-serializer/usage) para publicar no Quartz.
> ———
> #todo/P4

%%

Histórico das versões e melhorias implementadas ao longo do desenvolvimento do site.

- [[SU_VSN_0-0-1|🧩 0.0.1]]
- [[SU_VSN_0-0-2|🧩 0.0.2]]


--- 

# 🗃 Backlog

Este é (+ ou -) o planejamento das versões de desenvolvimento do site — um roteiro aberto do que está sendo construído e do que ainda virá.

## 📬 Inbox

- Projetos
	- AntiDoomScrooling
- Notas
	- Moc Aprendizados


## 🔥 Alpha

> [!important]- Out/2025 → Mar/2026  
> - **Objetivo:** criar uma base sólida e unificada entre os espaços do site e o fluxo de trabalho.  
>   Nesta fase, o foco é estruturar — organizar notas, conexões, navegação e hospedagem. É o esqueleto que vai sustentar tudo o que vem depois.  
> - **Não-objetivo:** estética visual, identidade de marca e automações em markdown. Essas camadas virão nas próximas fases.

- Home
	- Texto - Funcionamento do Site
- Páginas
	- Sobre
- Espaços / Sistemas
	- [[🧊 ID - Tipos de Conteudo]]
	- …
	- Kaleidoscopio
		- Musica
		- Jogos
		- Filmes
		- Leitura
		- YouTube
	- Projetos
	- Status
		- [[c1a8ec6823]]
	- Blog
- Notas
	- Avisos
		- Tags
		- Tags Inline


## ⏩ Beta

> [!note]- Abr/2026 → Jul/2026  
> - **Objetivo:** iniciar o trabalho de identidade visual e linguagem estética — definindo tipografia, cores e ritmo visual.  
> - **Não-objetivo:** alterações profundas na arquitetura ou automações de código.

- Páginas
	- Colophon
	- Faq
	- Call to Action
- Espaços / Sistemas
	- Notas Ilustradas
	- Liçensas
	- Newsletter e RSS
	- Lab-A
		- Manifesto / Diretrizes
			- [[e1a6706ce1]]
		- Sub-Categorias
			- Notas
			- [[9b3a57c4f7]]
			- Guias de Tempo
				- [[9916b068bd]]
		- Sobre
			- [[94ca9c0182]]
		- Processar
			- [[CVS-Insp-Lab-A.canvas|CVS-Insp-Lab-A]]
- Notas
	- Library e Antilibrary
	- Inspirações e Referências
	- Filosofia
- DEV (HTML/CSS/JS)
	- Home
		- *Não vai ser .md, e sim em HTML com seções em JSX;*
	- Filtro de Render
		- *.md com tags hash, ou baseado em arquivos com caminho relativo, não são renderizado links;*
		- *Isso melhora a acessibilidade ao não abrir a página 404;*
	- 404 - Voltar
		- *No Hugo tinha um metódo que chamava com base no proprio cache. Não sei como fazer em JSX;*
	- Link Embeds
		- *Remover texto e deixar somente emoji (↗). Também posicionar para o canto superior direito do callout.*
- Design
	- Logo
	- Tipografia
	- Forma
	- Cores
	- Imagens e Ilustração
	- Tipos de Notas, Sistemas e Covers
	- Formas e Cores por Espaços
- Outros
	- Nomenclatura de Diretório


## 📅 v1

> [!tip]- Ago/2026 → Dez/2026  
> - **Objetivo:** integrar a camada visual ao conteúdo, transformando o site em uma experiência coesa. Também a implementação de alguns componentes HTML.
> - **Não-objetivo:** experimentos técnicos avançados (HTML/CSS dinâmico).

- DEV (HTML/CSS/JS)
	- Menu
	- Hero
	- Footer
	- Listagens
		- Projetos
		- Blog
	- Acessibilidade
		- Alto Contraste
		- Som
		- Duração de Leitura
		- Dark Mode
	- Background Dinâmico
	- Imagens e Grids


## 📅 v2

> [!important]- 2027 → ...  
> - **Objetivo:** implementar sistemas dinâmicos e personalizações mais profundas (HTML, CSS, automações, layouts reativos).  
> - **Não-objetivo:** grandes reformulações conceituais — o foco é aprofundar o que já existe.

- DEV (HTML/CSS/JS)
	- Comentarios
	- Next e Prev Pages
	- Ouvindo Agora
- Configurar - Git SubModule

