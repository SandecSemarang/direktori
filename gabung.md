# Cara menambah data
Untuk yang belum pernah menggunakan git, dapat belajar di [tutorial](https://github.com/endymuhardin/belajarGit).

# Langkah-Langkah pada Windows

## Langkah 0: Pastikan sudah memiliki akun [GitHub](https://github.com/) dan terinstall [git](https://git-scm.com/downloads) di laptop/PCnya

## Langkah 1a: Bagi yang belum pernah *fork* dan *clone*
- Lakukan *fork* pada [direktori](https://github.com/SandecSemarang/direktori).
![1a fork](https://github.com/SandecSemarang/direktori/blob/master/images/gitwindows-1a-1-fork.JPG)

- Anda akan memiliki *repository* `username/direktori`
![1a hasil fork](https://github.com/SandecSemarang/direktori/blob/master/images/gitwindows-1a-2-hasil-fork.JPG)

- Lakukan *clone* hasil *fork*.
  1. *Copy* url untuk melakukan *clone*
  ![1a copy](https://github.com/SandecSemarang/direktori/blob/master/images/gitwindows-1a-3-copy.JPG)
  2. Buka *command prompt* dan lakukan perintah berikut.<br />
  `$ git clone git@github.com:username/direktori.git`
  ![1a clone](https://github.com/SandecSemarang/direktori/blob/master/images/gitwindows-1a-4-cmd.JPG)
  3. Pindah ke *folder* direktori untuk operasi *git* pada langkah 1b
  ![1a cd](https://github.com/SandecSemarang/direktori/blob/master/images/gitwindows-1a-5-cd.JPG)

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


# Langkah-Langkah pada Linux
