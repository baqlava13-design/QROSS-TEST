# Qrossborder — schone website

Drie pagina's: `/`, `/expertise/`, `/werken-bij/`. Contact is een anker naar `/#contact`.

## Installatie en build

```bash
npm install
npm run build
npm run dev
```

Railway: Build command `npm run build`. Voor een statische Vite-site: start command `npx vite preview --host 0.0.0.0 --port $PORT` (of gebruik een statische hostinginstelling). De Web3Forms-key is overgenomen uit de bestaande broncode. Test de formulieren na publicatie.

## Afbeeldingen

De oorspronkelijke `homepage.webp` (705×480 px) is hergebruikt om de bestaande uitstraling te bewaren. Dit is **geen** nieuw high-resolution bronbestand. Vervang `public/images/homepage.webp` door een scherp origineel (bij voorkeur 1600px breed of groter) voordat je definitief publiceert. Alle drie de hero's gebruiken momenteel diezelfde afbeelding; je kunt per pagina een andere bron toevoegen.

## Veilig publiceren

Maak eerst een back-up. Upload de inhoud van deze ZIP naar de **bestaande** GitHub-repository; verwijder de repository of Railway-service niet. Controleer de build, alle drie routes en beide formulieren.
