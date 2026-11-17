# Make it seamlessly – losse site voor GitHub Pages

## Online zetten
1. Maak op github.com een nieuwe repository, bijvoorbeeld `make-it-seamlessly` (Public).
2. Kies **uploading an existing file** en sleep de **inhoud** van deze map erin
   (index.html, fotos, img, stem, assets, lib, mediapipe en .nojekyll). Klik **Commit changes**.
   Lukt het slepen van mappen niet in je browser, gebruik dan GitHub Desktop.
3. Ga naar **Settings → Pages**. Kies bij *Branch* `main` en map `/ (root)` en klik **Save**.
4. Na een minuut staat je site op `https://<jouw-gebruikersnaam>.github.io/make-it-seamlessly/`.

## Testen
- Open de site op de computer (Chrome werkt het best): je ziet Élodie met de QR-code.
- Scan de QR-code met je telefoon. Bovenaan staat "Verbonden" zodra telefoon en scherm elkaar vinden.
- Tik op **Begin**, dan op de microfoon, en vertel wat je zoekt. De resultaten verschijnen op het scherm.
- Bij het opmeten vraagt de browser toestemming voor de webcam: dan sta je live voor de spiegel.

## Goed om te weten
- De telefoon en het scherm vinden elkaar via PeerJS (gratis, via internet). Beide toestellen hebben internet nodig.
- Praten werkt in Chrome op Android en in Safari op iPhone (iOS 14.5 of nieuwer). Geef toestemming voor de microfoon.
- Zonder Claude zoekt Élodie op trefwoorden (jas, kant, knopen, strepen, kleuren…).
  Stukken zonder uitgewerkt patroon krijgen een vereenvoudigd basispatroon.
- De lichaamsherkenning haalt het model op bij Google (storage.googleapis.com) de eerste keer dat je de camera start.
