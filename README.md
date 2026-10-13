# Algoritma

## Algoritma memindahkan air

Menukar isi dari gelas teh dengan isi dari gelas kopi.

1. Mulai
2. Sediakan gelas kosong tambahan
3. Tuangkan isi gelas teh ke dalam gelas kosong
4. Tuangkan isi gelas kopi ke dalam gelas teh
5. Tuangkan isi gelas kosong ke dalam gelas kopi
6. Selesai

## Algoritma menentukan bilangan ganjil atau genap

### Deskriptif

1. Mulai
2. Masukkan sebuah angka
3. Hitung hasil dari pembagian (modulus) angka tersebut dengan bilangan 2
4. Jika hasil dari pembagian tersebut bukan 0, tampilkan angka tersebut sebagai ganjil
5. Jika tidak, tampilkan angka tersebut sebagai genap
6. Selesai

### Flowchart

```mermaid
flowchart TD
    Start@{ shape: start, label: mulai }
    Input@{ shape: lean-r, label: angka }
    Control@{ shape: diamond, label: "angka % 2 == 0?" }
    OutputOdd@{ shape: lean-l, label: "#quot;ganjil#quot;" }
    OutputEven@{ shape: lean-l, label: "#quot;genap#quot;" }
    End@{ shape: stop, label: selesai }

    Start --> Input --> Control
    Control --ya--> OutputEven --> End
    Control --tidak--> OutputOdd --> End
```

## Algoritma hitung luas dan keliling lingkaran

### Deskriptif

1. Mulai
2. Masukkan sebuah angka sebagai jari-jari
3. **Untuk luas lingkaran**, lakukan perkalian *pi* (3,14) dengan **jari-jari** kuadrat
4. Tampilkan hasil perkalian sebagai **luas lingkaran**
5. **Untuk keliling lingkaran**, lakukan perkalian *pi* (3,14) dengan bilangan **2** dan **jari-jari**
6. Tampilkan hasil perkalian terakhir sebagai **keliling lingkaran**
7. Selesai

### Flowchart

```mermaid
flowchart TD
    Start@{ shape: start, label: "mulai" }
    End@{ shape: stop, label: "selesai"}
    Input@{ shape: lean-r, label: "jari-jari"}
    OutputCircum@{ shape: lean-l, label: "3,14 x jari-jari<sup>2</sup>" }
    OutputArea@{ shape: lean-l, label: "3,14 x 2 x jari-jari "}

    Start --> Input --> OutputArea --> OutputCircum --> End
```
