# Escola de Avatares — site para Vercel

Versão em React + Vite (SPA) da landing page, pronta para subir no GitHub e conectar na Vercel.

## Como colocar no ar

1. Crie um repositório novo no GitHub.
2. Envie **o conteúdo desta pasta** (não a pasta `export` em si).
3. Na Vercel: **Add New → Project** → importe o repositório.
4. A Vercel reconhece o Vite sozinha — só clicar em **Deploy**.

## Rodar localmente

```bash
npm install
npm run dev      # desenvolvimento
npm run build    # geração da pasta dist (o que a Vercel publica)
npm run preview  # abre a versão publicada
```

## O que está incluído

- Página completa (fotos, vídeos dos reels, carrossel da turma, FAQ, garantia).
- Preços em dólar: Starter $19.90, Pro $29.90, oferta de saída $19.80.
- Botões ligados à Hotmart:
  - Starter — https://pay.hotmart.com/L107952254U?checkoutMode=10&bid=1791520207025
  - Pro — https://pay.hotmart.com/M107952299D?checkoutMode=10&bid=1791589412827
  - Oferta $19.80 — https://pay.hotmart.com/P107967395C?bid=1791602093315
- Pop-up de desconto (aparece ao tentar voltar no celular; para testar, acrescente `?oferta=1` ao endereço).
- Rastreamento Utmify (UTM + pixel `6ac7deb84e42a16c45dad0c0`) no `index.html`.
