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
3. Lakukan pembagian antara angka tersebut dengan bilangan 2
4. Jika hasil dari pembagian tersebut bukan 0, tampilkan angka tersebut sebagai ganjil
5. Jika tidak, tampilkan angka tersebut sebagai genap
6. Selesai

### Flowchart

```mermaid
flowchart TD
Start@{ shape: circle, label: mulai }
Input@{ shape: lean-r, label: angka }
A@{ shape: rect,  label: mod = angka % 2 }
Control@{ shape: diamond, label: mod = 0? }
OutputOdd@{ shape: lean-l, label: #quot;ganjil#quot; }
OutputEven@{ shape: lean-l, label: #quot;genap#quot; }
End@{ shape: dbl-circ, label: selesai }

Start --> Input --> A --> Control
Control --ya--> OutputEven --> End
Control --tidak--> OutputOdd --> End
```

## Algoritma hitung luas dan keliling lingkaran

1. Mulai
2. Masukkan sebuah angka jari-jari lingkaran
3. Lakukan perkalian nilai *pi* sebesar 3,14 dengan **jari-jari** lingkaran tersebut
4. **Untuk luas lingkaran**, lakukan perkalian dari hasil perkalian *pi* pertama dengan dengan **jari-jari** lagi
5. Tampilkan hasil perkalian terakhir sebagai **luas lingkaran**
6. **Untuk keliling lingkaran**, lakukan perkalian dari hasil perkalian *pi* pertama dengan bilangan **2**
7. Tampilkan hasil perkalian terakhir sebagai **keliling lingkaran**
8. Selesai

