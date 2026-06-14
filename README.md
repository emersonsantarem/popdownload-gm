# POP Download GM

Site estático em HTML/CSS para divulgar o POP Download GM, um programa para Windows focado em downloads de jogos PC.

## Páginas do site

- `index.html` – página inicial
- `download.html` – download, requisitos e changelog
- `about.html` – sobre o projeto
- `contact.html` – contato com formulário
- `privacy.html` – política de privacidade
- `terms.html` – termos de uso
- `styles.css` – estilos globais

## Como trocar os links de download

No arquivo `download.html`, substitua `href="#"` nos botões de download pelo link real do instalador (`.exe` ou `.zip`).

Exemplo:
```html
<a class="button button-primary" href="https://seuservidor.com/POP-Download-GM.exe">
