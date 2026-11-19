# SteadySats Trading History

A static dashboard pairing live market quotes with clearly labeled simulated trades and transfers. The blue SteadySats mark is the favicon published on the official website. Current market data comes from public Binance Spot and Kraken endpoints. No API keys, accounts, or database are required to run the site.

## Deploy on Vercel

1. Put `index.html`, `vercel.json`, and `README.md` at the root of the GitHub repository (not inside another folder).
2. In Vercel, select **Add New → Project**, import `leephil1907-lab/steadysatsgenesrs`, and leave **Root Directory** at the repository root.
3. Select **Other** as the framework if prompted, then **Deploy**. There is no build step or environment variable to configure.

The dashboard streams live quotes when possible and also polls public snapshots. Prices with no fresh quote are marked delayed or unavailable, not filled with simulated prices. Account and history records are simulated. Nothing places real trades or moves funds.
