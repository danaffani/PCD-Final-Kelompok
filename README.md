# PCD Group 3 Final Project

## Instalasi (Installation)

### Persyaratan (Requirements)
- Python 3.10.0 (harus versi ini, terjamin bisa)
- pip (Python package manager)

### Langkah-langkah Instalasi (Installation Steps)

1. Pastikan Python 3.10.0 sudah installed di local computer
   ```bash
   python --version
   ```

2. Buat virtual environment menggunakan Python 3.10.0 melalui GUI dari VSCode dan aktifkan melalui Terminal VSCode
   ```bash
   .venv/Scripts/activate
   ```

3. Pastikan virtual environment sudah aktif (tanda (venv) akan muncul di terminal)

4. Install dependencies dari requirements.txt
   ```bash
   pip install -r requirements.txt
   ```

## Penggunaan (Usage)

Setelah instalasi selesai, jalankan program sesuai dengan instruksi yang diberikan pada markdown. Testing saat ini hanya bisa dilakukan menggunakan file bernama "test*.jpg" yang berada di root, apstikan file tersebut sudah ada ketika ingin menjalankan testing.

## Troubleshooting

Jika ada masalah saat instalasi, pastikan:

1. Python 3.10.0 terinstall dengan benar
2. Virtual environment sudah aktif
3. Semua dependencies terinstal dengan benar

4. Jika muncul error "cannot be loaded because running scripts is disabled on this system" saat mengaktifkan virtual environment di PowerShell:
   - Buka PowerShell sebagai Administrator
   - Jalankan perintah: `Set-ExecutionPolicy RemoteSigned`
   - Ketik "A" dan tekan Enter untuk "Yes to All"
   - Coba aktifkan virtual environment kembali