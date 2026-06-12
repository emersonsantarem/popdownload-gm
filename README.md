# POP Download GM

Site estatico em HTML e CSS para divulgar o POP Download GM, um programa para Windows focado em downloads de jogos para PC.

## Paginas do site

- `index.html`: pagina principal.
- `download.html`: pagina de download, requisitos e changelog.
- `styles.css`: visual do site inteiro.

## Como trocar o link de download

No arquivo `download.html`, procure por `href="#"` nos botoes de download e troque o `#` pelo link real do instalador do Windows.

Exemplo:

```html
<a class="button button-primary" href="https://seu-link.com/POP-Download-GM.exe">
```

## Hospedagem gratis recomendada

### Opcao 1: GitHub Pages

1. Crie uma conta no GitHub.
2. Crie um repositorio novo.
3. Envie os arquivos `index.html`, `styles.css` e `README.md`.
4. Abra `Settings`, depois `Pages`.
5. Em `Branch`, escolha `main` e a pasta `/root`.
6. Salve e aguarde o GitHub gerar o link.

### Opcao 2: Netlify

1. Acesse https://www.netlify.com/.
2. Crie uma conta gratis.
3. Arraste a pasta do site para a area de deploy.
4. O Netlify gera um link publico na hora.

GitHub Pages e otimo para manter o projeto salvo. Netlify costuma ser mais facil para publicar rapidamente.
