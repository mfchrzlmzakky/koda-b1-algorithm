# Algoritma

## Deskriptif
1. Mulai
2. Buat variabel A dengan nilai 1
3. Buat variabel B dengan nilai 1
4. Buat variabel C dengan nilai 0
5. Buat variabel Hasil untuk menyimpan hasil Variabel A * B + C
6. Tampilkan Hasil
7. Selesai

## Flowchart
``` mermaid
flowchart TB
start((Mulai))
inputA[/Variabel A = 1/]
inputB[/Variabel B = 1/]
inputC[/Variabel C = 0/]
result[Hasil A * B + C]
selesai(((end)))
start --> inputA --> inputB --> inputC --> result --> selesai
```

## Pseudo-Code
```
DECLARE A : INTEGER
DECLARE B : INTEGER
DECLARE C : INTEGER
DECLARE Result : INTEGER
A <- 1
B <- 1
C <- 0
Result <- A * B + C
OUTPUT "Hasilnya adalah ", Result

<!-- Function -->
FUNCTION Aritmatika(A : INTEGER, B : INTEGER, C : INTEGER) RETURNS INTEGER
 RETURN A * B + C
ENDFUNCTION
OUTPUT "Hasil = ", Aritmatika(1, 1, 0)
<!-- Cara Lain Memanggil Function -->
DECLARE Hasil : INTEGER
Hasil <- Aritmatika(1, 1, 0)
OUTPUT "Hasil ", Hasil
