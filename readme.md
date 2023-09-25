# Latihan Individu 1 #

flowchart TD
```mermaid
    A([Mulai]) --> B{{jarak}}
    B --> C[/nilai jarak/]
    C --> D{Pemilihan Senjata}
    D -->|jarak <= 5 Meter| E[Equip Melee Weapon]
    D -->|jarak >= 5 Meter| F[Equip Ranged Weapon]
    E --> G([Selesai])
    F --> G
```

# Latihan Individu 2 #

flowchart TD
```mermaid
    A([Mulai]) --> B{{username, password}}
    B --> C[/username, password/]
    C --> D{Apakah username password sesuai?}
    D -->|Ya| E[Login Berhasil]
    D -->|Tidak| F[Login Gagal]
    E --> G([Selesai])
    F -->|input ulang username dan password|C
```
# Tugas Diskusi Kelompok #
Pertanyaan 1/
Q : Identifikasi sesuai project masing-masing fitur apa saja yang membutuhkan konsep pemilihan
A : password dan menu

Pertanyaan 2/
Q : Tentukan bentuk pemilihan yang digunakan, serta masing-masing kondisi yang dibutuhkan
A : password : if else, do while. menu : switch case

Pertanyaan 3/
Q : Buatlah algoritma dalam bentuk flowchart sesuai kebutuhan yang telah Anda identifikasi berdasarkan tugas No 1 dan 2
A : File pdf