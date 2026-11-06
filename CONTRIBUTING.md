# Contributing Guide

## 1. Branch Convention

Setiap anggota kelompok wajib menggunakan format branch:

`<type>/<short-description>`

| Type | Kegunaan | Contoh |
|---|---|---|
| feature/ | Menambahkan fitur | feature/user-login |
| fix/ | Memperbaiki bug | fix/cart-total |
| hotfix/ | Perbaikan darurat | hotfix/payment-down |
| refactor/ | Merapikan kode | refactor/order-service |
| docs/ | Dokumentasi | docs/api-reference |
| test/ | Pengujian | test/checkout-flow |
| chore/ | Pemeliharaan | chore/update-deps |

Aturan:
- Menggunakan huruf kecil.
- Menggunakan tanda hubung (-).
- Tidak menggunakan spasi.
- Menyertakan nomor tiket jika tersedia.
- Maksimal 50 karakter.

## 2. Commit Convention

Format commit:

`<type>(<scope>): <subject>`

Jenis commit:
- feat: fitur baru.
- fix: perbaikan bug.
- docs: perubahan dokumentasi.
- style: perubahan format kode.
- refactor: penyusunan ulang kode.
- perf: peningkatan performa.
- test: penambahan pengujian.
- build: perubahan sistem build.
- ci: perubahan konfigurasi CI.
- chore: pemeliharaan proyek.
- revert: membatalkan commit.

Contoh:
- feat(auth): add user login
- fix(cart): correct total price
- docs(readme): update installation steps

Aturan:
- Menggunakan huruf kecil.
- Menggunakan kalimat perintah.
- Tidak menggunakan titik di akhir.
- Maksimal 50 karakter untuk subject.
- Referensi masalah menggunakan Closes #123.

## 3. Pull Request

Aturan Pull Request:
- Judul mengikuti format commit message.
- Perubahan maksimal 400 baris.
- Wajib mendapatkan persetujuan minimal satu reviewer.
- Wajib lolos CI.
- Menggunakan Squash Merge.

## 4. Code Review

Jenis komentar:
- blocking: perubahan wajib diperbaiki.
- nit: saran kecil yang bersifat opsional.
- question: meminta penjelasan.
- praise: memberikan apresiasi.

## 5. Workflow Git

1. Memperbarui branch main.
2. Membuat branch baru.
3. Mengerjakan perubahan.
4. Melakukan commit sesuai standar.
5. Push branch ke GitHub.
6. Membuat Pull Request.
7. Menunggu proses review.
8. Melakukan Squash Merge.
9. Menghapus branch setelah merge.

## 6. Larangan

- Tidak boleh push langsung ke main.
- Tidak menggunakan commit message yang tidak jelas.
- Tidak mengunggah file .env.
- Tidak mengunggah node_modules.
- Tidak mengunggah password atau credentials.
- Tidak melakukan rebase pada branch yang sudah digunakan anggota lain.