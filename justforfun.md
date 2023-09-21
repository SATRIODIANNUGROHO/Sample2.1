# Flowchart #

```mermdaid
flowchart TD;
    A([Start])-->B{{int jari-jari, double keliling, luas}};
    B{{int jari-jari, double keliling, luas}}-->C[/input jari-jari/];
    C[/input jari-jari/]-->D(keliling = 2 * pi * r, luas = pi * r * r);
    D(keliling = 2 * pi * r, luas = pi * r * r)-->E[/tampilkan keliling, luas/];
    E[/output keliling, luas/]-->F([Selesai]);
```
