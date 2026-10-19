TAKWIM PINTAR 2027 - SK SUNGEI ANTU (PWA)

FAIL UNTUK GITHUB:
- index.html
- style.css
- app.js
- manifest.webmanifest
- sw.js

LENCANA / IKON PWA:
https://iili.io/nwPkxu1.md.png

LOGIN ADMIN BAHARU:
Username: admin
Password: YBB2206

PENTING - LOGIN ADMIN:
1. Buka fail AppsScript_Takwim_Pintar_2027_SK_Sungei_Antu_ADMIN_FIX.gs.
2. Gantikan Code.gs dalam projek Apps Script dengan fail tersebut.
3. Save.
4. Jalankan setupTakwimSystem2027() ATAU resetAdminCredentials2027() sekali.
   (Kod juga mempunyai migrasi automatik credential pada login pertama.)
5. Deploy > Manage deployments > Edit > New version > Deploy.
6. Kekalkan Execute as: Me dan Who has access: Anyone.
7. Jika mengemas kini deployment yang sama, URL /exec kekal dan app.js tidak perlu diubah.

PWA:
- Deploy melalui GitHub Pages (HTTPS diperlukan untuk Service Worker/PWA).
- Selepas site dibuka, browser/peranti yang menyokong PWA akan membenarkan pemasangan aplikasi.
- Manifest dan Service Worker menggunakan path relatif supaya sesuai dengan GitHub Pages repository path.
