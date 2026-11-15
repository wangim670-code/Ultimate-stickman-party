# 10,000 GAMES – ULTIMATE STICKMAN PARTY (1P–4P Offline Arcade)

Projek lengkap aplikasi parti arked 1–4 pemain dengan 68 permainan mini boleh dimainkan secara offline, mod Landscape Android, 20 karakter Stickman, 16 senjata, 10 pet beranimasi, kedai, ganjaran harian, roda bertuah, pencapaian, dan sistem tahap Level 1–100.

## Keperluan Sistem
- Node.js 18+ (disyorkan Node 20/22)
- npm 9+

## Cara Pasang & Bina Projek

```bash
# 1. Pasang semua pakej
npm install

# 2. Jalankan pelayan pembangunan (dev server)
npm run dev

# 3. Bina versi produksi (dist/)
npm run build

# 4. Pratonton binaan produksi
npm run preview
```

## Kandungan Utama Projek
- `index.html` — Titik masuk HTML & metadata PWA
- `src/` — Kod sumber React, TypeScript, CSS Tailwind & semua 19 enjin permainan (68 permainan mini)
- `public/` — Ikon PNG/SVG, `manifest.json`, dan `service-worker.js`
- `package.json`, `tsconfig.json`, `vite.config.ts` — Konfigurasi binaan Vite & PWA
