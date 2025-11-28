# TA-6-Praktikum-Pemrograman-Web

---

# Dokumentasi

## Dark Mode

<img width="663" height="713" alt="Screenshot 2025-11-28 214332" src="https://github.com/user-attachments/assets/effea947-804d-449c-ad6c-7081ee9cdf23" />

---

## Light Mode

<img width="581" height="709" alt="Screenshot 2025-11-28 214416" src="https://github.com/user-attachments/assets/b3b8e1b8-00e3-4724-8141-73bfe2d28c0c" />


# 🚀 XelaWeather Dashboard

XelaWeather adalah aplikasi dashboard cuaca modern dan responsif, dibangun menggunakan HTML, JavaScript murni, dan Tailwind CSS. Aplikasi ini menyediakan informasi cuaca *real-time* dan prakiraan 5 hari, dilengkapi dengan fitur interaktif, *autocomplete* pencarian, dan dukungan untuk Dark/Light Mode.

## ✨ Fitur Utama

Dashboard XelaWeather dirancang untuk memberikan pengalaman pengguna yang cepat dan informatif, menyoroti fitur-fitur utama berikut:

---

### ☀️ Current Weather Display

Informasi cuaca terkini ditampilkan secara jelas di bagian tengah dasbor:

| Fitur | Deskripsi |
| :--- | :--- |
| **Data Dasar** | Menampilkan **Suhu**, **Kelembapan** (*humidity*), dan **Kecepatan Angin** (*wind speed*). |
| **Kondisi & Ikon** | Kondisi cuaca utama (misalnya, Clear, Clouds, Rain) direpresentasikan dengan **ikon Emoji** yang sesuai. |
| **Lokasi & Waktu** | Menampilkan nama lokasi lengkap (`Kota, Negara`) dan dua *timestamp*: |
| **Timestamp Lokal** | Waktu saat ini di lokasi pengguna, **diperbarui setiap detik**. |
| **Real-time Updates** | Data cuaca diperbarui secara otomatis setiap **5 menit**. |

### 🗓️ 5-Day Forecast

Menyediakan gambaran cuaca harian untuk 5 hari ke depan dalam format kartu yang *scannable*:

* **Prediksi Harian:** Menampilkan ramalan cuaca untuk hari kerja (Senin, Sel, Rab, dll.).
* **Suhu Min/Max:** Menampilkan kisaran suhu minimum dan maksimum harian.
* **Detail Visual:** Setiap kartu prakiraan mencakup ikon cuaca dan deskripsi kondisinya.

### 🔍 Search Functionality

Memudahkan pengguna untuk mencari dan menyimpan lokasi:

* **Pencarian Berdasarkan Nama Kota:** Cari data cuaca secara instan dengan memasukkan nama kota.
* ***Auto-complete Suggestions***: Sistem memberikan saran kota secara *real-time* saat mengetik (didukung oleh OpenWeather Geocoding API).
* **Simpan Kota Favorit:** Pengguna dapat menandai kota yang sedang dilihat sebagai favorit (dengan ikon ⭐). Kota favorit muncul sebagai tombol pintasan untuk akses cepat.

### ⚙️ Interactive Features

Meningkatkan pengalaman pengguna dengan kontrol personalisasi:

* **Toggle Suhu:** Beralih dengan mudah antara satuan **Celsius (°C)** (default) dan **Fahrenheit (°F)**.
* **Toggle Tema:** Beralih antara tema Terang (*Light Mode*) dengan gradien warna dinamis, dan tema Gelap (*Dark Mode*) dengan latar belakang gelap kontras.
* **Tombol Perbarui (*Refresh*):** Tombol manual untuk memaksa pembaruan data cuaca saat ini, disertai indikator animasi (*spin*).
* ***Loading Indicators***: Efek *skeleton loading* ditampilkan di seluruh dasbor saat data cuaca sedang diambil.

---

## 🛠️ Persyaratan dan Instalasi

Aplikasi ini dibangun menggunakan tumpukan teknologi web dasar dan memerlukan kunci API dari OpenWeatherMap.

### Persyaratan:

* Kunci API OpenWeatherMap.

### Cara Menjalankan:

1.  Salin kode HTML lengkap (termasuk CSS dan JavaScript).
2.  Simpan kode tersebut sebagai file tunggal bernama `index.html`.
3.  **Penting:** Ganti placeholder `API_KEY` di dalam tag `<script>` dengan kunci API OpenWeatherMap Anda yang valid:

    ```javascript
    const API_KEY = 'GANTI_DENGAN_API_KEY_ANDA'; 
    ```

4.  Buka file `index.html` di browser web modern Anda.
