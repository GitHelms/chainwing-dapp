# 🚁 ChainWing – Drohnen. Energie. Zukunft.

![Lizenz: MIT](https://img.shields.io/badge/license-MIT-green.svg)
![Technologie: Solana](https://img.shields.io/badge/Technologie-Solana-blueviolet)
![Status: Aktiv](https://img.shields.io/badge/status-pilotphase-success)

> ChainWing ist ein technologiegestützter Drohnendienstleister mit Fokus auf Thermografie, Inspektion und zukunftsorientierter Energieplanung.  
> Unser Ziel: Bereits heute verlässlich arbeiten – und gleichzeitig den Weg ebnen für die dezentrale Koordination von Drohneneinsätzen.

---

## 🌍 Was wir heute tun

ChainWing führt mit zertifizierten Piloten und geprüfter Technik hochwertige Drohneneinsätze durch.  
Dazu gehören unter anderem:

- 🔍 Thermografie von Photovoltaikanlagen
- 🏗️ Umsetzung von Photovoltaikanlagen
- 📸 Dokumentation bei Bauprojekten
- 🛰️ Erste Tests für automatisierte Erkennung & Bewertung (KI)

Alle Einsätze werden derzeit **zentral verwaltet** und **manuell geplant**.  
Piloten werden persönlich ausgewählt und geprüft. Wir tragen die volle Verantwortung für Qualität und Rechtssicherheit.

---

## 🔮 Was wir vorbereiten

Parallel zum operativen Geschäft bauen wir eine technologische Plattform auf, die:

- 💼 Pilotenprofile mit verifizierten Daten führt (A1/A3, STS, Versicherung)
- 🧾 Zertifikate optional in Form von **NFTs** speichert
- 💰 Tokenisierte Belohnungen über den **ChainWing Token (CWT)** ermöglicht
- 🧠 Smarte Auftragslogik über Wallet-Login und Smart Contracts abbildet
- 🛰️ Perspektivisch DePIN-fähige Drohnentürme mit Lade- & Startlogik integrieren kann

**Die Infrastruktur steht bereit – der Markt ist es noch nicht.**

---

## 🧱 Technologie

| Ebene         | Technologie                             |
|---------------|------------------------------------------|
| Frontend      | Next.js, Tailwind CSS                    |
| Wallet-Login  | Solana Wallet Adapter                    |
| Backend       | Supabase (PostgreSQL, Auth, Edge)        |
| Blockchain    | Solana, Anchor, Metaplex NFTs            |
| Automatisierung | GitHub Actions, Cloudflare Pages      |

---

## ⚙️ Lokales Setup

```bash
# 1. Repository klonen
git clone https://github.com/deinname/chainwing-dapp.git
cd chainwing-dapp

# 2. Frontend starten
cd frontend
pnpm install
pnpm dev

