# Site — Andréa Barreto Assessoria Contábil

Site de página única em HTML, CSS e JavaScript puros (sem instalação, sem build, sem backend).

## Como ver
Abra `index.html` no navegador (as fontes do Google exigem internet).

## Como publicar
Envie esta pasta para qualquer hospedagem estática (Netlify, Vercel, GitHub Pages, Cloudflare Pages ou a hospedagem do seu domínio). O arquivo principal é `index.html`.

## O que editar (tudo dentro de `index.html`, no final, na tag `<script>`)
- **WhatsApp:** `CONFIG.whatsapp`, hoje `"5581983001393"` (país + DDD + número, só dígitos).
- **Mensagem automática:** função `msg`. Cada botão tem o atributo `data-need`, que completa a frase "Minha necessidade principal é ...".
- **Clientes:** lista `CLIENTES`. Cada item aceita `nome` (obrigatório), `instagram`, `descricao` e `imagem`. Exemplo:
  `{nome:"Nome da Empresa", instagram:"@usuario", descricao:"Uma frase.", imagem:"clientes/empresa.jpg"}`
  Publique apenas clientes que autorizaram. Fotos em proporção 4:3 ficam na pasta `clientes/`.
- **Contato:** WhatsApp, Instagram `@ab_contabiloficial` e e-mail `abcontabil2026@gmail.com` estão na seção final e no rodapé.
- **Cores:** variáveis no início do `<style>` (`--g` verde, `--gold` dourado, `--ivory` marfim).

## Pendências
- Endereço e horário de atendimento (a página avisa que serão publicados após confirmação).
- Confirmar quais serviços são realmente oferecidos (os quatro atuais foram supostos a partir do briefing).
- Confirmar o texto de "Como funciona o atendimento".
- Seção "Sobre a Andréa" (foto, história, formação), ainda não criada.
- Dados estruturados (SEO local), sitemap e metadados de compartilhamento, que dependem do domínio e do endereço.
- Logo com fundo transparente, se existir.

## Limitações
Este é um protótipo em arquivo único, não o projeto React/Vite/Tailwind do briefing original, e é uma página só, sem páginas individuais de serviços nem artigos. Não foi aberto em navegador durante o desenvolvimento: faça a revisão visual, de responsividade e o clique nos botões do WhatsApp antes de publicar.
