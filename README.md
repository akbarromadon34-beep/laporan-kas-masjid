# laporan-kas-masjid


1) Siapkan Google Sheet dari Excel

Upload Excel ke Google Drive

Klik kanan file Excel → Open with → Google Sheets

(Opsional tapi disarankan) File → Save as Google Sheets

Buat tab (nama sheet) misalnya: Transaksi

Baris 1 wajib header seperti ini (A–E):

Tanggal | Tipe | Kategori | Keterangan | Jumlah


2) Buat “API” di Google Apps Script (tanpa Cloud Console)

Di Google Sheets: Extensions → Apps Script (file diupdate)


3) Deploy Apps Script jadi Web App

Klik Deploy → New deployment

Pilih Select type: Web app

Execute as: Me

Who has access: Anyone

Klik Deploy, izinkan permission

Copy Web app URL (contoh: https://script.google.com/macros/s/XXXXX/exec)



4) Website GitHub Pages (index.html) – versi lengkap

Buat index.html di repo GitHub Pages kamu, isi ini.

Ganti WEB_APP_URL dengan URL web app kamu. (index.html download saja)




