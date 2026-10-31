# Contoh Sebelum dan Sesudah

Contoh berikut menunjukkan gaya hasil yang dituju. Makna sumber tetap menjadi acuan.

## Kata Kerja Langsung

Sebelum:

> Sebaiknya Anda melakukan pemeriksaan konfigurasi sebelum menerapkan perubahan.

Sesudah:

> Sebaiknya Anda memeriksa konfigurasi sebelum menerapkan perubahan.

## Pesan Error yang Belum Pasti

Sebelum:

> Ada kemungkinan bahwa permintaan gagal karena ukuran berkas mungkin melampaui batas 10 MB.

Sesudah:

> Permintaan mungkin gagal karena ukuran berkas mungkin melebihi batas 10 MB.

## Kalimat Aktif

Sebelum:

> Pemeriksaan konfigurasi akan dilakukan oleh server sebelum layanan dimulai.

Sesudah:

> Server akan memeriksa konfigurasi sebelum layanan dimulai.

## Syarat dan Urutan Langkah

Sebelum:

> Jika semua pengujian lulus, sebaiknya Anda melakukan peninjauan terhadap hasilnya lalu melakukan pencatatan nomor versi.

Sesudah:

> Jika semua pengujian lulus, sebaiknya Anda meninjau hasilnya. Setelah peninjauan itu, sebaiknya Anda mencatat nomor versi.

## Batas dan Pengecualian

Sebelum:

> Lakukan penghapusan hanya pada berkas sementara yang usianya lebih dari 7 hari, kecuali berkas yang sedang digunakan.

Sesudah:

> Hapus hanya berkas sementara yang berusia lebih dari 7 hari dan tidak sedang digunakan.

## Kode Tetap Utuh

Sebelum:

> Lakukan pengaturan pada `retry_count` menjadi `3`, kemudian jalankan `client.send("a;b", timeout=10)` dan lakukan penyimpanan respons pada `{output_path}`.

Sesudah:

1. Atur `retry_count` menjadi `3`.
2. Jalankan `client.send("a;b", timeout=10)`.
3. Simpan respons pada `{output_path}`.

## Teks yang Sudah Jelas

Sumber dan hasil tetap sama:

> Jika token kedaluwarsa, server menolak permintaan dengan status `401`.

## Ambiguitas yang Perlu Ditanyakan

Sumber:

> Arsipkan laporan dan log yang lebih lama dari 30 hari.

Respons:

> Apakah batas usia lebih dari 30 hari berlaku untuk laporan dan log, atau hanya untuk log?
