# ◈ NEON APEX — Retro Racer

Game balap arcade bergaya synthwave/retrowave yang berjalan langsung di browser. Tidak membutuhkan framework, instalasi, atau server backend.

![NEON APEX banner](assets/neon-apex-pixel-banner.png)

## Fitur
- Opening cinematic animasi setelah tombol **START ENGINE** ditekan (dapat dilewati dengan **SKIP INTRO**).
- Gameplay 3 jalur dengan mobil lalu lintas, skor, kecepatan, dan nitro.
- Rekor terbaik disimpan di browser perangkat menggunakan `localStorage`.
- Kontrol keyboard, sentuh, dan klik pada area game.
- Responsif untuk desktop dan perangkat mobile.

## Cara menjalankan lokal
1. Download atau clone repository ini.
2. Buka `index.html` di browser modern.

## Deploy ke GitHub Pages
1. Buat repository GitHub baru.
2. Upload seluruh isi folder ini, termasuk folder `assets`.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Tunggu proses selesai, kemudian buka URL GitHub Pages yang diberikan.

## Kontrol
- **← / →** atau **A / D**: belok kiri/kanan.
- **SPACE** atau **SHIFT**: nitro.
- **P**: jeda / lanjutkan.
- **R** atau **ENTER**: mulai ulang.
- Pada layar sentuh: gunakan tombol panah dan NITRO.

## Struktur project
```text
neon-apex-github/
├── index.html
├── README.md
└── assets/
    ├── neon-apex-promo.png
    ├── neon-apex-cover.png
    ├── neon-apex-wallpaper.png
    └── neon-apex-pixel-banner.png
```

Made with ❤️ for the midnight highway.
