# Hands-on Komdigi: Modul 3 - Kontrol Perilaku dan Multimodal

Selamat datang di *repository hands-on* untuk **Modul 3 ("Arsitektur LLM Modern, Sampling, dan Evolusinya")** dari program AI Engineer Komdigi!

**Tujuan:**
Repository ini berisi *notebook* Jupyter interaktif (`Modul_3_Sampling_dan_Multimodal.ipynb`) yang dirancang untuk membantu Anda **bereksperimen** dengan konsep-konsep kunci dari Modul 3:

* **Proses Sampling (Teori 3.2):** Menggunakan model Decoder-Only (GPT-2) untuk melihat bagaimana parameter `temperature`, `top_k`, dan `top_p` secara drastis mengubah *output* teks yang dihasilkan.
* **Multimodal (Teori 3.3):** Menggunakan *pipeline* VLM (Vision Language Model) untuk menjembatani gambar dan teks (membuat deskripsi gambar otomatis).

**Prasyarat:**
* Pemahaman dasar bahasa pemrograman Python.
* Akses ke materi Modul 3 (terutama Subtopik 3.2 dan 3.3).
* Notebook dari Modul 2 (memahami Tokenizer).

---

## Cara Menjalankan Notebook (`Modul_3_Sampling_dan_Multimodal.ipynb`)

Anda bisa menjalankan *notebook* ini menggunakan salah satu cara berikut:

### Google Colaboratory (Rekomendasi Cepat)

Klik *badge* di bawah untuk membuka *notebook* langsung di Google Colab (tidak perlu instalasi lokal).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uVqt7nABNuf4g--xpc1eBsyyNo0uPLCE?usp=sharing)

*(Catatan: Anda harus mengunggah file `.ipynb` ini ke Google Drive Anda sendiri untuk mendapatkan link Colab).*

**Catatan Colab:**
* Jalankan sel pertama yang berisi `!pip install transformers torch pillow requests` untuk menginstal *library* yang dibutuhkan.
* Untuk bagian Multimodal, *runtime* standar (CPU) sudah cukup.

---

Selamat bereksperimen dengan kontrol perilaku LLM!
