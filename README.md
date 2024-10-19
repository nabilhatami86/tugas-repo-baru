# tugas-repo-baru

---

# Git Workflow

Repository ini berisi materi dan perintah dasar Git untuk memulai dan mengelola proyek dengan baik.

## Perintah Dasar Git
1. **Inisialisasi Repository**
   ```bash
   git init
   ```
   Inisialisasi repository Git baru.

2. **Konfigurasi Pengguna**
   ```bash
   git config --global user.name "Nama Pengguna"
   git config --global user.email "email@example.com"
   ```
   Mengatur nama dan email pengguna.

3. **Melihat Status**
   ```bash
   git status
   ```
   Memeriksa status file yang belum di-*commit*.

4. **Menambahkan File**
   ```bash
   git add .
   ```
   Menambahkan semua file ke *staging area*.

5. **Commit Perubahan**
   ```bash
   git commit -m "Pesan commit"
   ```
   Menyimpan perubahan dengan pesan commit.

6. **Membuat Branch Baru**
   ```bash
   git branch <branch_name>
   ```
   Membuat *branch* baru untuk fitur atau pengembangan.

7. **Berpindah Branch**
   ```bash
   git checkout <branch_name>
   ```
   Berpindah ke *branch* yang baru dibuat.

8. **Merge Branch**
   ```bash
   git merge <branch_name>
   ```
   Menggabungkan *branch* ke *branch* aktif.

9. **Menghapus Branch**
   ```bash
   git branch -d <branch_name>
   ```
   Menghapus *branch* yang sudah selesai.

## Push ke GitHub
Setelah commit, Anda dapat mendorong perubahan ke GitHub dengan:
```bash
git push origin <branch_name>
```

---

README ini merangkum semua perintah penting dalam penggunaan Git untuk manajemen proyek.
