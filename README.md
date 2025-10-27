# Hands-on Komdigi: Modul 3 - Implementasi Dasar LLM

Selamat datang di *repository hands-on* untuk **Modul 3 ("PyTorch dan HuggingFace pada LLM")** dari program AI Engineer Komdigi!

**Tujuan:**
Repository ini berisi *notebook* Jupyter interaktif (`2_Pipeline_Inference_Dasar.ipynb`) yang dirancang untuk membantu Anda **mempraktikkan** alur kerja implementasi dasar dari Modul 3:
* **Memuat Model & Tokenizer:** Menggunakan `AutoClass` (`AutoModel`, `AutoTokenizer`) dari Hugging Face.
* **Menyiapkan Device:** Bekerja dengan PyTorch Tensor dan memindahkannya ke CPU/GPU (`.to(device)`).
* **Preprocessing Input:** Menerapkan *padding* dan *truncation* saat tokenisasi.
* **Inference Dasar:** Menjalankan model (`AutoModel` dasar) untuk mendapatkan output internal (`last_hidden_state`).

**Prasyarat:**
* Pemahaman dasar bahasa pemrograman Python.
* Akses ke materi Modul 3.
* *(Sangat disarankan)* Telah mencoba *hands-on* Modul 2.

---

## Cara Menjalankan Notebook (`2_Pipeline_Inference_Dasar.ipynb`)

Anda bisa menjalankan *notebook* ini menggunakan salah satu cara berikut:

### Opsi A: Google Colaboratory (Rekomendasi Cepat)

Klik *badge* di bawah untuk membuka *notebook* langsung di Google Colab.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](<https://colab.research.google.com/drive/1vPlORclIxg3iQgY1ULrDB1fzyzT64knF?usp=sharing>)

**Catatan Colab:**
* Jalankan sel pertama yang berisi `!pip install transformers torch` untuk instalasi.
* Pilih *Runtime* GPU (`Runtime > Change runtime type > GPU`) untuk melihat `device` berubah menjadi 'cuda'.

---

## Kaitan dengan Unjuk Kerja Modul 3

**Penting:** *Notebook hands-on* ini dirancang sebagai **latihan interaktif** untuk memahami langkah-langkah implementasi dasar yang akan Anda perlukan untuk **Unjuk Kerja Modul 3**.

* Unjuk Kerja Modul 3 meminta Anda untuk membuat **script Python (`.py`)** yang terstruktur di dalam folder `src/` dan mengunggahnya ke **repository GitHub**.
* *Notebook* ini membantu Anda **memahami setiap langkah** (load, tokenize, inference, cek output) dalam lingkungan yang lebih mudah dieksplorasi **sebelum** Anda menyusunnya menjadi *script* `.py` yang formal untuk Unjuk Kerja.
* Gunakan *notebook* ini untuk bereksperimen dan memastikan Anda paham cara kerja kodenya, kemudian **adaptasi** logika tersebut ke dalam format *script* `.py` sesuai instruksi Unjuk Kerja.

Selamat berlatih implementasi dasar LLM!
