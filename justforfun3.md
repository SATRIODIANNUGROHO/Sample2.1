# Flowchart #

```mermaid
graph TD;
    A([Start])-->B{{int harga, jumlah, double diskon = 0.1, total, bayar, jumlah diskon}};
    B{{int harga, jumlah, double diskon = 0.1, total, bayar, jumlah diskon}}-->C[/harga, jumlah/];
    C[/harga, jumlah/]-->D(total = harga * jumlah);
    D(total = harga * jumlah)-->E(jumlah diskon = total * diskon);
    E(jumlah diskon = total * diskon)-->F(bayar = total - jumlah diskon);
    F(bayar = total - jumlah diskon)-->G[/tampilkan jumlah diskon, bayar/];
    G[/tampilkan jumlah diskon, bayar/]-->H([Selesai]);
```
