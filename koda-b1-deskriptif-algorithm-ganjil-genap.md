Menentukan bilangan ganjil atau genap

1. Mulai
2. Siapkan variabel untuk menampung bilangan yang mau dicek ganjil atau genap
3. Masukkan bilangan yang mau dicek ke dalam variabel
4. Lakukan pembagian 2 ke bilangan yang sudah dimasukkan ke variabel tersebut
5. Jika sisa bagi sama dengan 0, maka bilangan tersebut bilangan genap
6. Jika sisa bagi tidak sama dengan 0, maka bilangan tersebut bilangan ganjil 
6. Selesai



# Flowchart

## Menentukan Bilangan Ganjil/Genap

::: mermaid

flowchart TB

start((Mulai))
number[/Bilangan/]
pembagian[Bilangan / 2]
cek{% 2 = 0}
genap[/Genap/]
ganjil[/Ganjil/]
selesai([Selesai])

start --> number
number --> pembagian
pembagian --> cek
cek -. Ya .-> genap
cek -. Tidak .-> ganjil
ganjil --> selesai
genap --> selesai

:::