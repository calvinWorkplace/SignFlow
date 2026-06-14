<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"/>
</p>

<h1 align="center">🤟 SignFlow</h1>

<p align="center">
  <b>Pembelajaran Hand Sign melalui Aplikasi Mobile Interaktif</b><br/>
  Meningkatkan komunikasi antara pengguna normal dan disabilitas melalui Bahasa Isyarat Indonesia (BISINDO)
</p>

<p align="center">
  <a href="https://github.com/abeliooo/SignFlow">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github" alt="GitHub"/>
  </a>
  <a href="https://www.figma.com/proto/Pt9qce1sObYI1b00YK75Jl/Protorype-SignFlow?node-id=0-1&t=seDDc9ZFOCdA1pta-1">
    <img src="https://img.shields.io/badge/Figma-Prototype-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma"/>
  </a>
</p>

---

## 📖 Tentang SignFlow

**SignFlow** adalah aplikasi mobile edukatif berbasis Flutter yang dirancang untuk mengajarkan **Bahasa Isyarat Indonesia (BISINDO)** kepada masyarakat umum. Nama *SignFlow* mencerminkan fokus pada bahasa isyarat (*Sign*) dengan alur pembelajaran yang lancar dan terstruktur (*Flow*).

Aplikasi ini hadir sebagai solusi atas minimnya media pembelajaran bahasa isyarat yang interaktif, dengan memanfaatkan teknologi digital untuk mendukung pembelajaran inklusif bagi penyandang disabilitas pendengaran.

---

## 🎯 Tujuan

<table>
  <tr>
    <td align="center" width="33%">
      <b>♿ Inklusivitas</b><br/>
      Menyediakan platform pembelajaran Bahasa Isyarat Indonesia yang mudah diakses oleh masyarakat umum.
    </td>
    <td align="center" width="33%">
      <b>🤝 Komunikasi</b><br/>
      Meningkatkan kemampuan komunikasi antara pengguna normal dan disabilitas melalui media interaktif.
    </td>
    <td align="center" width="33%">
      <b>🌍 Kesenjangan Sosial</b><br/>
      Mengurangi kesenjangan sosial dengan menciptakan masyarakat yang lebih inklusif dan berempati.
    </td>
  </tr>
</table>

---

## ✨ Fitur Utama

<table>
  <tr>
    <td width="50%">
      <b>🔐 Login & Sign Up</b><br/>
      Autentikasi menggunakan Firebase Authentication — mendukung login dengan email/password, Google, dan Microsoft. Tersedia fitur <i>Forget Your Password</i> untuk reset password.
    </td>
    <td width="50%">
      <b>🏠 Home & Unit Pembelajaran</b><br/>
      Tampilan unit-unit pembelajaran yang terkunci secara berurutan. Pengguna hanya dapat membuka unit berikutnya setelah menyelesaikan unit sebelumnya.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b>🎬 Video Tutorial</b><br/>
      Setiap chapter menampilkan video pembelajaran bahasa isyarat yang disimpan di Firebase Storage. Lesson baru hanya terbuka setelah lesson sebelumnya selesai.
    </td>
    <td width="50%">
      <b>📝 Quiz Interaktif</b><br/>
      Quiz pilihan ganda di akhir setiap lesson untuk menguji pemahaman. Pengguna memiliki sistem <b>HP (Health Point)</b> — 3 HP default, berkurang setiap jawaban salah.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b>📚 Dictionary (Kamus Isyarat)</b><br/>
      Referensi kamus bahasa isyarat A–Z dengan video per huruf, dapat diakses kapan saja sebagai referensi visual cepat di luar sesi lesson.
    </td>
    <td width="50%">
      <b>👤 Profile & Daily Streak</b><br/>
      Halaman profil dengan fitur daily streak, riwayat pembelian HP, langganan (subscription), dan sertifikat yang dapat diunduh dan dibagikan.
    </td>
  </tr>
</table>

---

## 📸 Screenshots

### 🔐 Login Page

<p align="center">
  <img src="assets/screenshots/login1.jpg" width="220" alt="Login Page 1"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/login2.jpg" width="220" alt="Login Page 2"/>
</p>

<p align="center">
  Halaman awal untuk pengguna masuk ke dalam aplikasi. Mendukung login via email, Google, dan Microsoft.
</p>

---

### 🏠 Home Page

<p align="center">
  <img src="assets/screenshots/home1.jpg" width="220" alt="Home Page 1"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/home2.jpg" width="220" alt="Home Page 2"/>
</p>

<p align="center">
  Pengguna disambut dengan unit-unit pembelajaran. Setiap unit berisi chapter dengan video pembelajaran tematik.
</p>

---

### 🎬 Video Tutorial Page

<p align="center">
  <img src="assets/screenshots/video1.jpg" width="220" alt="Video Tutorial 1"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/video2.jpg" width="220" alt="Video Tutorial 2"/>
</p>

<p align="center">
  Menampilkan video pembelajaran bahasa isyarat. Setiap lesson baru hanya terbuka setelah lesson sebelumnya selesai.
</p>

---

### 📝 Quiz Page

<p align="center">
  <img src="assets/screenshots/quiz1.jpg" width="220" alt="Quiz 1"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/quiz2.jpg" width="220" alt="Quiz 2"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/quiz_hp1.jpg" width="220" alt="Quiz HP"/>
</p>

<p align="center">
  Quiz pilihan ganda di akhir setiap lesson. Jawaban salah akan mengurangi HP pengguna.
</p>

<p align="center">
  <img src="assets/screenshots/quiz_purchase1.jpg" width="220" alt="Purchase HP"/>
</p>

<p align="center">
  Jika HP habis, pengguna dapat membeli HP tambahan untuk melanjutkan pembelajaran.
</p>

---

### 📚 Dictionary Page

<p align="center">
  <img src="assets/screenshots/dictionary1.jpg" width="220" alt="Dictionary 1"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/dictionary2.jpg" width="220" alt="Dictionary 2"/>
</p>

<p align="center">
  Kamus isyarat A–Z dengan video pendek per huruf sebagai referensi visual cepat.
</p>

---

### 👤 Profile Page

<p align="center">
  <img src="assets/screenshots/profile1.jpg" width="220" alt="Profile 1"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/profile2.jpg" width="220" alt="Profile 2"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/profile_edit1.jpg" width="220" alt="Profile Edit"/>
</p>

<p align="center">
  <img src="assets/screenshots/subscription1.jpg" width="220" alt="Subscription"/>
  &nbsp;&nbsp;
  <img src="assets/screenshots/help1.jpg" width="220" alt="Help & Support"/>
</p>

<p align="center">
  Halaman profil dengan daily streak, edit data pribadi, langganan (3 jenis), sertifikat, dan Help & Support.
</p>

---

## 🛠️ Teknologi

<table>
  <tr>
    <th align="center">Teknologi</th>
    <th align="center">Kegunaan</th>
  </tr>
  <tr>
    <td align="center"><b>Flutter</b></td>
    <td>Desain antarmuka interaktif, navigasi antar halaman, animasi & media, cross-platform, integrasi plugin</td>
  </tr>
  <tr>
    <td align="center"><b>Firebase Authentication</b></td>
    <td>Login/Sign Up via email, Google, dan Microsoft</td>
  </tr>
  <tr>
    <td align="center"><b>Cloud Firestore</b></td>
    <td>Menyimpan progres belajar, hasil quiz, streak, dan preferensi pengguna</td>
  </tr>
  <tr>
    <td align="center"><b>Firebase Storage</b></td>
    <td>Penyimpanan dan streaming video pembelajaran bahasa isyarat</td>
  </tr>
</table>

---

## ⚙️ Prasyarat

Sebelum menjalankan proyek ini, pastikan Anda telah menginstall:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (versi stabil terbaru)
- [Dart SDK](https://dart.dev/get-dart) (sudah termasuk di Flutter)
- [Android Studio](https://developer.android.com/studio) atau VS Code dengan ekstensi Flutter
- Akun [Firebase](https://firebase.google.com/) untuk konfigurasi backend

---

## 🚀 Cara Instalasi

**1. Clone repository**

```bash
git clone https://github.com/abeliooo/SignFlow.git
cd SignFlow
```

**2. Install dependencies**

```bash
flutter pub get
```

**3. Konfigurasi Firebase**

- Buat project di [Firebase Console](https://console.firebase.google.com/)
- Download file `google-services.json` dan letakkan di folder `android/app/`
- Aktifkan Firebase Authentication, Firestore, dan Storage

**4. Jalankan aplikasi**

```bash
flutter run
```

---

<details>
<summary><b>ℹ️ Catatan Developer (Klik untuk buka)</b></summary>

<br/>

Terdapat 2 versi aplikasi dalam repository ini:

| Folder | Keterangan |
|--------|-----------|
| `withGoogleSignIn` | Versi lengkap dengan dukungan login Google & Microsoft (memerlukan konfigurasi OAuth) |
| `justLocal` | Versi yang hanya menggunakan dummy email untuk pengujian lokal |

**Fitur Debug (Reset Button):**
Di pojok kanan atas terdapat tombol reset untuk keperluan debugging. Tombol ini dapat mereset:
- Progress lesson pengguna
- Daily streak
- HP (Health Point)

</details>

---

## 👥 Tim Pengembang

<p align="center">
  Proyek ini dikembangkan oleh <b>Group 10</b> — AOL Software Engineering
</p>

<table align="center">
  <tr>
    <th>NIM</th>
    <th>Nama</th>
  </tr>
  <tr>
    <td>2702225612</td>
    <td>Albert Tandy Harison</td>
  </tr>
  <tr>
    <td>2702225846</td>
    <td>Calvin Suharjono</td>
  </tr>
  <tr>
    <td>2702253793</td>
    <td>Lucky Sean Marulin</td>
  </tr>
  <tr>
    <td>2702210485</td>
    <td>Ringo Gary Buntino</td>
  </tr>
  <tr>
    <td>2702302271</td>
    <td>Stefanus Abel Fillio</td>
  </tr>
</table>

---

<p align="center">
  Made with ❤️ for a more inclusive world
</p>
