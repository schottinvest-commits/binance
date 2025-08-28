# Binance Proxy (Vercel)

Petit proxy gratuit pour appeler l’API Binance depuis Google Sheets (ou Apps Script) 
sans se faire bloquer par les restrictions régionales.

## Endpoints disponibles

- `/api/binance/price?symbol=BTCUSDT`
- `/api/binance/ticker24?symbol=BTCUSDT`
- `/api/binance/klines?symbol=BTCUSDT&interval=30m&limit=100`

## Déploiement

1. Crée un dépôt GitHub et copie ce projet dedans.
2. Sur https://vercel.com, clique **Add New → Project**.
3. Sélectionne ton dépôt.
4. Deploy 🚀

Ton proxy sera disponible à une URL du type :
`https://ton-projet.vercel.app/api/binance/...`
