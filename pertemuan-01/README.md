# pertemuan-01
1. kesinambungan PWD–DPW–DPWL;
    jawaban:intinya urutan belajar. PWD itu dasar banget, baru html css js. DPW udah mulai php sama database, bikin crud sederhana tapi kodingan masih campur. Nah DPWL itu lanjutan DPW, kodingan yang berantakan tadi dirapiin pake MVC biar ga pusing.

2. perbedaan PHP terstruktur dan MVC;
    jawaban:kalo terstruktur (DPW) itu semua jadi satu file, html, php, sql campur aduk. gampang di awal tapi kalo udah banyak file jadi susah nyarinya.
kalo MVC (DPWL) itu dipisah-pisah. jadi lebih rapi, mau benerin tampilan ya buka view aja, mau benerin database ya buka model aja.

3. fungsi Model, View, dan Controller;
    jawaban:Model = bagian yang ngurus database, isinya query semua. misal insert, delete, select.
View = bagian yang ngurus tampilan, isinya html doang buat diliat user.
Controller = jembatannya, dia yang ngatur. misal user klik hapus, controller yang nyuruh model buat hapus.

4. alur request–response MVC;
    jawaban:user buka link -> masuk ke controller dulu -> controller manggil model buat ambil/hapus data di db -> model ngasih data balik ke controller -> controller ngasih data ke view -> view nampilin ke user. gitu aja alurnya muter.

5. pemetaan satu atau beberapa bagian/fitur aplikasi DPW ke Model, Controller, dan View disertai alasan; dan
    jawaban:- yang `select _ from siswa` itu masuk Model, soalnya kan query database. alasannya biar query ga berantakan di html.
- yang nampilin tabel siswa itu masuk View, soalnya cuma buat nampilin aja.
- yang proses pas klik tombol tambah/hapus itu masuk Controller, soalnya dia yang ngatur logika mau diapain datanya.

_kamu ganti ya jadi sesuai aplikasi kamu, jangan data siswa kalo aplikasi kamu kasir*

*

6. kesimpulan P1.
    jawaban:jadi di P1 ini kita belajar kalau MVC itu cara buat merapikan kode dari DPW yang sebelumnya masih berantakan. dengan dipisah jadi 3 bagian, aplikasi jadi lebih gampang dibenerin dan dikembangin lagi kedepannya.Udah, ini kalau kamu tulis tangan udah aman banget. Jangan lupa ganti contoh aplikasinya biar beda sama teman lain.