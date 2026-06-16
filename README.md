# Rubinho Landing Page Kit

Template open-source de landing page feito pelo **Rubinho** para o pessoal aproveitar, estudar, adaptar e usar em projetos reais.

Este projeto foi criado para quem quer uma landing page moderna, rápida e fácil de personalizar usando apenas **HTML, CSS e JavaScript puro**.

## Demos incluídas

- Stand automóvel
- Café / restaurante
- Loja de roupa / streetwear

## Funcionalidades

- Layout moderno e responsivo
- Modo claro / escuro
- Menu mobile
- Botão flutuante de WhatsApp
- FAQ interativo
- Animações suaves ao scroll
- Conteúdo configurável via JavaScript
- Sem frameworks
- Fácil de adaptar para qualquer projeto

## Estrutura

```txt
rubinho-landing-page-kit/
├── index.html
├── styles.css
├── script.js
├── package.json
├── LICENSE
└── README.md
```

## Como usar

### Abrir direto

Abre o ficheiro `index.html` no browser.

### Usar com servidor local

```bash
npm install
npm run dev
```

Depois abre o endereço indicado no terminal.

## Como personalizar

### Textos das demos

Edita o objeto `demos` no ficheiro `script.js`.

```js
const demos = {
  cars: {
    brand: 'A tua marca',
    title: 'A tua headline principal.'
  }
};
```

### Cores

Edita as variáveis no topo do ficheiro `styles.css`:

```css
:root {
  --bg: #f7f7f2;
  --text: #151515;
  --accent: #d7ff5f;
}
```

### WhatsApp

No `index.html`, troca o número nos links:

```html
https://wa.me/351900000000
```

Substitui pelo teu número.

## Publicar no GitHub Pages

1. Cria um repositório no GitHub.
2. Envia estes ficheiros para o repositório.
3. Vai a **Settings > Pages**.
4. Escolhe a branch `main` e a pasta `/root`.
5. Guarda e espera o link ficar ativo.

## Créditos

Feito pelo **Rubinho**.

Podes usar, alterar, melhorar e partilhar.

## Licença

MIT License.
