# pencariloker


Ini adalah website pencari loker, hanyalah sebuah project yang dikasih oleh bapak Nova K.
Proyek ini dibangun atas kepasrahan kelompok dalam memilih pilihan, hanya ini yang tersisa yang tersedia.

# Cara Push ( Buat Anggota tercinta )
```bash
$ git add .
$ git commit -m "pesan commit lo"
$ git push -u origin main

```
# Troubleshooting 👀
Kalau dapat Error 
```bash
$ error: failed to push some refs to 'https://github.com/ardan-su/pencariloker.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```


kudu di giniin dulu 

```bash
$ git pull
```
lalu
```bash
$ git push -u origin main
```

Selamat Ngoding, kalau mau tesh push bisa di readme.md