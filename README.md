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
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/24c368a4-5b9f-4a9a-b5d7-c290a107cdcd" width="300" alt="Light Mode Preview" /> | <img src="https://github.com/user-attachments/assets/4eb64311-0ecf-40ce-b839-935e7f86c0a0" width="300" alt="Dark Mode Preview" /> |


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
