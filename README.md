# Ricardo Juliano, Desenvolvedor Fullstack

Meu portfólio pessoal: uma página única com quem eu sou, no que trabalho e os projetos que já construí.

**Ver online:** https://meu-portfolio-sigma-self.vercel.app

![Prévia do portfólio](img/og-image.jpg)

## Sobre mim

Sou desenvolvedor fullstack, de Buenópolis, MG. Na web, trabalho com React, Next.js e TypeScript no front-end e com Node/Express ou Supabase e PostgreSQL no back-end. No Android, uso Kotlin e Jetpack Compose, e no projeto mais recente também escrevi a API em Kotlin, com Ktor e MongoDB. Meu projeto mais completo é a Boutique Arco-Íris, uma loja com checkout, painel administrativo e uma consultora de estilo feita com a API da Anthropic (Claude). Estou em transição de carreira e busco minha primeira oportunidade como desenvolvedor.

## Projetos em destaque

| Projeto | O que é | Stack |
|---|---|---|
| [Boutique Arco-Íris](https://github.com/RicardoJuliano/Boutique-Arco-ris) ([demo](https://boutique-arco-ris.vercel.app)) | Loja de moda com checkout, painel admin, importação de nota fiscal e consultora de estilo com IA | React, TypeScript, Node/Express, PostgreSQL, Claude API |
| [Vende no Zap](https://github.com/RicardoJuliano/vende-no-zap) ([demo](https://vende-no-zap.vercel.app)) | CRM leve para quem vende pelo WhatsApp (WhatsApp e Pix ainda não implementados) | Next.js, TypeScript, Supabase, Zod, Vitest |
| [App Pokémon](https://github.com/RicardoJuliano/App_Pokemon) ([APK](https://github.com/RicardoJuliano/App_Pokemon/releases/latest)) | Jogo Android de batalhas por turnos que funciona sem internet | Kotlin, Jetpack Compose, Room, Retrofit, Coroutines |
| [StudyTaks](https://github.com/RicardoJuliano/StudyTaks) | App Android de checklist de estudos com API própria (em andamento) | Kotlin, Jetpack Compose, Ktor, MongoDB, Docker |
| [Project Tilt](https://github.com/RicardoJuliano/Mini-game) | Jogo de corrida em que o celular vira o volante (um jogador contra bots; modo em grupo é a meta) | JavaScript, Three.js, WebSocket, Node |
| [Resumo Fácil (booktube)](https://github.com/RicardoJuliano/booktube) | Ferramenta de linha de comando que produz vídeos-resumo de livros | Node, FFmpeg, Claude API, ElevenLabs |
| [Touch Hero](https://github.com/RicardoJuliano/Touch-Hero) | Jogo de ritmo estilo Guitar Hero com detecção de toques | Kotlin, Jetpack Compose |
| [trokei](https://github.com/RicardoJuliano/trokei) ([demo](https://trokei-seven.vercel.app)) | Brechó online com catálogo e cadastro de produtos (protótipo) | HTML, CSS, JavaScript |
| [Maison Vêtir](https://github.com/RicardoJuliano/maison-vetir) ([demo](https://ricardojuliano.github.io/maison-vetir/)) | Vitrine de moda premium só com front-end | HTML, CSS, JavaScript |
| [NEXUS](https://github.com/RicardoJuliano/NEXUS-SITE) ([demo](https://ricardojuliano.github.io/NEXUS-SITE/)) | Landing conceitual futurista, um experimento visual | HTML, CSS, JavaScript |
| [Landing Pages](https://github.com/RicardoJuliano/landinpages) | Estudos de design responsivo | HTML5, CSS3, JavaScript |

## Como o site foi feito

- **HTML, CSS e JavaScript puros**, sem framework e sem etapa de build. Tudo está em um único `index.html`.
- **Animações de entrada** ao rolar a página, feitas com `IntersectionObserver`.
- **Vídeos dos cards** só tocam enquanto estão visíveis na tela, para economizar dados e bateria.
- **Layout responsivo**, com menu para celular e ajustes para telas estreitas.
- **Sem JavaScript:** o conteúdo continua visível se o script não carregar.
- **Compartilhamento:** metatags Open Graph e Twitter Card, com imagem de prévia.
- **Fontes:** Playfair Display, Qwitcher Grypen e IBM Plex Mono, via Google Fonts.

## Rodando localmente

Não precisa instalar nada. Clone o repositório e abra o arquivo no navegador:

```bash
git clone https://github.com/RicardoJuliano/meu-portfolio.git
cd meu-portfolio
```

Abra o `index.html`, ou, se preferir um servidor local:

```bash
npx serve .
```

## Estrutura

```
meu-portfolio/
├── index.html   # página inteira (HTML, CSS e JS)
├── img/         # fotos, capas dos projetos e imagem de prévia
└── video/       # vídeos curtos dos cards
```

## Contato

- E-mail: rjulianojunior@gmail.com
- GitHub: [RicardoJuliano](https://github.com/RicardoJuliano)
- LinkedIn: [ricardo-juliano](https://www.linkedin.com/in/ricardo-juliano)
