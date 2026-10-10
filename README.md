# Escola de Avatares — landing page (Vercel-ready)

Static React + Vite + Tailwind v4 site. No backend needed.

## Put it online (GitHub + Vercel)

1. Unzip this file. You will see an `export` folder.
2. Upload **the contents of the `export` folder** (not the folder itself) to a new GitHub repository.
3. In Vercel: "Add New..." → Project → import that repository → click **Deploy**. No settings to change.
4. After it deploys, Vercel shows your live URL.

You can also run it locally: `npm install`, then `npm run dev`.

## Payment links (already wired in the buttons)

- Starter $19.90 → https://pay.hotmart.com/L107952254U?checkoutMode=10&bid=1791520207025
- Pro $29.90 → https://pay.hotmart.com/M107952299D?checkoutMode=10&bid=1791589412827
- Exit offer $19.80 → https://pay.hotmart.com/P107967395C?bid=1791602093315

## Notes

- Utmify tracking (pixel 6ac7deb84e42a16c45dad0c0 + UTM scripts) is loaded on every page; the UTM script appends your ad UTM params to the checkout links.
- This export is a snapshot of the site. Changes made later in Lovable need a new export.
- The mobile discount pop-up appears when the user presses the browser back button (once per visit). You can preview it by adding `?oferta=1` to the URL.
