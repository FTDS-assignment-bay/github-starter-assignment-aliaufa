# Cara Clone dan Push ke Github dari Local

## 1. Clone Repository

Berikut cara clone dari SSH:
1. buka repository-nya
2. di bagian `<> Code` warna hijau, copy URL dari tab SSH
3. buka terminal di directory local dimana kalian akan clone repo
4. di terminal tulis `git clone <url yang di copy>`
5. akan terbuat folder hasil clone di directory-nya

Setelah ada hasil clone, kita bekerja di folder repository tersebut.

## 2. Add and Commit files

Setelah ada perubahan file di folder repo yang ingin kita track perubahannya maka harus kita lakukan add dan commit. caranya:
1. di terminal (pastikan directorynya sudah repository) cek status files dengan `git status`
2. jika ada perubahan dari file apapun akan diindikasikan dengan warna merah
3. untuk track perubahan lakukan `git add <nama file>` atau juka banyak bisa `git add .` untuk track semua perubahan pada semua file sekaligus.
4. kalau mau lihat status setelah di add harusnya warnanya hijau.
5. gunakan `git commit -m "pesan commit" untuk menandakan batch perubahan

## 3. Push and Pull to github
1. setelah ada commit yang mau dimasukan ke github bisa lakukan `git push`
2. kalau kita menggunakan device yang berbeda dan ada clone di device masing-masing, sebelum mengerjakan apa-apa lakukan `git pull`