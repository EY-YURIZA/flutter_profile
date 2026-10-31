## Hari 1: Kerangka Dasar & Refactoring Awal

### Pagi
* **Keterangan & Perbaikan:**
  * Membuat struktur file `main.dart` dan `profile_page.dart`.
  * Menampilkan avatar dan teks nama/role.
  * **Fix:** Mengubah `SizedBox(width: 16)` menjadi `SizedBox(height: 16)` karena disusun secara vertikal (`Column`).

### Malam

* **Keterangan & Perbaikan:**
  * Memecah UI menjadi custom widget `ProfileAvatar` dan `ProfileInfo`.
  * Menerapkan parameter passing data (`name` dan `role`).

---

  ## Hari 2: Komponen Statistik Profil

### Pagi

* **Keterangan & Perbaikan:**
  * Menambahkan baris statistik (Proyek, Followers, Following) dan tombol Edit.
  * **Fix:** Mengubah angka integer `42` menjadi String `'42'` pada `StatItem` agar tidak error.

  ### Malam

* **Keterangan & Perbaikan:**
  * Mengekstrak baris statistik menjadi widget terpisah `ProfileStats` dan `StatItem` agar *reusable*.


  ---

## Hari 3: Daftar Pengalaman (ListView)

### Pagi

* **Keterangan & Perbaikan:**
  * Menampilkan daftar pengalaman kerja menggunakan `ListView.builder`.
  * **Fix:** Menambahkan tanda koma (`,`) yang hilang pada array data `experiences`.
  * **Fix:** Membungkus `ListView.builder` dengan widget `Expanded` agar tidak terjadi error *layout overflow*.