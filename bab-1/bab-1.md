**BAB I**

**PENDAHULUAN**

**1.1 Latar Belakang**

Dalam dunia professional, kita bekerja tidak terlepas dengan penggunaan
dokumen. seperti membuat dokumen, mencetak dokumen maupun menyimpan
dokumen baik dalam bentuk digital maupun dalam bentuk fisik.

Termasuk dalam dunia perkantoran, dokumen menjadi sangat penting dalam
kegiatan operasional sehari-hari seperti pada dokumen *reimbursement*
dimana saat ini masih banyak yang dilakukan secara input struk manual
baik dilakukan dengan aplikasi ataupun dokumen fisik.

Berdasarkan masalah tersebut, perlu adanya penerapan sistem dengan
mengandalkan salah satu teknik dari Pengolahan Citra Digital yaitu
*Optical Character Recognition* dan penerapannya harus di sesuaikan
dengan kebutuhan saat ini dan masa yang akan datang. Dengan itu peneliti
menggunakan judul **“PEMANFAATAN LIBARARY TESSERACT OPTICAL CHARACTER
RECOGNITION UNTUK MENCARI TOTAL BELANJA MELALUI STRUK MENGGUNAKAN METODE
KANBAN (STUDI KASUS: FITUR APLIKASI REIMBURSEMENT)”.** Sistem ini di
bangun dengan menggunakan Bahasa pemrograman Javascript dan menggunakan
kerangka untuk mengembangkan aplikasi yaitu NodeJS serta menggunakan
PostgreSQL sebagai DBMS (*Database Management System*).

**1.2 Identifikasi Masalah**

Berdasarkan latar belakang diatas, peneliti mengidentifikasi masalah
yang ada sebagai berikut :

1.  Dalam penggunaan dokumen *reimbursement* masih menggunakan dokumen
    fisik sehingga dokumen dapat hilang dang rusak.

2.  Input struk manual memakan waktu yang cukup lama dalam pembuatan
    dokumen *rimbursement* sehingga mengurangi efisiensi dalam
    operasional perkantoran.

**1.3 Rumusan Masalah**

Berdasarkan latar belakang masalah yang ditemukan diatas, maka yang
menjadi pokok masalah dalam penelitian yaitu :

1.  Bagaimana merancang sistem *API Service* dalam penerapan fitur
    *reimbursement* sehingga bisa di akses menggunakan aplikasi berbasis
    android maupun web.

2.  Bagaimana membuat aplikasi android untuk mengunggah foto struk yang
    akan dimasukan ke dalam dokumen reimbursement.

**1.4 Batasan Masalah**

Sistem *API Service* dan aplikasi android yang akan dibuat memiliki
batas-batas kegunaan berikut :

1.  Perancangan API Service untuk digunakan sebagai jalur komunikasi
    antar aplikasi yang digunakan pengguna dengan pemrosesan gambar
    menggunakan Bahasa pemrograman Javascript dengan kerangka untuk
    mengembangkan aplikasi yaitu NodeJS dan PostgreSQL.

2.  Pengolahan gambar untuk mengidentifikasi jumlah total belanja pada
    struk dilakukan menggunakan *tesseract.js.*

3.  Perancangan aplikasi android sebagai sarana mengunggah foto struk
    menggunakan kerangka pengembangan aplikasi berbahasa pemrograman
    Javascript yaitu React Native.

**1.5 Tujuan Penelitian**

Tujuan dari penelitian ini adalah sebagai berikut :

1.  Pembuatan *API Service* untuk mengemas fitur *reimbursement* sangat
    berguna, karena dapat digunakan secara fleksibel baik melalui
    aplikasi berbasis android ataupun web.

2.  Perancangan fitur *reimbursement* yang dilakukan secara sistem lebih
    efisien tanpa adanya dokumen fisik dan dapat di proses secepat
    mungkin.

**1.6 Manfaat Penelitian**

Manfaat dari penelitian ini adalah sebagai berikut :

1.  Dengan adanya penerapan *Optical Character Recognition* dalam fitur
    sistem *reimbursement* dapat mempermudah karyawan dalam mengajukan
    *reimburse* tanpa harus menulis jumlah total belanja dalam struk
    secara manual.

2.  Mengurangi penggunaan dokumen fisik dalam proses *reimbursement.*

3.  Memudahkan staff administrasi perkantoran dalam mengolah data
    *reimbursement* tanpa harus melihat dokumen fisik yang memakan
    tempat dalam ruangan.

**1.7 Metode Penelitian**

Dalam upaya memperoleh data serta informasi yang lebih luas dan akurat,

maka penulis melakukan penelitian dengan metode, diantaranya adalah :

**1.7.1 Pengumpula Data**

1.  Wawancara

Pengumpulan data yang dilakukan peneliti dalam menunjang kelengkapan
data melalui metode wawancara. Peneliti melakukan tanya jawab dengan
karyawan terkait dengan bagaimana proses *reimbursement* pada tempat
karyawan tersebut bekerja.

2.  Observasi

Metode yang digunakan dalam pengumpulan data juga melalui metode
observasi. Peneliti mencari data-data yang di butuhkan dalam pembuatan
fitur *reimbursement* yang memenuhi kebutuhan pengguna.

3.  Studi Literatur

Peneliti melakukan studi pustaka karena dalam penelitian ini tidak
terlepas dari buku, jurnal, dan artikel yang menjadi referensi untuk
membantu melengkapi data-data yang telah ada.

**1.7.2 Metode Pengembangan Sistem**

Pengembangan sistem ialah menyusun sistem yang baru untuk menggantikan
sistem yang lama secara keseluruhan atau untuk memperbaiki sistem yang
telah ada.

Metode *Kanban* memiliki beberapa tahapan yaitu :

1.  *Backlog* adalah tahap dimana mendaftarkan apa saja yang harus
    dilakukan untuk pembuatan aplikasi*.*

2.  *Work In Progress* adalah proses mengerjakan apa saja yang di
    daftarkan di *Backlog* baik itu merancang desain aplikasi ataupun
    penerjemahan desain ke dalam Bahasa pemrograman yang sesuai dengan
    kebutuhan.

3.  *Testing* adalah tahap pengujian perangkat lunak yang dikenbangkan,
    untuk mengcover kesalahan-kesalahan dan menjamin bahwa masukkan
    sesuai dengan hasil yang dibutuhkan.

4.  *Done* adalah tempat dimana tugas yang sudah di laksanakan dan
    berhasil melewati proses t*esting*. Pada tahap ini pula harus dijaga
    performa aplikasi agar berjalan dengan baik.

**1.8 Sistematika Penulisan**

Dalam penelitian ini terdapat beberapa bab materi pembahasan, yaitu
diantaranya :

**BAB I PENDAHULUAN**

> Bab ini membahas mengenai latar belakang, rumusan masalah, tujuan
> penulisan, manfaat penulisan, batasan masalah, serta metode penelitian
> yang digunakan.

**BAB II LANDASAN TEORI**

> Bab ini menjelaskan teori-teori yang menjadi acuan dalam penulisan
> laporan, yaitu mengenai tahapan perancangan aplikasi yang diperoleh
> dari beberapa buku litelatur, perpustakaan, dan internet.

**BAB III ANALISA DAN PERANCANGAN**

> Dalam bab ini akan di bahas menganai perancangan aplikasi layanan
> pengaduan masyarakat Desa Dangdang yang akan dibuat.

**BAB IV IMPLEMENTASI DAN PENGUJIAN SISTEM**

> Bab ini membahas tentang aplikasi yang dibuat serta contoh tampilan
> dari setiap aplikasi dan pengujian aplikasi yang sudah dibuat.

**BAB V PENUTUP**

> Dalam bab ini diuraikan kesimpulan dan saran dari hasil pemanfaatan
> library tesseract optical character recognition untuk mencari total
> belanja melalui struk
