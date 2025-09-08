# Install_JupyterLab
# 📘 Panduan Instalasi JupyterLab di Windows

## 1️⃣ Instalasi Python
1. Download Python di [python.org](https://www.python.org/downloads/).
2. Saat instalasi, **centang opsi "Add Python to PATH"**.
3. Cek apakah sudah terpasang dengan benar:
   ```bash
   python --version
## 2️⃣ Cek pip
    pip --version
### Kalau belum ada, jalankan:
    python -m ensurepip --upgrade

# 3️⃣ Buat Virtual Environment (opsional tapi disarankan)
### Agar project lebih rapi, buat virtual environment:
    python -m venv myenv
### Aktifkan environment:
    myenv\Scripts\activate
### Nonaktifkan environment dengan:
    deactivate
# 4️⃣ Install JupyterLab
### Pastikan environment sudah aktif, lalu jalankan:
    pip install jupyterlab
# 5️⃣ Jalankan JupyterLab
      jupyter lab
-Browser akan otomatis terbuka dengan alamat:
👉 http://localhost:8888/lab

