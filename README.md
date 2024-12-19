# Watsonx.ai LLM Demo

Proyek ini menunjukkan bagaimana cara berinteraksi dengan IBM Watsonx.ai Large Language Models (LLMs) menggunakan Watson Machine Learning SDK. Demo ini mencakup dua skrip:

- **`demo_wml_api_wit_sreamlit.py`**: Aplikasi web berbasis Streamlit yang memungkinkan pengguna untuk berinteraksi dengan Watsonx.ai LLM dengan mengajukan pertanyaan dan menerima jawaban yang dihasilkan.
- **`demo_wml_api.py`**: Skrip Python yang mendemonstrasikan pemanggilan LLM menggunakan SDK Watson Machine Learning dan REST API.

## Fitur

- Menghasilkan jawaban untuk berbagai macam pertanyaan menggunakan Watsonx.ai LLM.
- Mengekstraksi faktor keluhan pelanggan berdasarkan prompt yang sudah ditentukan.
- Integrasi REST API untuk memanggil LLM tanpa memerlukan SDK.

## Prasyarat

Sebelum menjalankan proyek ini, pastikan Anda memiliki hal-hal berikut:

- Akun **IBM Cloud**.
- **API Key** dan **Project ID** dari Watsonx.ai.
- Python 3.10 atau 3.11 terpasang.

## Daftar Pustaka Python yang Dibutuhkan

Instal dependensi yang diperlukan dengan menjalankan perintah berikut:
- pip install -r requirements.txt

## Pengaturan

### Buat file .env:
- api_key=YOUR_IBM_API_KEY
- project_id=YOUR_IBM_PROJECT_ID

Gantilah YOUR_IBM_API_KEY dan YOUR_IBM_PROJECT_ID dengan API Key dan Project ID IBM Cloud anda.

### Menjalankan Aplikasi Streamlit:
- streamlit run demo_wml_api_wit_sreamlit.py
### Menjalankan Skrip Python:
- python demo_wml_api.py





