# Ana Vicente - Site institucional

Site estático para publicação no Netlify, com formulário capturado pelo Netlify Forms e botão opcional para abrir conversa no WhatsApp.

## Publicar no Netlify

1. Suba este repositório no GitHub.
2. No Netlify, clique em **Add new site** e depois **Import an existing project**.
3. Escolha o GitHub e selecione este repositório.
4. Em **Build settings**, deixe:
   - Build command: vazio
   - Publish directory: `.`
5. Publique o site.

## Ver contatos do formulário

Depois do primeiro deploy, o Netlify detecta o formulário `contato` automaticamente. Os envios aparecem em **Site configuration > Forms** ou na aba **Forms** do site.

## Conectar WhatsApp

O WhatsApp usa links no formato `https://wa.me/55DDDNUMERO?text=mensagem`. O número atual configurado é `5547996714706`.

Para trocar o número, altere estas ocorrências em `index.html` e `obrigado.html`:

```txt
5547996714706
```

Use sempre o formato internacional, sem espaços, parênteses ou traços: `55` + DDD + número.
