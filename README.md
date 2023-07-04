# ClusteringTopikSkripsi
Proyek ini merupakan proyek skripsi saya untuk mengelompokkan judul-judul skripsi di Program Studi Sistem Informasi Universitas Pembangunan Nasional "Veteran" Jawa Timur. Proyek ini bertujuan untuk menganalisis dan menemukan kelompok/cluster judul skripsi untuk mengidentifikasi topik dan tema penelitian skripsi di jurusan Sistem Informasi.


# Berikut merupakan tata cara untuk menjalankan sistem baik untuk Python Notebook dan Website Clustering.

Untuk menjalankan Python Notebook maka lakukan langkah berikut:
1. Pastikan Anda telah memiliki atau telah menginstall Anaconda dan Jupyter Notebook. 
	Link download anaconda: https://www.anaconda.com/download
2. Extract Folder dan File ke dalam Local Disk Anda.
3. Pindahkan folder "web_dev" ke directory AnacondaPython\envs. Sesuaikan dengan directory Anda pada saat menginstall Anaconda.
   Misalnya:
			D:\Install\AnacondaPython\envs
5. Setelah itu, untuk menjalankan python maka buka aplikasi Jupyter Notebook dengan mencari pada kolom search pada Windows. Tunggu hingga Jupyter Notebook terbuka pada Browser Anda.
6. Setelah terbuka, buka file "Clustering Data Skripsi.ipynb" pada Jupyter Notebook. Kemudian pilih kernel yang akan digunakan yaitu web_dev setelah itu klik run all cells.
7. Selesai.

------------------------------------------------------------------------------------------------------------------------------------------
Untuk menjalankan Website Clustering maka lakukan langkah berikut:
1. Buka AnacondaPrompt. Anda bisa mencarinya pada kolom search pada Windows.
2. Setelah terbuka, ketikkan kode berikut.
	conda activate web_dev
3. Kemudian pada prompt lakukan perintah untuk pindah ke directory dimana Anda menyimpan folder "web". Misalnya:
      (web_dev) C:\Users\HP>D:

      (web_dev) D:\>cd D:\Skripsi\web
5. Setelah itu, ketik kode berikut.
      python wsgi.py
6. Kemudian copy URL yang telah diberikan ke browser Anda. Misalnya:
	    Running on http://127.0.0.1:3000
7. Tunggu hingga browser membuka Web tersebut dan terkadang memang membutuhkan waktu yang cukup lama.
8. Setelah Web berhasil terbuka, maka Anda dapat melihat halaman Home atau halaman utama yang berisikan data skripsi mahasiswa. 
9. Pada Web ini Anda juga dapat mengunggah file yang akan dikelompokkan dengan cara klik tombol "Choose File" kemudian unggah file yang akan dikelompokkan. Anda dapat menggunakan file yang sudah disediakan yaitu "TestExcel.xlsx" atau Anda juga dapat menggunakan file lainnya dan pastikan memiliki template yang sesuai dengan ketentuan (Anda dapat mengeceknya pada link template file pada Website). Kemudian tunggu hingga website menampilkan hasil clustering dan biasanya akan memerlukan proses yang cukup lama.
10. Selesai

------------------------------------------------------------------------------------------------------------------------------------------
Atau untuk versi lengkap dari AnacondaPrompt yang dilakukan kurang lebih sebagai berikut.

(base) C:\Users\HP>conda activate web_dev

(web_dev) C:\Users\HP>D:

(web_dev) D:\>cd D:\Skripsi\web

(web_dev) D:\Skripsi\web>python wsgi.py
 * Serving Flask app 'app'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:3000
Press CTRL+C to quit
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 113-865-781
	
