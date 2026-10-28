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