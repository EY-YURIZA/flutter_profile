## Hari 1: Kerangka Dasar & Refactoring Awal

### Pagi
* **Keterangan & Perbaikan:**
  * Membuat struktur file `main.dart` dan `profile_page.dart`.
  * Menampilkan avatar dan teks nama/role.
  * **Fix:** Mengubah `SizedBox(width: 16)` menjadi `SizedBox(height: 16)` karena disusun secara vertikal (`Column`).

### Malam
* **Commit:** `refactor: extract avatar and info into custom widgets`
* **Keterangan & Perbaikan:**
  * Memecah UI menjadi custom widget `ProfileAvatar` dan `ProfileInfo`.
  * Menerapkan parameter passing data (`name` dan `role`).

---

  ## Hari 2: Komponen Statistik Profil

### Pagi
* **Commit:** `feat: add profile statistics row`
* **Keterangan & Perbaikan:**
  * Menambahkan baris statistik (Proyek, Followers, Following) dan tombol Edit.
  * **Fix:** Mengubah angka integer `42` menjadi String `'42'` pada `StatItem` agar tidak error.