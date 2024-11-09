# PA-DDP Kelompok 10
Tema: Sistem Manajemen Rental Mobil (Rental Laju Sejahtera)
Penyimpanan dinamis: CSV
# Anggota Kelompok
1. Ahmad Dani (2409116074)
2. Dinathan Fahrezi (2409116050)
3. Nadila Putri (2409116052)

### Panduan pengguaan program
## Menu Login/Register akun dan Exit Program
![Screenshot 2024-11-09 191532](https://github.com/user-attachments/assets/61a9fc6c-179b-4b92-b725-3de9b3c566e5)

pada menu awal akan menampilkan 3 menu, yaitu Login, Register, dan Exit. untuk masuk ke menunya dengan cara mengetikkan menu(contoh : login)

## Menu Login
![image](https://github.com/user-attachments/assets/358d0c38-2b73-4101-8527-41cb40f0dfb6)

Selanjutnya kita akan masuk ke menu login, dan akan mencoba login dengan menggunakan username admin untuk masuk ke manu admin

## Menu Admin
![Screenshot 2024-11-09 190253](https://github.com/user-attachments/assets/4ef6d8d1-4e50-463b-9d94-7274a9a76fff)

Pada menu admin ada 8 opsi, yang pertama tambah mobil, lihat daftar mobil, hapus mobil, lihat transaksi yang aktif, edit mobil, lihat daftar user, tambah vouchert, dan logout. Kita akan coba masuk ke menu tambah mobil

## Menu Tambah Mobil
![Screenshot 2024-11-09 190308](https://github.com/user-attachments/assets/7ec15ab0-9ebb-430c-bf62-b8e57088ee2e)

Pada menu ini kita harus menginputkan 3 data, yang pertama nama mobil, yang kedu harga sewa, dan yang terakhir plat mobil. Input dapat berupa huruf lowercase saja karena nanti akan otomatis disesuaikan dengan programnya

## Menu Lihat Daftar Mobil
![Screenshot 2024-11-09 190424](https://github.com/user-attachments/assets/e6b9042d-8b18-4b70-a7a0-eaced598fc31)

Pertama kali masuk ke menu ini akan diberi 3 opsi, yang pertama untuk melakukan searching, yang kedua untuk melakukan sorting, dan yang ketiga akan kembali ke menu admin. Kita coba untuk fitur searchingnya

![Screenshot 2024-11-09 190507](https://github.com/user-attachments/assets/74937721-4984-4de4-8c5a-cd05d1f6b6b4)

Disini saya mencoba memasukkan keyword "set" dan muncul data yang mengandung kata "set" (Wuling Setrum). Selesai muncul keyword yang diketik maka akan muncul opsi di awal tadi. Lalu saya akan mencoba fitur untuk sorting harga

![Screenshot 2024-11-09 190521](https://github.com/user-attachments/assets/9ee0504e-6104-4c77-b37b-f25bbe7e26f0)

Lalu kita akan coba sorting dari yang paling murah lebih dahulu

![Screenshot 2024-11-09 190543](https://github.com/user-attachments/assets/4a7d8337-5028-4fb7-8737-9b57d0224f5e)

Gambar di atas adalah hasil sorting data dari harga yang termurah ke harga yang paling mahal

![Screenshot 2024-11-09 190602](https://github.com/user-attachments/assets/8e166c0b-0e02-43b7-a616-8577e1d74a26)

Gambar di atas adalah hasil sorting data dari harga yang termahal ke harga yang paling murah

## Menu Hapus Mobil

![Screenshot 2024-11-09 190650](https://github.com/user-attachments/assets/669fedfe-cfd2-4089-98d4-e09b8a6812dc)

Pada menu hapus mobil pertama tama akan ditampilkan tabel mobil yang tersedia pada database, lalu masukkan id mobil yang ingin dihapus

## Menu Edit Mobil

![Screenshot 2024-11-09 190830](https://github.com/user-attachments/assets/180a708a-fc93-48a0-a366-0c71351fc05f)

Pada menu edit pertama-tama akan menampilkan seluruh data yang ada pada CSV, lalu disuruh untuk memasukkan id mobil yang ingin diedit. Ketika id cocok dengan data yang ingin di edit. Maka selanjutnya akan diminta untuk memasukkan data baru sesuai yang diinginkan oleh user 

## Menu Lihat Transaksi Aktif

![Screenshot 2024-11-09 204444](https://github.com/user-attachments/assets/d470684b-e4e1-4c3f-8901-a3461cca9ba5)

Pada menu ini akan menampilkan data transaksi yang tersedia pada file CSV

## Menu Daftar User

![Screenshot 2024-11-09 190956](https://github.com/user-attachments/assets/903e5914-8ece-4154-933d-9133fec9836f)

Pada menu ini akan menampilkan semua user yang terdaftar pada database 

## Menu Tambah Voucher

![Screenshot 2024-11-09 191525](https://github.com/user-attachments/assets/17744393-69ef-4e21-9385-102a4d6fd5ef)

Pada menu ini akan disuruh untuk menambahkan nama voucher dan menambahkan jumlah dari voucher tersebut. kode voucher ini nanti akan digunakan pengguna untuk melakukan topup saldo

## Menu Logout

![Screenshot 2024-11-09 191532](https://github.com/user-attachments/assets/82c38d0e-8e38-4c49-817b-b9ba64308074)

Ketika memasukkan input 8 akan kembali ke menu awal


## Menu User
Selanjutnya kita akan mencobas login dengan menggunakan username dengan role user

![Screenshot 2024-11-09 192112](https://github.com/user-attachments/assets/0f38b7c2-4845-4e28-a36c-ec278b6d8405)

Pada menu user ada  6 menu, yaitu : rental, kembalikan mobil, lihat daftar mobil, lihat saldo, topup saldo, dan logout

## Menu Rental

![Screenshot 2024-11-09 192135](https://github.com/user-attachments/assets/b4f56d51-4ed6-4ec4-abd2-8f1462221a99)

Pada menu ini juga terdapat fitur search dan sorting juga sama seperti fitur pada list di menu admin tadi. Kita coba memasukkan query n

![Screenshot 2024-11-09 192203](https://github.com/user-attachments/assets/11fd2a98-31e1-4199-92a1-86a01eb4cb74)

Ketika sudah menemukan mobil yang dicari, maka akan diminta untuk memasukkan id mobil yang ingin dipinjam dan ingin meminjam berapa lama. Jika sudah maka akan menampilkan invoice dan menambahkan saldo admin sesuai dengan total transaksi
![Screenshot 2024-11-09 192253](https://github.com/user-attachments/assets/56104128-5a1b-4d89-a905-7c824bd88007)

## Menu Kembalikan Mobil

![Screenshot 2024-11-09 192337](https://github.com/user-attachments/assets/ea5a523e-fd1d-427b-887a-3a44abac1144)

Pada menu ini akan menampilkan mobil yang dipinjam oleh user dan akan disuruh memasukkan nama, nama mobil, dan no plat dari mobil yang dipinjam kemaren

## Menu Lihat Mobil

![Screenshot 2024-11-09 192435](https://github.com/user-attachments/assets/44d5e15a-5a25-4d2e-a70d-2a447900d23c)

menu ini juga sama seperti menu lihat mobil yang ada pada menu admin

## Menu Lihat Saldo

![Screenshot 2024-11-09 192508](https://github.com/user-attachments/assets/5afc0d23-f717-445c-a826-02b036ceee9e)

Pada menu ini akan melihatkan saldo yang dimiliki dari user

## Menu Tambah Saldo 

![Screenshot 2024-11-09 192551](https://github.com/user-attachments/assets/73dbf5a7-d4ea-4049-9159-5e2eaee7abeb)

Menu ini untuk menambahkan saldo user dengan cara memasukkan kode voucher yang tersedia pada database voucher. Jika kode voucher ada maka saldo user akan bertambah sesuai dengan nilai dari kode voucher

## Menu Register

![Screenshot 2024-11-09 192615](https://github.com/user-attachments/assets/db8e33d3-af7b-43bb-9506-294abac1794c)

Untuk melakukan register user perlu memasukkan username dan password, untuk username tidak boleh mengandung angka ataupun simbol. Dan untuk password, harus melakukan konfirmasi, jika konfirmasinya tidak sesuai maka akan diminta memasukkan ulang password lagi. Ketika sudah berhasil registrasi maka data user akan ditambahkan pada database CSV dan diminta untuk login

## Menu Exit

![image](https://github.com/user-attachments/assets/dc45c057-66c9-4553-9a89-5dd83c45a1cd)

Jika mengetikkan exit pada menu awal, maka program akan berhenti dan mengucapkan terimakasih
