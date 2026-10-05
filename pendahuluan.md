# Jquery
Pengertian jQuery

jQuery adalah kumpulan fungsi-fungsi Javascript yang berguna untuk memudahkan penulisan kode Javascript.

jQuery mempunyai fitur seperti menyederhanakan document traversing, event handling, animating dan interaksi AJAX untuk pengembangan web secara cepat.

Sang creator jQuery adalah John Resig , beliau merupakan master javascript yang menciptakan sebuah library untuk mempermudah developer agar dapat membuat aplikasi javascript tanpa harus mengetik javascript dari awal.
Manfaat jQuery

    Menemukan elemen dalam dokumen HTML
    Mengubah konten HTML
    Mendengarkan apa yang dilakukan pengguna dan melakukan tindakan yang sesuai (event listener)
    Membuat animasi konten di halaman
    Berbicara melalui jaringan untuk mengambil konten baru. (AJAX)

Document Object Model (DOM)

Merupakan sebuah struktur seperti pohon yang dibuat oleh browser sehingga kita dapat dengan cepat menemukan elemen HTML menggunakan Javascript.
Image
Cara memanggil jQuery

Agar dapat menggunakan jQuery, kita harus memanggil file nya terlebih dahulu.

Contohnya kita bisa menautkan atau memuat link jQuery yang disediakan di website resminya seperti berikut ini :

<html>
	<head>
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js">
        </script>
	</head>
</html>

Cara lain adalah kita bisa mendownload file jquery.min.js tersebut kemudian kita simpan di dalam folder aplikasi kita, contoh pemanggilannya sebagai berikut ini :

<html>
	<head>
		<script src="assets/js/jquery.min.js">
        </script>
	</head>
</html>

Karena JavaScript (dan jQuery) dapat berjalan sebelum DOM "siap" , maka kita jalankan (listen) kode jQuery jika dokumen (DOM) sudah siap (ready).

$(document).ready(function())
{
    //kode jQuery
});

Tambahkan script di atas pada bagian awal halaman, hal ini untuk mengantisipasi agar jQuery tidak diload terlebih dahulu sebelum halaman siap.
Menggunakan jQuery

Kita akan coba praktek cara menggunakan jQuery, yang harus kita lakukan di awal adalah mendownload file jQuery melalui situs resminya yaitu https://jquery.com
Image

Pilih yang production, klik kanan lalu pilih save link as atau save link content as :
Image

Simpan pada folder aplikasi yang akan kita kerjakan, misal folder codepolitan-jquery.

Pada folder tersebut buat sebuah file index.html

Isi index.html dengan kode html seperti di bawah ini :

<!DOCTYPE html>
<html>
<title>Belajar jQuery</title>
<body>
	<!--load file jquery-->
    <script src="jquery-3.4.0.min.js"></script>
</body>
</html>

Setelah itu kita bisa tes dengan memanggilnya dari localhost.
Image

Hasil dari index.html merupakan halaman kosong, untuk mengetahui apakah jQuery sudah termuat atau belum, kita bisa melihatnya melalui console (Developer tool) lalu ketikkan simbol "$" , apabila jQuery sudah termuat maka akan menampilkan pesan "ƒ (e,t){return new k.fn.init(e,t)}"
Image

Demikian materi tentang pengenalan jQuery semoga mudah dipahami.