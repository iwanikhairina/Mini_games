# 🧩 Puzzle Siska

## Struktur Folder

```
puzzle_siska/
├── index.html          ← File utama game (buka ini di browser)
├── images/
│   ├── siska1.png      ← Foto untuk level Easy   (6 potongan, 2×3)
│   ├── siska2.png      ← Foto untuk level Medium (12 potongan, 4×3)
│   └── siska3.png      ← Foto untuk level Hard   (30 potongan, 6×5)
├── music/
│   ├── background.mp3  ← File musik latar (isi sendiri)
│   └── background.ogg  ← Alternatif format OGG (opsional)
└── README.md           ← Panduan ini
```

## Cara Menggunakan

1. **Buka** `index.html` di browser (Chrome / Firefox / Safari)
2. **Ganti foto** — cukup ganti file di folder `images/` dengan nama yang sama:
   - `siska1.png` → foto untuk level Easy
   - `siska2.png` → foto untuk level Medium
   - `siska3.png` → foto untuk level Hard
3. **Tambah musik** — taruh file musik di folder `music/` dengan nama `background.mp3`
   - Bisa pakai format MP3 atau OGG
   - Klik tombol 🔇 di game untuk menyalakan musik

## Level

| Level  | Potongan | Grid  | Foto     |
|--------|----------|-------|----------|
| Easy   | 6        | 2 × 3 | siska1.png |
| Medium | 12       | 4 × 3 | siska2.png |
| Hard   | 30       | 6 × 5 | siska3.png |

## Catatan

- Format foto yang didukung: PNG, JPG, JPEG, WEBP
- Ukuran foto bebas, akan otomatis disesuaikan
- Game responsif untuk HP dan komputer
- Untuk ganti nama file foto, edit bagian `LEVELS` di dalam `index.html`
