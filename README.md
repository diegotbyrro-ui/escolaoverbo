# Escola O Verbo

Site institucional da Escola O Verbo, em Maceió. Fotos ilustrativas de crianças, foto real de drone e depoimentos das mães.

## Publicação

Site estático, sem instalação nem compilação. Pasta de publicação: `dist`. Em hospedagem tradicional, enviar o conteúdo dessa pasta para a raiz do domínio.

- Vercel: importar o repositório; configuração estática incluída.
- Netlify: importar o repositório; publicação definida em `netlify.toml`.
- Outro provedor: pasta de saída `dist`; sem comando de build.

## Prévia local

Execute `python -m http.server 8080 --directory dist` e abra http://localhost:8080.

## Edição

Textos e estrutura das quatro páginas em `build.py`. Execute `python build.py` depois de editar (Python 3, sem dependências). CSS e JavaScript em `dist/style.css` e `dist/app.js`.

## Contato e mídias

O formulário prepara um e-mail para a secretaria; o visitante revisa e confirma o envio no aplicativo. Imagens de crianças são ilustrativas, criadas por IA. A foto de drone é real. Os vídeos mantêm os depoimentos originais das mães, com cenas de crianças reais substituídas por imagens ilustrativas.
