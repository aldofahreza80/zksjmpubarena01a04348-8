# Wallet Intelligence Corpus

Korpus data forensik dompet untuk riset
[Wallet Intelligence Engine v2](https://github.com/aldofahreza80/Wallet-Intelligence-Engine).

Isi = **data on-chain publik** (transaksi Solana mainnet) hasil crawl RPC
standar — bukan data pribadi, tanpa rahasia, tanpa endpoint ber-api-key.

- `*.json` — crawl dompet kasus-3 (funder / ops / anggota / anak pabrik /
  rel / sink), 24 file + 1 laporan token, format kolektor v1.
- `MANIFEST.md` — provenance per-file (sha256 + commit asal).

Konvensi nama: `case3_<peran>_<dompet>.json` (funder / ops / wallet /
parent / child / deep / cosign / genesis / rail / spawn / pocket).

Lisensi data: CC0 1.0 (dedikasi domain publik) — data blockchain publik
didistribusikan ulang untuk riset koordinasi pasar.
