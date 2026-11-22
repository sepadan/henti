# Sijil Tamat Sekolah Rendah

Halaman depan sistem sijil tamat sekolah, dihoskan di GitHub Pages.

- **Halaman:** https://sepadan.github.io/henti/
- **Data:** kekal dalam Google Sheets sekolah. Repo ini tidak mengandungi data murid.
- **Pelayan:** Apps Script terikat pada Sheet itu, di-deploy sebagai Web App
  (*Execute as: Me*, *Who has access: Anyone*). Semua tindakan memerlukan
  kata laluan web.

## Tetapkan atau tukar kata laluan

Dalam Google Sheets: **Sijil Tamat Sekolah → Tetapkan kata laluan web**.
Menukar kata laluan membatalkan semua sesi yang sedang log masuk.

## Kemas kini kod Apps Script

Selepas menukar kod dalam editor Apps Script, kemas kini deployment yang sama
supaya URL tidak berubah: **Deploy → Manage deployments → (pensel) →
Version: New version → Deploy**. Jika deployment baharu dibuat, tukar
`API_URL` dalam `index.html`.
