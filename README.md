# My Notes App 📝

Aplikasi catatan (Notes) sederhana dan minimalis yang dibangun menggunakan **Flutter**. Proyek ini menampilkan tata letak grid dua kolom, fitur perpindahan tema (Dark/Light mode), dan fungsi CRUD lengkap.

---

## ✨ Fitur Utama

* **Mode Gelap & Terang**: Berpindah tema dengan mudah melalui ikon toggle di bagian header.
* **Tata Letak Grid**: Tampilan catatan yang rapi dengan sistem grid 2 kolom yang responsif.
* **Operasi CRUD Lengkap**:
    * **Tambah (Create)**: Menambahkan catatan baru melalui Floating Action Button.
    * **Baca (Read)**: Menampilkan daftar catatan yang tersusun rapi di halaman utama.
    * **Ubah (Update)**: Mengedit isi catatan hanya dengan mengetuk kartu catatan.
    * **Hapus (Delete)**: Menghapus catatan secara cepat menggunakan ikon sampah merah.
* **UI Minimalis**: Desain bersih dan fokus pada fungsionalitas untuk produktivitas.

---

## 📸 Cuplikan Layar (Screenshots)

| Mode Terang | Mode Gelap |
|---|---|
| ![Dark Mode Preview](<img width="500" height="656" alt="darkmodepreview" src="https://github.com/user-attachments/assets/fea3da3c-9905-457b-b0f1-37cdf8f8271c" />
) | ![Light Mode Preview](<img width="498" height="653" alt="lightmodepreview" src="https://github.com/user-attachments/assets/cd2b0410-7388-4ea0-b5d8-90f69e1bcf14" />
) |

> *Catatan: Jangan lupa ganti gambar di atas dengan screenshot asli dari aplikasi kamu.*

---

## 🚀 Memulai

### Prasyarat
* Flutter SDK (Versi terbaru)
* Dart SDK
* Android Studio / VS Code

### Instalasi
1.  **Clone repository ini**
    ```bash
    git clone [https://github.com/username-kamu/my-notes-app.git](https://github.com/username-kamu/my-notes-app.git)
    ```
2.  **Masuk ke direktori proyek**
    ```bash
    cd my-notes-app
    ```
3.  **Instal package yang dibutuhkan**
    ```bash
    flutter pub get
    ```
4.  **Jalankan aplikasi**
    ```bash
    flutter run
    ```

---

## 🛠️ Teknologi yang Digunakan
* **Framework**: [Flutter](https://flutter.dev)
* **Bahasa**: [Dart](https://dart.dev)
* **UI Components**: Material Design 3

---

## 📂 Struktur Proyek
```text
lib/
├── main.dart           # Titik masuk utama dan logika tema
├── models/             # Model data untuk catatan
├── screens/            # Layar utama (Beranda, Tambah/Edit)
└── widgets/            # Widget kustom (Kartu catatan, dll)
