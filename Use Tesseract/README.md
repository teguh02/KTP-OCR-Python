# Ekstraksi KTP menggunakan Tesseract OCR
Selamat datang di repositori ini! Di sini Anda akan menemukan sebuah proyek Python yang bertujuan untuk melakukan ekstraksi data pada Kartu Tanda Penduduk (KTP) menggunakan teknologi Optical Character Recognition (OCR). Proyek ini memanfaatkan pustaka Tesseract OCR, Pytesseract, dan OpenCV-Python untuk melakukan proses pengenalan teks pada gambar KTP.

# Cara Kerja
Proyek ini bekerja dengan cara mengambil gambar KTP sebagai input, kemudian melakukan pre-processing menggunakan OpenCV untuk meningkatkan kualitas gambar dan mengidentifikasi region of interest (ROI) yang berisi informasi KTP. Setelah itu, menggunakan Tesseract OCR, proyek akan mengekstraksi teks dari ROI tersebut dan menghasilkan data-data seperti nama, nomor KTP, alamat, dan lainnya. Sebagai tambahannya dapat dilihat dalam flow diagram berikut

![KTP OCR Flow Diagram drawio](https://github.com/teguh02/KTP-OCR-Python-Projects/assets/43981051/aacfbea0-b937-4980-8dfe-45409c18593d)

# Persyaratan
- Python 3.x
- Tesseract OCR (instalasi dan konfigurasi yang tepat diperlukan)
- Pytesseract
- OpenCV-Python
- imutils

# Cara Penggunaan
Cara penggunaan telah dijelaskan secara detail pada file ipynb yang telah disediakan

# Kontribusi
Kontribusi terhadap proyek ini sangat dipersilakan! Jika Anda memiliki saran, perbaikan bug, atau peningkatan fitur, silakan buat pull request dan kami akan senang menerima kontribusi Anda. Kami memiliki rencana untuk proyek ini sebagai berikut
- Terus meningkatkan hasil akurasi teks setelah proses OCR (Done, silahkan cek folder Use EasyOCR)
- Membuat API menggunakan flask sehingga siapapun yang ingin membuat projek ekstraksi KTP cukup hanya pull ke server mereka saja, dan menjalankan flask tersebut (Implementasi API dilakukan pada projek dengan easyocr yang hasilnya lebih akurat)

# Catatan!
Proyek ini masih dalam tahap pengembangan awal, sehingga mungkin terdapat beberapa keterbatasan atau bug. Kami akan berusaha untuk memperbaikinya secepat mungkin. Jika Anda menemukan masalah, jangan ragu untuk membuka issue.

Terima kasih telah menggunakan proyek ini!
