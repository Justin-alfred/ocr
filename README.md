# OCR AI Response Tool
Deskripsi
Aplikasi ini adalah GUI berbasis Python untuk menangkap tangkapan layar (screenshot), melakukan Optical Character Recognition (OCR) menggunakan Tesseract, dan mengirimkan teks yang dikenali ke beberapa API AI untuk mendapatkan respons.

Fitur
Tangkapan layar dan OCR otomatis dengan menekan tombol ENTER.

Dukungan untuk beberapa model AI: Claude Sonnet, GPT-3, Gemini Pro, dan Luminai.

GUI dengan CustomTkinter.

Penyimpanan gambar hasil tangkapan layar dalam folder image.

Tombol untuk membersihkan gambar dan respons.

Persyaratan
Python 3.x

pip (Python package installer)

Tesseract-OCR (Harus diinstal terpisah)

Library Python yang diperlukan (requirements.txt):
nginx
Copy
Edit
Pillow
pynput
pytesseract
requests
customtkinter
Cara Menginstal Library Python
Pastikan Python sudah terpasang di sistem Anda.

Instal library menggunakan perintah berikut:

bash
Copy
Edit
pip install -r requirements.txt
Cara Menginstal Tesseract
Unduh dan instal Tesseract dari tautan berikut:

Tesseract OCR GitHub

Atau unduh dari Tesseract Download Page

Saat menginstal, pastikan untuk mencentang opsi "Add Tesseract to System Path".

Setelah instalasi, atur jalur Tesseract pada script Python:

python
Copy
Edit
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
Jika Anda menggunakan bahasa Indonesia dalam OCR, pastikan untuk mengunduh data bahasa tambahan (ind.traineddata):

Buka folder tessdata di lokasi instalasi Tesseract.

Unduh file ind.traineddata dari Tesseract tessdata GitHub dan tempatkan di folder tersebut.

Cara Menggunakan
Jalankan aplikasi dengan perintah berikut:

bash
Copy
Edit
python <nama_file_script.py>
GUI akan terbuka secara otomatis.

Tekan ENTER untuk mengambil screenshot dan melakukan OCR.

Hasil OCR akan dikirim ke API AI (Claude Sonnet, GPT-3, Gemini Pro, Luminai).

Respons akan ditampilkan di area teks GUI.

Tekan ESC untuk keluar dari aplikasi.

Troubleshooting
Masalah: Tidak ada teks yang terdeteksi dalam tangkapan layar.

Pastikan area tangkapan layar memiliki teks yang jelas.

Periksa konfigurasi Tesseract (pastikan sudah diatur dengan benar).

Masalah: Error saat mengakses API.

Periksa koneksi internet.

Pastikan URL API yang digunakan masih aktif.

Kontak
Jika ada pertanyaan atau masalah, silakan hubungi [your email or contact info].
