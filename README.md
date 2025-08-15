# WA Chat Viewer (Client‑side)
Drag & drop file export WhatsApp (`_chat.txt`, tanpa media) → tampil seperti chat, bisa search & jump date. Jalan full di browser, aman (nggak upload ke server).

## Cara pakai (GitHub Pages)
1. Upload `index.html` ini ke repo GitHub kamu (root).
2. Aktifkan GitHub Pages: Settings → Pages → Deploy from a branch (main /root).
3. Buka URL Pages repo kamu → drag & drop `_chat.txt`.

## Format yang didukung
- `DD/MM/YYYY, HH:MM - Nama: Pesan`
- `[DD/MM/YY, HH:MM] Nama: Pesan`
- `DD/MM/YYYY, HH.MM - Nama: Pesan`
- `[DD/MM/YY, HH.MM.SS] Nama: Pesan` (pakai detik)
- `DD/MM/YYYY, HH.MM.SS - Nama: Pesan`

## Catatan
- Token seperti `sticker/image/video/audio omitted` akan ditampilkan sebagai ikon.
- Baris `Location: https://maps.google.com/?...` jadi tautan 📍 yang bisa diklik.
