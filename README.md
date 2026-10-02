# SMK PINTAR RPG — RPL Adventure

Game RPG edukatif berbasis HTML/CSS/JavaScript untuk materi Rekayasa Perangkat Lunak Kelas X, XI, XII.

## Fitur
- Registrasi pemain dan login.
- Pilihan karakter menggunakan karakter dari gambar sprite yang diberikan.
- 53 level; setiap level mempunyai tantangan berbeda.
- Tipe tantangan: pilihan ganda, benar/salah, susun algoritma, debugging, SQL, kode JavaScript, skenario UI/UX, keamanan, testing, Git, API, deployment, dan tantangan profesional.
- XP, HP, score, progress, checkpoint, dan boss setiap 10 level.
- Data pendaftaran dan aktivitas permainan dapat dikirim ke Google Sheets.
- Akun `superadmin` untuk melihat daftar pemain dan aktivitas.
- Responsive untuk PC dan HP.
- Siap di-host pada GitHub Pages.

## Akun demo
- `rplx` / `rpl123`
- `rpli` / `rpl123`
- `rplii` / `rpl123`
- `rpliii` / `rpl123`
- `superadmin` / `admin123`

## Google Sheets
1. Buat Google Sheet.
2. Extensions → Apps Script.
3. Salin `google-apps-script.gs`.
4. Deploy → New deployment → Web app.
5. Execute as: Me.
6. Who has access: Anyone.
7. Salin URL `/exec`.
8. Buka `script.js` dan isi `APP_SCRIPT_URL` dengan URL tersebut.
9. Upload seluruh folder ke GitHub dan aktifkan GitHub Pages.

## Catatan keamanan
Akun demo di `script.js` adalah autentikasi client-side sehingga source code dapat dibaca pengguna. Untuk produksi sekolah, autentikasi sebaiknya dipindahkan ke backend/database dan password di-hash. Google Sheets pada paket ini berfungsi sebagai pencatatan/monitoring, bukan database password produksi.

## Struktur
- index.html
- style.css
- script.js
- google-apps-script.gs
- assets/hero.png
- README.md


## Level 51–53 — Refleksi Siswa
- Level 51: harapan, keinginan, kritik membangun untuk SMK 17 Muncar.
- Level 52: alasan memilih RPL dan keterampilan yang ingin dikembangkan.
- Level 53: ide aplikasi/game/sistem yang ingin dikembangkan serta cita-cita/target setelah lulus.

Jawaban level 51–53 disimpan ke Google Sheets pada kolom `detail` sehingga sekolah dapat membaca aspirasi siswa. Jawaban bersifat refleksi; tidak ada jawaban benar/salah.

Nama game resmi: **RPG SMK PINTAR** — SMK 17 Muncar.
