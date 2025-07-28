
# NoteApp – Aplikasi Catatan Harian

NoteApp adalah aplikasi berbasis Python yang sederhana untuk mencatat, melihat, dan menghapus catatan harian. Aplikasi ini menggunakan pendekatan Pemrograman Berorientasi Objek (OOP) dan dijalankan melalui Command Line Interface (CLI).

## Fitur Aplikasi
- Tambah catatan (judul dan isi)
- Lihat semua catatan
- Hapus semua catatan
- Penyimpanan catatan ke dalam file (`notes.txt`)

## Struktur Folder
```
noteapp/
├── main.py                # Program utama (entry point)
├── models/
│   └── note.py            # Class Note
├── services/
│   └── note_service.py    # Class NoteService untuk kelola data
├── data/
│   └── notes.txt          # File penyimpanan catatan (otomatis dibuat)
```

## Cara Menjalankan
1. Buka terminal di folder `noteapp/`.
3. Jalankan perintah berikut:

```bash
python main.py
```

## Tampilan Simulasi CLI
```
=== Aplikasi Catatan Harian ===
1. Tambah Catatan
2. Lihat Catatan
3. Hapus Semua Catatan
0. Keluar
Pilih menu: 1
Judul: Belajar PBO
Isi: Mengerjakan UAS PBO menggunakan Python OOP
✅ Catatan ditambahkan!
```

## Lisensi
Proyek ini dikembangkan untuk keperluan UAS mata kuliah Pemrograman Berorientasi Objek (PBO) – Universitas Amikom Yogyakarta.
