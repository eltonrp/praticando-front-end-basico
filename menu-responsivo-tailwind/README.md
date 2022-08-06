# Menu Responsivo com Tailwind
* Uso do Framework Tailwind
* Técnicas de responsividade
* Práticando Javascript manipulando - DOM

## Instalação
`npm install -D tailwindcss`
`npx tailwindcss init`

## Configuração tailwind.config.js
```
  module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
  }
```

## Configuração do CSS do tailwind
```
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```

## Rodando o Tailwind CLI build process
`npx tailwindcss -i ./tailwind.css -o ../app.css --watch`

## Adicionando Tailwind no HTML
`<link href="/dist/output.css" rel="stylesheet">`

## Versão mínima para produção
`npx tailwindcss -i tailwind.css -o final.css --minify`