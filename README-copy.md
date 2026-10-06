# Algoritma Deskriptif

## Memasak Mie Instan

::: mermaid

flowchart TB

start[Mulai]
step1[Siapkan Mie]
step2[Masak Air]
step3[Masukkan Mie]
step4[TUnggu Hingga Matang]
step5[Setelah matang mie dimasukkan ke piring]
step6[Masukkan bumbu dan di aduk]
step7[Mie siap disajikan]
step8[Selesai]

mulai --> nilai
nilai --> cek
cek --> lulus
cek --> tidak
tidak --> nilai
lulus --> selesai

:::