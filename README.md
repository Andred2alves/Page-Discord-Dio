# Desafio de Responsividade DIO — Clone da página do Discord

Reprodução da homepage do Discord feita com HTML + CSS puro, a partir do
layout do Figma "Desafio Responsividade - DIO".

## Estrutura

```
desafio-discord/
├── index.html      # Estrutura da página
├── style.css       # Todos os estilos + media queries
└── assets/         # Imagens (fundo do hero, 4 ilustrações das seções, rodapé)
```

## Como abrir no VS Code

1. Extraia o `desafio-discord.zip` em uma pasta do seu computador.
2. No VS Code: **Arquivo → Abrir Pasta** e selecione a pasta `desafio-discord`.
3. Para ver a página rodando:
   - **Opção 1 (recomendada):** instale a extensão **Live Server** no VS Code,
     clique com o botão direito no `index.html` → **Open with Live Server**.
   - **Opção 2:** clique duas vezes no `index.html` para abrir direto no navegador.

## Testando a responsividade

- No navegador, aperte **F12** → ícone de dispositivo móvel (ou **Ctrl+Shift+M**)
  e alterne entre larguras (ex.: 1280px desktop e 428px iPhone 13 Pro Max).
- Redimensione a janela: abaixo de **768px** a página muda para o layout mobile
  (seções empilhadas com a ilustração primeiro, botões do hero em largura cheia,
  tipografia menor).

## O que foi praticado

- Flexbox (`display: flex`, `gap`, `row-reverse`, `order`)
- Media queries e breakpoint mobile
- Unidades relativas e imagens fluidas (`max-width: 100%`)
- Google Fonts (Luckiest Guy + Open Sans)
- Botões pill com hover
