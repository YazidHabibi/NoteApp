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
| ![Light Mode Preview](<img width="300" height="500" alt="lightmodepreview" src="https://github.com/user-attachments/assets/3a6c6a9e-5bd4-4ce6-8ad9-c10f71a874c5" />
) | ![Dark Mode Preview](<img width="300" height="500" alt="darkmodepreview" src="https://github.com/user-attachments/assets/bdaf2fe0-7ccf-43b9-8b7f-138084fb6105" />
) |



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
