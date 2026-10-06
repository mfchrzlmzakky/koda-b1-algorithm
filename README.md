::: mermaid

flowchart TB

mulai[Start]
nilai[Nilai]
cek{">=75"}
lulus[Lulus]
tidak[Tidak Lulus]
selesai((End))

mulai --> nilai
nilai --> cek
cek --> lulus
cek --> tidak
tidak --> nilai
lulus --> selesai

:::
