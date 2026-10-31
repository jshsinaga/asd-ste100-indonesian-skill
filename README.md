# Bahasa Indonesia Teknis Sederhana

Skill untuk membuat teks teknis bahasa Indonesia lebih jelas, bersih, dan lugas
tanpa mengubah makna. Terinspirasi oleh
[asd-ste100-skill](https://github.com/danyuchn/asd-ste100-skill) untuk bahasa Inggris.

## Contoh

| Sebelum | Sesudah |
|---|---|
| Sebaiknya Anda melakukan pemeriksaan konfigurasi sebelum menerapkan perubahan. | Sebaiknya Anda memeriksa konfigurasi sebelum menerapkan perubahan. |
| Lakukan penghapusan hanya pada berkas sementara yang usianya lebih dari 7 hari, kecuali berkas yang sedang digunakan. | Hapus hanya berkas sementara yang berusia lebih dari 7 hari dan tidak sedang digunakan. |

## Instalasi

```bash
npx skills add jshsinaga/asd-ste100-indonesian-skill
```

## Penggunaan

Tempatkan folder `asd-ste100-indonesian` di direktori skill yang didukung agen
Anda, misalnya `.agents/skills/` pada proyek. Lalu minta:

```text
Gunakan $asd-ste100-indonesian untuk menyederhanakan teks berikut:
[teks Anda]
```

Skill mengembalikan hasil saja. Tambahkan `jelaskan perubahannya` jika Anda ingin
melihat alasan penyuntingan. Jika teks sudah jelas, skill mempertahankannya.

Instruksi utama ada di [SKILL.md](skills/asd-ste100-indonesian/SKILL.md), dengan
[panduan penulisan](skills/asd-ste100-indonesian/references/writing-rules.md) dan
[contoh sebelum/sesudah](skills/asd-ste100-indonesian/examples/before-after.md).

## Asal dan Status

Adaptasi dari [danyuchn/asd-ste100-skill](https://github.com/danyuchn/asd-ste100-skill),
dengan dasar commit lokal `255631a36dea63b427b6a454c1e59a53cdc0b14a`.
Lisensi [MIT](LICENSE), dengan pemberitahuan hak cipta upstream dipertahankan.

ASD-STE100 mengatur bahasa Inggris. Aturan Indonesia ini adalah adaptasi proyek,
bukan standar resmi ASD-STE100.

Skill `asd-ste100-indonesian`, versi `0.1.0`.
