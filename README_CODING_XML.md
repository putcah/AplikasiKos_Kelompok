# Coding XML UI Aplikasi Kos

Project ini berisi rancangan UI Android sesuai lampiran tugas:

- `app/src/main/res/layout/activity_login.xml` untuk halaman login.
- `app/src/main/res/layout/activity_beranda.xml` untuk halaman beranda.
- `app/src/main/res/drawable/` berisi background, tombol, card, dan ikon pendukung.
- `app/src/main/res/values/colors.xml` berisi warna utama aplikasi.

Cara pakai di Android Studio:

1. Buat project Android baru atau buka project kelompok Anda.
2. Salin folder `app/src/main/res` dari folder ini ke project Android tersebut.
3. Hubungkan layout login di Activity login dengan:

```kotlin
setContentView(R.layout.activity_login)
```

4. Hubungkan layout beranda di Activity beranda dengan:

```kotlin
setContentView(R.layout.activity_beranda)
```

Tampilan dibuat dengan kombinasi `LinearLayout`, `ScrollView`, `TextView`, `EditText`, `Button`, dan `ImageView`.
