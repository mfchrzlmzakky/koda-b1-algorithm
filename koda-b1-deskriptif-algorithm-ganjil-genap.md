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