Modul User 

1. Create Users (Register), masukkan URL https://alodokter-api.herokuapp.com/register dengan memilih method POST, 
kemudian menambahkannya akun di HTTP body --> text --> JSON --> run.

2. Login Users, masukkan URL https://alodokter-api.herokuapp.com/auth/login dengan memilih method POST,
kemudian memasukkan email dan password di HTTP body --> text --> JSON --> run.

3. Get All Users, masukkan URL https://alodokter-api.herokuapp.com/users dengan memilih method GET, 
kemudian memasukkan Authorization masukkan username dan password dengan mengupdate HTTP Header sesuai dengan token saat login --> run.

4. Update User, memasukkan URL https://alodokter-api.herokuapp.com/users/astrin123 dengan memilih method PUT,
kemudian memasukkan username yang akan diupdate pada HTPP body --> run, status berubah menjadi status : update.

5. Delete User, memasukkan URL https://alodokter-api.herokuapp.com/users/astrin12 dengan memilih method DELETE --> run.

6. Setelah point 1 s/d 5 selesai, maka selanjutnya membuat test case pada masing-masing point 1 s/d 5.

7. Berikutnya memasukkan akun testrail, langkah selanjutnya TestSuites semua modul user.


Modul Doctor

1. Register, masukkan URL https://alodokter-api.herokuapp.com/doctors dengan memilih method POST, 
kemudian menambahkannya akun di HTTP body --> text --> JSON --> run.

2. Update Doctor, memasukkan URL https://alodokter-api.herokuapp.com/doctors/1234 dengan memilih method PUT,
kemudian memasukkan phone yang akan diupdate pada HTPP body --> run, status berubah menjadi status : update.

3. Get All Doctor, masukkan URL https://alodokter-api.herokuapp.com/doctors dengan memilih method GET --> run, akan terlihat tampilan semua dokter

4. Get by Name, masukkan URL https://alodokter-api.herokuapp.com/doctors/090899 dengan memilih method GET --> run, akan menampilkan data dokter dengan nip 090899.

5. Delete Doctor, masukkan URL https://alodokter-api.herokuapp.com/doctors/090899 dengan memilih method DELETE --> run.

6. Setelah point 1 s/d 5 selesai, maka selanjutnya membuat test case pada masing-masing point 1 s/d 5.

7. Berikutnya memasukkan akun testrail, langkah selanjutnya TestSuites semua modul doctor.

