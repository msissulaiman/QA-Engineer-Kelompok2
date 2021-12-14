# QA-Engineer-Kelompok2

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

7. Berikutnya memasukkan akun testrail, langkah selanjutnya TestSuites semua modul doctor


Modul Article

1. Get All Article, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/articles?page=1&per_page=2 dengan memilih method GET --> run, akan terlihat tampilan semua article.
2. Add Article, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/articles dengan memilih method POST, kemudian menambahkan title, description, image, date_posted dan reference pada HTTP body --> text --> JSON --> run.
3. Get Article by id, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/articles/article_id dengan memilih method GET --> run, akan menampilkan article sesuai dengan id yang dimasukkan.
4. Get Comment by Article id, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/articles/:id/comments?page=1&per_page=10 dengan memilih method GET, masukkan id article pada URL kemudian mengubah page dan per_page dalam sebuah article.
5. Add Comment by Article id, https://alodokter-k2.herokuapp.com/api/v1/articles/:id/comments dengan memilih method POST, kemudian menambahkan owner, article_id dan content pada HTTP body --> text --> JSON dan masukkan article id pada URL tersebut.
6. Get Spesific comment by id and article id, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/articles/:article_id/comments/:id dengan memilih method GET, masukkan comment id dan article id pada URL tersebut.
7. Update Comment, masukan URL https://alodokter-k2.herokuapp.com/api/v1/articles/:article_id/comments/:id dengan memilih method PUT, kemudian menambahkan owner pada pada HTTP body --> text --> JSON dan masukkan article id dan comment id pada URL tersebut.
8. Delete Article, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/articles/:id dengan memilih method DELETE, kemudian masukkan article id pada URL tersebut yang ingin di hapus.
9. Delete Comment, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/articles/1/comments/:id dengan memilih method DELETE, kemudian masukkan comment id pada URL tersebut yang ingin di hapus. 
10. Get Article by title, masukkan URL https://alodokter-k2.herokuapp.com/api/v1/searcharticles/title dengan memilih method GET --> run, akan menampilkan article sesuai dengan title yang dimasukkan.
11. Setelah point 1 s/d 5 selesai, maka selanjutnya membuat test case pada masing-masing point 1 s/d 10.
12. Berikutnya memasukkan akun testrail, langkah selanjutnya TestSuites semua modul article
