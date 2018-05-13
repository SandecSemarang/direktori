# Cara menambah data
Untuk yang belum pernah menggunakan git, dapat belajar di [tutorial](https://github.com/endymuhardin/belajarGit).

# Langkah-Langkah
## Langkah 1a: Bagi yang belum pernah *fork* dan *clone*
- Lakukan *fork* pada [direktori](https://github.com/SandecSemarang/direktori).
- Anda akan memiliki *repository* `username/direktori`
- Lakukan *clone* hasil *fork*. `$ git clone git@github.com:username/direktori.git`

## Langkah 1b: Bagi yang sudah pernah *fork* dan *clone*
- Tambahkan *upstream* sandecsemarang/direktori pada *clone* direktori

`$ git remote add upstream git://github.com/SandecSemarang/direktori.git`<br/>
`$ git fetch upstream`<br/>
`$ git rebase upstream/master`<br/>

## Langkah 2
Lakukan perubahan, dengan menambahkan nama sesuai urutan.

## Langkah 3
Lakukan `commit` dan `push` ke `direktori` pribadi -> `username/direktori`

## Langkah 4
Lakukan *Pull Request* dengan menyesuaikan **username**  pada link berikut.<br/>
[https://github.com/username/direktori/compare/SandecSemarang:master...master](https://github.com/username/direktori/compare/SandecSemarang:master...master)
