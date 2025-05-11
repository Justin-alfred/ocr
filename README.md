# OCR AI Response Tool
# Deskripsi
Aplikasi ini adalah GUI berbasis Python untuk menangkap tangkapan layar (screenshot), melakukan Optical Character Recognition (OCR) menggunakan Tesseract, dan mengirimkan teks yang dikenali ke beberapa API AI untuk mendapatkan respons.

# Fitur
Tangkapan layar dan OCR otomatis dengan menekan tombol ENTER.
Dukungan untuk beberapa model AI: Claude Sonnet, GPT-3, Gemini Pro, dan Luminai.
GUI dengan CustomTkinter.
Penyimpanan gambar hasil tangkapan layar dalam folder image.
Tombol untuk membersihkan gambar dan respons.

# Instalasi
- Python 3.x
- pip install -r requirements.txt
- install tesseract di https://github.com/tesseract-ocr/tesseract

# Cara Menggunakan
- python app.py
  > Tunggu sampai GUI terbuka
- Command
  > `ENTER` untuk mengambil screenshot dan melakukan OCR.
    > Hasil OCR akan dikirim ke API AI (Claude Sonnet, GPT-3, Gemini Pro, Luminai).
    > Respons akan ditampilkan di area teks GUI.
