# D&D Braids Beauty — V9 Final

Versão final do frontend estático.

## Arquivos
- `index.html` — interface
- `styles.css` — estilos
- `app.js` — **todo o JavaScript do sistema em um único arquivo**

## GitHub Pages
Esta build não usa imports ES Modules entre arquivos. O `index.html` carrega apenas `app.js` com `defer`, tornando a publicação estática mais simples.

A inicialização também não depende mais de uma chave `*_initialized`: ela verifica diretamente se o estado `ddbraids_v9_clean` existe. Se não existir, carrega os dados de demonstração uma única vez.

Login demo: `admin@ddbraids.com` / `1234`
