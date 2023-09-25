# Latihan Individu 2 #

flowchart TD;
```mermaid
    A([Mulai]) --> B{{username, password}}
    B --> C[/username, password/]
    C --> D{Apakah username password sesuai?}
    D -->|Ya| E[Login Berhasil]
    D -->|Tidak| F[Login Gagal]
    E --> G([Selesai])
    F -->|input ulang username dan password|C
```