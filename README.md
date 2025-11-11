# Chatbot dengan Google Generative AI

## Cara menjalankan kode

Untuk menginstal dan menjalankan kode, berikut petunjuknya:

1. Unduh folder (zip atau github)

2. Masuk ke direktori chatbot genai:

```(CMD)
cd "chatbot-di-console-with-Google-Generative-AI"
```

3. Buat lingkungan virtual (contoh namanya adalah 'venv'):

```
python -m venv venv
```

4. Aktifkan lingkungan virtual baru:
```
venv\Scripts\activate.bat
```

5. Instal paket yang diperlukan (perintah upgrade pip terlebih dahulu):

```
python -m pip install --upgrade pip
python.exe -m pip install -r requirements.txt
```

6. Dapatkan Kunci API GOOGLE Anda

7. Buka file `Chatbot menggunakan generative ai(Tanpa kunci API).py` di root direktori repositori, lalu ganti `<your-api-key>` dengan kunci API Anda yang sebenarnya

```
GOOGLE_API_KEY=<your-api-key>
```

8. Jalankan aplikasi:

```
python "Chatbot menggunakan generative ai(Tanpa API key).py"
```

## Alat dan Pustaka (Paket) yang digunakan
google
google-generativeai

## Penggunaan

Setelah aplikasi berjalan, Anda dapat mengobrol dengan Google Generative AI di konsol atau CMD Anda
ketik /quit atau /exit untuk mengakhiri percakapan yang mana juga mengakhiri program (Break Program)
