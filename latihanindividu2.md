# Latihan Individu 2 #

flowchart TD
```mermaid
    A([Mulai]) --> B{{username, password}}
    B --> C[/username, password/]
    C --> D{Apakah username password sesuai?}
    D --> E[Login Berhasil]
    D --> F[Login Gagal]
    E --> G([Selesai])
    F --> C
```