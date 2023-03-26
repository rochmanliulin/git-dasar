## Keyword GIT

Berikut merupakan beberapa keyword GIT yang sering digunakan

Membuat Repository
```shell
git init
```

Menambahkan file ke staging directory
```shell
git add namaFile
```

Menambahkan file ke repository
```shell
git commit
```

Memberikan message / pesan ketika membuat commit
```shell
git commit -m "pesan"
```

Melihat perubahan code
```shell
git diff
```


Melihat history lengkap
```shell
git log
```

Melihat satu baris hystory
```shell
git log --oneline
```

Mengembalikan file:
- Mengembalikan perubahan file dari working directory
```shell
git restore namaFile
```

- Mengembalikan file dari staging ke working directory
```shell
git restore -S namaFile
```
- Mengembalikan semua file dari staging ke working directory
```shell
git reset
```

Kembali ke commit versi lama dan menghapus commit versi terbaru
```shell
git reset --hard hashCode
```

Berpindah branch
```shell
git checkout namaBranch
```

Membuat branch baru (-b)
```shell
git checkout -b namaBranch
```

Menggabungkan branch ke master
```shell
git merge namaBranch
```

Merevisi commit / kembali ke versi commit sebelumnya dan tidak menghapus commit terbaru, tapi akan terjadi conflict antara versi commit lama yang dipilih dengan commit terbaru
```shell
git revert
```

Menyalin repository Git ke local komputer
```shell
git clone
```

Menupload local repository ke remote repository (Github, Gitlab, dll)
```shell
git push
```

Mendownload remote repository ke local repository
```shell
git pull
```


### Noted
Cara kembali dari commit versi terbaru ke versi lama :
- `git checkout`  : Kembali hanya untuk sementara (tidak disarankan)
- `git reset`     : Kembali dan menghapus versi terbaru
- `git revert`    : Kembali dan versi terbaru tetap ada