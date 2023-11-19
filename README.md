# Program Otomatis Mencocokkan Data Google Classroom dengan Database Kampus
Program Python Interpreter untuk mencocokkan nilai-nilai mahasiswa di Google Classroom dengan Database Kampus. Terdapat 3 buah file program ipynb:
<ol>
  <li>Fungsi <i>cocokkan_data_lama.ipynb</i> <br />
    Mencari email mahasiswa terbaru yang belum masuk ke Database Email Semester Sebelumnya setiap Angkatan. Jika di hasil akhir terdapat daftar email, masukkan email tersebut secara manual ke database file Excel tersebut.
  </li>
  <li>Fungsi <i>program_get_score.ipynb</i> <br />
    Mencocokkan Database (File Excel) dari kampus dengan file .csv dari google classroom
  </li>
  <li>Fungsi Program <i>concatenate_score</i>
  <ul>
    <li>Kasus perlu prgram ini: Mengajar di salah satu matakuliah, tetapi matakuliah tersebut ada dua kelas berbeda. Misalnya, mengajar matakuliah A di Kelas Pagi dan Kelas Malam</li>
    <li>Jalankan <i>program_get_score.ipynb</i> terlebih dahulu untuk mendapatkan nilai kedua kelas tersebut </li>
    <li>Output dari kedua <i>program_get_score.ipynb</i> tersebut akan menjadi input program <i>concatenate_score.ipynb</i></li>
  </ul> 
  </li>
</ol>
