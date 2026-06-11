# PFF-Folio — Family Investment Portfolio Dashboard

**Privacy-first. Locally-run. No cloud. No login.**

PFF-Folio is a desktop investment portfolio dashboard that consolidates your holdings across multiple brokers into one view — net worth, P&L, diversification, fees, and tax reporting, all computed on your device.

Your broker files never leave your machine.

---

## What it does

- **Unified portfolio view** — import data from IBKR, Nordnet, eToro, Zerodha, DEGIRO, Trading 212, Avanza, Trade Republic, and Equalplus/Computershare. Add bank savings, real estate, and pension manually.
- **Net worth tracking** — total value, unrealised P&L, CAGR, XIRR, and invested capital — across all brokers and currencies (EUR, USD, GBP, SEK, INR).
- **Diversification analysis** — broker allocation, sector allocation, and asset-category donuts across 13 categories.
- **Investment journey** — portfolio value chart over time with milestone tracking (€1K → €1M invested and portfolio value).
- **End-of-day prices** — fetched automatically from Yahoo Finance after import for Nordnet, eToro, DEGIRO, and manual holdings. IBKR uses its own authoritative MarkPrice.
- **Multi-member family portfolio** — track up to 6 family members in one dashboard. Nordnet multi-account CSVs are auto-split by account number.
- **Finnish Vero tax report** — Form 9A capital gains table + VSY09A flat file for ilmoitin.fi submission, including CFD handling and hankintameno-olettama (deemed acquisition cost).
- **Manual transaction entry** — add BUY, SELL, DIVIDEND, DEPOSIT, WITHDRAWAL, and FEE transactions manually with full edit and delete.
- **IBKR Flex Query auto-sync** — pull the latest IBKR data automatically without downloading a CSV.
- **Notes** — research notes with tags and priority. High-priority notes appear on the Overview page.
- **Privacy mode** — one click blurs all monetary values across every tab. Resets on reload.
- **PIN lock** — optional AES-256-GCM encryption of all portfolio data at rest in local storage.
- **Backup & restore** — export your full portfolio as a JSON backup and restore it on any device.
- **7-day free trial** — no key needed to start.

---

## How to install

Download the file for your platform from the [Releases](https://github.com/senthil-prabu/pff-folio-releases/releases) page:

| Platform | Download | How to install |
|----------|----------|----------------|
| **Windows** | `PFF-Folio-Setup.exe` | Run the installer — the app launches automatically when it finishes |
| **macOS (Apple Silicon)** | `PFF-Folio-mac-apple.dmg` | Open the DMG → drag PFF-Folio to Applications → launch from Applications |
| **macOS (Intel)** | `PFF-Folio-mac-intel.dmg` | Open the DMG → drag PFF-Folio to Applications → launch from Applications |
| **Linux / advanced** | `pff-folio.zip` | Unzip → `chmod +x PFF-Folio-linux` → run `./start-linux.sh` |

The app opens automatically in its own window — no browser tab to open and no address to type.

No Node.js, npm, or any other software required — the app is fully self-contained.

---

## System requirements

| | |
|--|--|
| **OS** | Windows 7+, macOS 10.12+, Linux |
| **Browser** | Chrome or Edge (recommended) · Safari · Firefox |
| **Internet** | Required for price fetching and license activation; not required for daily use |
| **Storage** | ~100 MB for the binary; portfolio data stored locally in the browser |

---

## License

PFF-Folio includes a **7-day free trial** — no key needed to get started.

After the trial, purchase a license to continue: **[pff-folio.vercel.app](https://pff-folio.vercel.app)**

Your portfolio data is preserved through the trial and after activation.

---

## Privacy

- All broker files are parsed locally — nothing is sent to any server
- Live price fetching contacts Yahoo Finance with ticker symbols only — no account data transmitted
- With PIN lock enabled, all data is AES-256-GCM encrypted in local storage

---

## More information

Full documentation and user guide: **[pff-folio.vercel.app](https://pff-folio.vercel.app)**
