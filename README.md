# 🎮 Tetris do Lima — Arcade Edition

Jogo de Tetris feito em HTML/JS puro, com fases, combos, avatares, música e efeitos.
Este repositório já está pronto para funcionar como **app instalável (PWA)** — o
jogador pode "Adicionar à tela inicial" no celular e ele abre em tela cheia, com
ícone próprio, igual um aplicativo de verdade.

## 📁 Arquivos

- `index.html` — o jogo completo (HTML + CSS + JS em um único arquivo)
- `manifest.json` — configurações do app (nome, ícone, cor, modo tela cheia)
- `sw.js` — service worker, permite o jogo funcionar offline depois da primeira visita
- `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` — ícones do app

## 🚀 Como publicar no GitHub Pages (gratuito)

1. Crie um repositório novo no GitHub (ex: `tetris-do-lima`).
2. Envie **todos os arquivos desta pasta** para o repositório (pode arrastar e
   soltar direto na página do GitHub, em "Add file" → "Upload files").
3. Vá em **Settings** → **Pages** (barra lateral esquerda).
4. Em "Source", escolha a branch `main` e a pasta `/ (root)`. Salve.
5. Espere 1 ou 2 minutos. O GitHub vai te dar um link parecido com:
   `https://SEU-USUARIO.github.io/tetris-do-lima/`
6. Abra esse link no celular. Pronto, o jogo já está no ar!

## 📲 Como instalar como app no celular

1. Abra o link do jogo pelo **Chrome** no Android.
2. Toque nos três pontinhos (⋮) no canto superior direito.
3. Toque em **"Adicionar à tela inicial"** (ou "Instalar app").
4. Confirme. Vai aparecer um ícone do jogo na tela inicial, igual qualquer app.

## 🛠️ Atualizando o jogo depois

Sempre que quiser trocar por uma versão nova do `index.html`, é só subir o
arquivo novo substituindo o antigo no repositório (mesmo nome: `index.html`).
O GitHub Pages atualiza sozinho em 1 ou 2 minutos.

---
Feito por Luciano. 🕹️
