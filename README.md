# Calcimei — Kalkulator Bayar IMEI
> by Dino Studio · Samuel Lana

## File yang ada di folder ini

| File | Fungsi |
|------|--------|
| `calcimei.html` | File utama aplikasi |
| `manifest.json` | Config PWA (biar bisa diinstall) |
| `sw.js` | Service Worker (offline support) |
| `icon-192.png` | Icon app ukuran 192px *(buat sendiri)* |
| `icon-512.png` | Icon app ukuran 512px *(buat sendiri)* |

---

## Cara Deploy ke Vercel (Gratis)

### 1. Upload ke GitHub
- Buat repo baru di github.com
- Upload semua file di folder ini

### 2. Connect ke Vercel
- Buka vercel.com → New Project
- Import repo GitHub tadi
- Klik Deploy — selesai!

### 3. Custom Domain (opsional)
- Di Vercel → Settings → Domains
- Tambah domain kamu sendiri

---

## Cara Jadiin PWA (Install di HP)

Setelah deploy, buka web di Chrome/Safari HP → akan muncul prompt "Install App".

Atau manual:
- Chrome: menu ⋮ → "Add to Home Screen"  
- Safari iOS: Share → "Add to Home Screen"

---

## Icon App

Buat 2 file icon:
- `icon-192.png` — 192×192 px
- `icon-512.png` — 512×512 px

Bisa buat di Canva, Figma, atau tools lain.
Pastikan background tidak transparan (maskable icon).

---

## Update Kalkulator

Edit langsung di `calcimei.html` bagian fungsi `hitung()`.
Setelah edit → push ke GitHub → Vercel otomatis redeploy!

---

*Calcimei — Dino Studio 2026*
