# <div align="center">

  <h1>💸 Kaizen PAY</h1>
  
  <p>
    <b>Official Payment Gateway Interface</b><br>
    Sistem pembayaran modern dengan desain <i>Glassmorphism</i> & <i>Neon Glow</i>.
  </p>

  <p>
    <a href="https://github.com/Abizaral/Payment-Gateway-V2.0.git">
      <img src="https://img.shields.io/badge/Version-2.0-cyan?style=for-the-badge&logo=rocket" alt="Version">
    </a>
    <a href="https://github.com/username-kamu/nama-repo-kamu/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
    </a>
    <img src="https://img.shields.io/badge/Status-Active-blue?style=for-the-badge" alt="Status">
  </p>

  <br>
  
  <img src="https://via.placeholder.com/800x400/000000/22d3ee?text=Preview+Tampilan+Kaizen+Pay" alt="Preview Kaizen Pay" width="100%" style="border-radius: 20px; box-shadow: 0 0 20px rgba(34, 211, 238, 0.3);">

</div>

<br>

## ✨ Fitur Utama

Project ini dibuat untuk memudahkan proses checkout/pembayaran dengan tampilan yang estetik dan fungsional.

* 🎨 **Desain Modern:** Menggunakan gaya *Glassmorphism* (kaca transparan) dan efek *Neon Glow*.
* 📱 **Responsive:** Tampilan menyesuaikan layar HP maupun PC dengan sempurna.
* ⚡ **Tanpa Backend:** Berjalan murni menggunakan HTML, CSS (Tailwind), dan JS.
* 🔗 **Auto WhatsApp:** Pesan konfirmasi pembayaran terformat otomatis dan langsung mengarah ke WA Admin.
* 📋 **Copy to Clipboard:** Fitur salin nomor rekening/e-wallet dengan satu klik.
* 🧮 **Kalkulasi Otomatis:** Input nominal langsung terformat menjadi Rupiah.

---

## 🛠️ Teknologi yang Digunakan

| Tech | Deskripsi |
| :--- | :--- |
| <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white"> | Struktur utama website |
| <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white"> | Framework CSS untuk styling cepat |
| <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"> | Logika kalkulasi & interaksi WA |
| <img src="https://img.shields.io/badge/Font_Awesome-528DD7?style=flat&logo=font-awesome&logoColor=white"> | Ikon UI (Wallet, Bank, dll) |

---

## 🚀 Cara Menggunakan (Untuk Developer)

Ingin menggunakan template ini untuk bisnis kamu sendiri? Caranya sangat mudah!

1.  **Clone** atau **Download** repository ini.
2.  Buka file `index.html`.
3.  Cari bagian script konfigurasi di bawah (sekitar baris 200-an):
    ```javascript
    const DATA_MERCHANT = {
        whatsapp_admin: "628XXXXXXXXXX", // Ganti No WA Admin
        
        dana: {
            nomor: "08123456789", 
            qr_image: "LINK_GAMBAR_QR_DANA" 
        },
        // ... dst
    };
    ```
4.  Edit data tersebut sesuai kebutuhanmu.
5.  Upload ke GitHub Pages atau hosting pilihanmu!

---

## 📸 Demo Tampilan

| Input Nominal | Metode Pembayaran | Loading Screen |
| :---: | :---: | :---: |
| *User memasukkan jumlah uang* | *Pilihan DANA, GoPay, SeaBank* | *Animasi verifikasi unik* |

---

## 🤝 Support & Komunitas

Jika ada pertanyaan atau ingin request fitur, silakan hubungi saya:

<a href="https://tiktok.com/@kaizenn.zz">
  <img src="https://img.shields.io/badge/TikTok-Follow_Me-000000?style=for-the-badge&logo=tiktok&logoColor=white">
</a>

<br>
<div align="center">
  <p>Dibuat dengan ❤️ oleh <b>Abizar Al</b></p>
  <p class="text-xs">© 2026 Kaizen Pay System v2.0</p>
</div>
