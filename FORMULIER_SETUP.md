# Qrossborder — formulier activeren

1. Maak bij Web3Forms een nieuwe access key voor qontact@qrossborder.com en bevestig de verificatie-e-mail.
2. In Railway > de website-service > Variables: voeg VITE_WEB3FORMS_ACCESS_KEY toe met de nieuwe key als waarde. Zet de key niet in GitHub.
3. Start een nieuwe build/deployment (Vite leest VITE_ variabelen tijdens de build).
4. Test op het uiteindelijke domein zowel een klantaanvraag als een kandidaat-aanmelding. Controleer daadwerkelijke ontvangst en Reply-To.
5. Let op: de eerdere melding 'Form submissions from this domain TLD is blocked' kan op *.railway.app blijven optreden. Een nieuwe key lost een domeinblokkade niet automatisch op; neem zo nodig contact op met Web3Forms support.
6. Koppel het productiedomein pas aan de nieuwe code nadat de deployment gezond is.

Let op: VITE_ waarden zijn publiek zichtbaar in de browserbundle. Een Web3Forms access key is ontworpen voor gebruik in frontend-formulieren; gebruik hiervoor geen geheime API-sleutel.

Hetzelfde formulier staat op Home en Werken bij. Op Werken bij is kandidaat standaard geselecteerd. Bedrijfsnaam is alleen voor klanten verplicht.
