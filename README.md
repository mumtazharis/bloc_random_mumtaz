# bloc_random_mumtaz

Soal 13\
Praktikum ini bertujuan untuk memahami dan menerapkan pola BLoC (Business Logic Component). Pola BLoC berfungsi untuk memisahkan logika dari antarmuka pengguna, sehingga aplikasi menjadi lebih terorganisir dan mudah dikembangkan. Pada praktikum ini, logika untuk menghasilkan angka acak diimplementasikan dalam kelas RandomNumberBloc, sedangkan pengelolaan antarmuka dilakukan pada file random_screen.dart.
Penerapan pola BLoC terlihat dari bagaimana logika dan antarmuka saling berinteraksi menggunakan stream. Saat tombol di antarmuka ditekan, sinyal event dikirimkan ke BLoC melalui metode generateRandom. BLoC kemudian memproses sinyal tersebut, menghasilkan angka acak, dan mengirimkan hasilnya kembali ke antarmuka melalui stream. Antarmuka memanfaatkan StreamBuilder untuk mendengarkan data dari BLoC dan secara otomatis memperbarui tampilan berdasarkan data yang diterima.
![alt text](images/soal13.gif)