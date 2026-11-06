# BB Musicall – O Gigante e o Anão

Site de lançamento do livro **O Gigante e o Anão – A Canção da Amizade** (organizado por Patrícia Sales Neri de Andrade e Amauri Rodrigo de Andrade), com pedidos do livro e do kit pelo WhatsApp.

## Trocar o QR Code da música
1. Substitua o arquivo `qr-musica.png` pelo QR Code correto (mesmo nome).
2. No fim do `index.html`, troque o link do botão "Ouvir a música":

```js
const MUSICA_URL = "https://www.instagram.com/tv/B9-KfXlAW2y/?vrfl=NTJpdWhpN3o0Mmxs";
```

## Trocar o número do WhatsApp
No fim do `index.html`, altere `const WHATSAPP = "5511968657212";` (DDI + DDD + número) e o número exibido em `<code id="numero">`.
