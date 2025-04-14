# Mini-Task CLI Usage

This is bare minimum usage of cli.according to mini task on Day 1 (14/04/2025)

Membuat Folder Latihan Cli Dasar

```cmd
mkdir "Latihan CLI Dasar"
```

## Without Loop

Membuat File kosong LatihanX sebanyak 5x

```cmd
type con > "latihan1.txt"
type con >  "latihan2.txt"
type con > "latihan3.txt"
type con > "latihan4.txt"
type con >  "latihan5.txt"
```

## With Loop

Membuat File kosong Sebanyak 5x menggunakan looping

```cmd
for /l %i in (1,1,5) do type nul > file%i.txt
"Latihan%a.txt"
"latihan1.txt"
"latihan2.txt"
"latihan3.txt"
"latihan4.txt"
"latihan5.txt"
```

## Menampilkan Folder

Melihat daftar file yang dbuat

```cmd
dir

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/14/2025   2:29 PM                demo-vscode
d-----         4/14/2025  11:26 AM                latihan5.txt
-a----         4/14/2025  11:21 AM              0 latihan2.txt
-a----         4/14/2025  11:24 AM              0 latihan3.txt
-a----         4/14/2025   2:48 PM            875 README.md
```

## Menghapus file urutan 5

```cmd
rmdir "latihan5.txt"
```

## Membuat Folder Urutan 5

```cmd
mkdir "latihan5.txt"
```

## Melihat folder yang dibuat

```cmd
dir

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/14/2025   2:29 PM                demo-vscode
d-----         4/14/2025  11:26 AM                latihan5.txt
-a----         4/14/2025  11:21 AM              0 latihan2.txt
-a----         4/14/2025  11:24 AM              0 latihan3.txt
-a----         4/14/2025   2:48 PM            875 README.md
```

## Menghapus folder dengan nama "latihan4.txt"

```cmd
rmdir "latihan4.txt"
```

## LOOPING LAGU

````cmd
# With Loop

```cmd
mkdir "Blackpink"
mkdir "Evanescence"
mkdir "Linkin Park"
for %a in (Blackpink, Evanescence, "Linkin Park") do move "%a -*" "%a\"



````
