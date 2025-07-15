# 🎯 Gemini Flash API Project

Hi Gesss, ..
Proyek Node.js ini menggunakan Express untuk membangun REST API yang terintegrasi dengan **Gemini 1.5 Flash** (atau model lain seperti Gemini 2.5 Pro) menggunakan package `@google/generative-ai`. API ini mendukung **permintaan berbasis teks**, **gambar**, dan **audio**, serta menggunakan metode POST untuk menghasilkan konten dari prompt yang diberikan.

---

## 🚀 Fitur Utama

- `POST /generate-text`  
  Menghasilkan teks berdasarkan prompt yang dikirim melalui JSON.

- `POST /generate-from-image`  
  Menghasilkan respons berbasis review dari file gambar yang dikirim melalui form-data.

- `POST /generate-from-document`
  Menghasilkan respons berbasis analisa dan review terkait dokumen yang dikirim melalui form-data.

- `POST /generate-from-audio`  
  Menghasilkan respons berbasis analisis atau transkripsi file audio.

---

## 🔧 Plugin / Package yang Dibutuhkan

Pastikan kamu telah menginstal package berikut dengan `npm install`:

```bash
npm install express dotenv multer fs path @google/generative-ai
