## Janji
Saya Raisyad Jullfikar NIM 2106238 mengerjakan Latihan 1 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Tugas latihan 1 DPBO 2023
Buatlah program berbasis OOP menggunakan bahasa pemrograman C++, Java, Python, dan PHP yang menampilkan informasi daftar mahasiswa (sekumpulan objek mahasiswa) dan memiliki fitur menambah, mengubah, dan menghapus data. Setiap mahasiswa memiliki data nama, NIM, program studi, fakultas, dan foto profil (khusus bahasa PHP).

# Desain Program
Program yang saya buat menggunakan 2 class, yaitu :
1. class Mahasiswa -> Set and Getter Data for Mahasiswa
2. class Crud -> Created Process of CRUD for Data of Object Mahasiswa

Pada class 'Mahasiswa', terdapat attr - attr antara lain :
* **Name**     -> Berisi value name mhs,     'String'
* **Nim**      -> Berisi value nim mhs,      'String'
* **Jurusan**  -> Berisi value jurusan mhs,  'String'
* **Fakultas** -> Berisi value fakultas mhs, 'String'
* **PathImg**  -> Berisi value path img mhs, 'String' (PHP)

Tiap attribut diatas mempunyai setter dan getternya masing-masing pada class 'Mahasiswa'.

Pada class 'Crud' juga sama, namun bedanya hanya digunakan untuk pemrosesan data seperti 'Create', 'Read', 'Update' and 'Delete' serta pada class ini mempunyai 4 method, diantaranya :
* **Create**     -> untuk menambahkan data mhs
* **Read**       -> untuk menampilkan data mhs
* **Update**     -> untuk mengubah data mhs
* **Delete**     -> untuk menghapus data mhs


# Alur Program
Alur program pada code setiap bahasa yang saya buat kurang lebih sama, kecuali pada bahasa PHP yang mana inputan serta proses dilakukan secara hardcode. Kemudian pada program selain PHP, tampilannya berupa menu.

Pertama - tama, ketika menjalankan program 'Java, 'C++' dan 'Python', pengguna dapat melihat/memilih menu 1 - 4 untuk menjalankan sebuah perintah yang mana sebagai berikut :

1. Jika user memilih menu 1, maka user diharuskan menginputkan beberapa data 'Nim', 'nama', 'jurusan', dan 'fakultas'. Pada penginputan data, terdapat error handling yang mana, ketika user menginputkan data dan data tersebut sudah ada dalam data terinput, maka data yang user inputkan tidak akan termasukkan kedalam list.

2. Jika user memilih menu 2, maka user diminta untuk menginputkan 'NIM' yang akan diubah, ketika nim yang dituju terdapat data, maka user disuguhkan menu kembali yang mana
- 1. Mengubah Nama
- 2. Mengubah Jurusan
- 3. Mengubah Fakultas
- 4. Mengubah keseluruhan data

3. Jika user memilih menu 3, maka user diminta untuk menginputkan 'NIM' yang akan didelete/dihapus. Jika data yang dituju terdapat pada list, maka data dengan NIM tersebut akan terhapus.

4. Jika user memilih menu 4, maka user akan diberikan tampilan data - data mahasiswa yang telah diinputkan sebelumnya.

5. Jika user memilih selain ke - 4 menu diatas, maka program yang dijalankan akan berhenti.

# Dokumentasi
