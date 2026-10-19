TAKWIM PINTAR 2027 SK SUNGEI ANTU — PWA CUTI FIX V3

PERUBAHAN UTAMA
- Cuti tambahan kini mengutamakan bacaan melalui Apps Script (listHolidays).
- CSV cuti hanya digunakan sebagai fallback.
- Service Worker / cache PWA dinaik taraf supaya fail lama tidak terus digunakan.
- Semua fungsi PWA, program, ringkasan, cuti rasmi, emolumen dan login admin dikekalkan.

FAIL GITHUB
Upload semua fail berikut ke ROOT repository GitHub:
- index.html
- style.css
- app.js
- manifest.webmanifest
- sw.js
- README_PWA_CUTI_FIX.txt (optional)

APPS SCRIPT
Gunakan fail AppsScript_Takwim_Pintar_2027_SK_Sungei_Antu_CUTI_FIX.gs yang diberikan berasingan.

LANGKAH WAJIB SELEPAS PASTE APPS SCRIPT
1. Save.
2. Run setupTakwimSystem2027() sekali dan benarkan permission.
3. Run resetAdminCredentials2027() sekali.
4. Run testConnection2027(). Ia mesti memulangkan success:true dan menunjukkan tab Program2027 serta Cuti2027.
5. Deploy > Manage deployments > Edit > New version > Deploy.
6. Kekalkan Execute as: Me dan Who has access: Anyone.
7. Jika mengemas kini deployment yang sama, URL /exec tidak berubah.

UJIAN API
Buka URL Web App dengan ?action=listHolidays di hujung.
Contoh:
https://script.google.com/macros/s/AKfycbxqPcuOFway0lr-ePhJq3oELvgbmTUqe1qJIZQvwtmRmKu2axTNN3fGzcIlhsuq8PFE/exec?action=listHolidays

Respons yang betul sekurang-kurangnya:
{"success":true,"holidays":[]...}

LOGIN ADMIN
Username: admin
Password: YBB2206

PWA / CACHE
Versi ini menggunakan cache baharu v3. Selepas GitHub Pages selesai deploy, refresh halaman. Jika app pernah dipasang, tutup dan buka semula PWA sekali supaya Service Worker baharu diaktifkan.
