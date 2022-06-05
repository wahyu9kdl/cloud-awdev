# cloud awdev


[cloud.awdev.eu.org](https://cloud.awdev.eu.org)


[![crates.io](https://img.shields.io/crates/v/wrangler.svg)](https://crates.io/crates/wrangler) &nbsp;
[![npm](https://img.shields.io/npm/v/@cloudflare/wrangler.svg)](https://www.npmjs.com/package/@cloudflare/wrangler) &nbsp;
[![GitHub Actions - Test Status](https://github.com/cloudflare/wrangler/workflows/Tests/badge.svg)](https://github.com/cloudflare/wrangler/actions) &nbsp;
[![GitHub Actions - Linter Status](https://github.com/cloudflare/wrangler/workflows/Linters/badge.svg)](https://github.com/cloudflare/wrangler/actions) &nbsp;

# Apa itu cloud?

Kita semua pernah mendengar kata "cloud" ini. Namun bagi beberapa orang, istilah ini masih menjadi misteri. Pelajari mengapa "cloud" sangat penting bagi bisnis maupun pribadi.


## Cloud computing

Cloud computing itu apa dan bagaimana cara kerjanya?
Anda mungkin memiliki beberapa gambaran tentang apa itu cloud, dan layanan yang disediakannya, namun di sini kita akan melihat lebih dekat lagi bagaimana sebenarnya cara kerjanya dan mengapa cloud dalam waktu singkat telah menjadi hal yang sangat penting bagi kita. Ada kemungkinan meski Anda tidak tahu sama sekali apa itu layanan cloud computing, Anda mungkin suatu waktu pernah menggunakannya.

"Cloud" adalah singkatan dari "cloud computing" atau komputasi awan, dan istilah ini merujuk pada tugas dan layanan yang disediakan atau di-hosting di internet atas dasar bayar sekali pakai. Orang mungkin sudah lama bisa menyimpan, mengoperasikan, dan mengelola data lewat internet, namun cloud computing merupakan layanan berbayar yang melakukan semua ini dalam skala yang jauh lebih besar.

Pertama-tama, perlu dijelaskan bahwa cloud itu tidak semuanya virtual, dan meski file tidak disimpan secara langsung ke komputer Anda, file-file tersebut masih perlu dikaitkan dengan beberapa perangkat keras yang berada di suatu tempat di belahan dunia ini. Ketika Anda mengunggah sesuatu ke cloud, lewat layanan seperti Dropbox, file itu akan dikirim lewat internet ke server—sebuah server sungguhan yang berwujud. Penyedia layanan cloud memiliki ratusan dan ribuan server fisik, yang bersama-sama disebut sebagai "server farms" atau "ladang server" yang berlokasi di pusat data di seluruh dunia.

Jadi, dalam istilah yang paling sederhana, cloud merupakan sekumpulan server dan pusat data yang tersebar di seluruh dunia yang di dalamnya dapat menyimpan data kita.

Pada intinya, cloud adalah sebuah unit penyimpanan digital yang dapat menyimpan semua file Anda; perbedaannya adalah bahwa kalau pada unit penyimpanan Anda harus hadir secara fisik untuk mengakses file-file Anda, pada cloud Anda dapat mengaksesnya dari perangkat apa saja sepanjang perangkat itu memiliki koneksi ke internet.

Agar lebih jelas, "cloud" itu bukanlah sebuah entitas tunggal yang kasat mata. Ia sedikit lebih abstrak. "Cloud" pada dasarnya adalah sebuah perumpamaan dari internet itu sendiri. Saat Anda menyimpan file di cloud, berarti Anda menyimpannya secara online. Siapa saja yang memiliki sumber daya dan infrastruktur dapat meng-hosting cloud mereka sendiri, namun ini bukanlah sebuah tugas yang mudah, dan tentu tidak murah. Jadi kalau kita bicara tentang layanan cloud, kita berbicara tentang layanan tingkat tinggi yang ditawarkan oleh penyedia seperti Dropbox.

Agar memberi sudut pandang yang jelas, mari kita gunakan listrik sebagai contoh. Biaya memiliki generator pribadi di rumah Anda akan sangat mahal dan butuh pemeliharaan yang tinggi. Jadi, sebagai gantinya kita menggunakan layanan dari perusahaan listrik yang pada dasarnya mengoperasikan satu generator raksasa yang bisa diakses semua orang, dan kita semua hanya membayar apa yang kita pakai. Dalam arti yang serupa ini, akan jauh lebih efisien dan efektif secara biaya jika penyedia layanan cloud dapat meng-hosting dan menyimpan data Anda, alih-alih membuat infrastruktur sendiri.

## Fungsi

Fungsi lain di luar layanan penyimpanan cloud
Meski dalam pengertian paling sederhana cloud itu adalah solusi penyimpanan digital, cloud computing sebenarnya dapat dibagi menjadi tiga fungsi utama berbeda: model Infrastructure as a Service (IaaS) atau Infrastruktur sebagai Layanan, Platform as a Service (PaaS) atau Platform sebagai Layanan, dan Software as a Service (SaaS) atau Perangkat Lunak Sebagai Layanan.

Infrastructure as a Service (IaaS) adalah penyedia layanan awan yang menawarkan ruang server mereka untuk berbagai kebutuhan, mulai dari penyimpanan data sampai hosting web. Dalam hal ini, Anda akan tetap mengelola dan memelihara data, situs web, atau aplikasinya, sementara penyedia layanan awan hanya menyewakan sumber daya komputasinya kepada Anda untuk melakukannya.

Menggunakan Dropbox untuk penyimpanan file adalah sebuah contoh dari IaaS. Anda dapat mengakses, mengubah, dan menambahkan data sesuka hati, sementara Dropbox menyediakan server untuk menampungnya.

Contoh lainnya adalah Netflix, yang menggunakan IaaS untuk mengelola secara efektif kumpulan data dalam jumlah sangat besar yang diakses secara terus menerus oleh pelanggan dari seluruh dunia, sehingga kita dapat mengakses konten dengan cepat, tanpa kita sendiri harus mengunduh file apa pun. Netflix pun tidak harus membuat pusat data raksasa untuk menyimpan katalog kontennya yang terus bertambah.

Sementara itu, hampir setiap situs web yang Anda kunjungi itu dihosting di awan berkat model Iaas.

Platform as a Service (PaaS) serupa dengan IaaS, tetapi dengan sedikit lebih banyak kontrol oleh penyedia layanan awan. Di masa lalu, mengembangkan perangkat lunak dan mengujinya secara lokal merupakan pekerjaan yang mahal dari segi waktu, uang, dan ruang. PaaS menyediakan platform virtual untuk pengembangan dan pengujian backend, agar pemrogram memiliki kerangka kerja virtual yang dapat digunakan untuk mengembangkan perangkat lunak secara online, sedangkan semua server dan penyimpanannya masih ditangani oleh penyedia layanan. Jadi, alih-alih menghadapi risiko kerugian saat mengembangkan dan menguji secara langsung di perangkat, model Paas menawarkan solusi virtual.

Software as a Service (SaaS) merujuk pada setiap perangkat lunak yang dijalankan melalui awan. Contohnya adalah Dropbox Paper. Dengan aplikasi ini, Anda dapat membuat, mengedit, membagikan, dan berkolaborasi mengerjakan file teks secara online, dan Anda tidak perlu menginstal dan menyiapkan aplikasi yang akan menghabiskan ruang di perangkat Anda—karena cloud menyediakan itu semua. Anda hanya tinggal mengakses aplikasi saat dibutuhkan, dan mengerjakan file dari perangkat mana pun. Contoh lain dari SaaS adalah ekstensi seperti Grammarly, yang berjalan secara online, langsung di browser web.
Agar lebih mudah dipahami, model Iaas menawarkan kendali paling besar atas sumber daya Anda dan memberi admin degan layanan hosting dan penyimpanan. Model PaaS menawarkan kontrol lebih sedikit dan membutuhkan pengembang untuk mengembangkan, dan model Saas menawarkan kontrol paling sedikit dan disediakan kepada pengguna akhir untuk menggunakannya.

### Hybrid Cloud

Apa itu hybrid cloud?
Agak sedikit teknis, ada cloud publik, cloud pribadi, hybrid cloud, dan multicloud.

- Cloud publik

Cloud publik merujuk pada layanan cloud yang dapat digunakan setiap orang. Layanan Dropbox, misalnya, semuanya adalah layanan cloud publik. Siapa saja yang menggunakan Dropbox itu sama seperti menyewa sebagian dari ruang servernya, sehingga cloud publik dapat dilihat sebagai sebuah lingkungan bersama, seperti kantor besar namun semua orang memiliki meja dan lemarinya sendiri-sendiri.

- Cloud pribadi 

Cloud pribadi sangat berbeda, karena mesin virtual dan semua infrastruktur cloud akan dikhususkan bagi satu pelanggan. Anda masih dapat men-hosting semuanya melalui internet, namun server yang men-hosting data Anda akan menjadi milik Anda dan hanya diri Anda. Sebagian orang mungkin memilih menggunakan cloud pribadi untuk keamanan tambahan, sementara sebagian orang lainnya mungkin perlu menggunakan cloud pribadi untuk performa, karena server yang men-hosting data Anda tidak akan dibagi ke beberapa pelanggan, dan model ini dapat memberi semua kuasa pemrosesannya untuk kebutuhan Anda.

Cloud pribadi, tidak seperti cloud publik, juga memberi kontrol penuh kepada pelanggan mengenai cara server dikelola, diamankan, dan dicadangkan. Meski kebanyakan orang kemungkinan besar menggunakan cloud publik, cloud pribadi pasti lebih memilih mereka yang menangani data besar, yang berukuran sampai petabita.

- Hybrid cloud 

Hybrid cloud memanfaatkan server internal dan cloud publik, agar Anda dapat menyimpan dokumen lebih besar atau pribadi di cloud pribadi, namun tetap menyimpan yang lainnya di cloud publik.

- Multicloud

Multicloud adalah ketika sebuah bisnis menggunakan beberapa cloud publik yang berbeda dan tidak menggunakan dari cloud pribadi dan publik seperti hybrid. Ini pada umumnya terjadi karena layanan cloud yang berbeda akan menawarkan layanan berbeda dan satu bisnis mungkin membutuhkan semuanya.

### Manfaat cloud bagi bisnis

Dalam hal bisnis, manfaat cloud computing bisa lebih dari sekadar solusi penyimpanan sederhana. Cloud computing telah menjadi penggerak esensial dari produktivitas, efisiensi, pertumbuhan, dan pengorganisasian tempat kerja modern. Beberapa manfaat cloud computing bagi bisnis adalah:

- Biaya: Melakukan semuanya di perangkat Anda sendiri bisa jadi sangat mahal. Dengan layanan awan, tidak lagi perlu mengelola sistem dan peralatan TI di lokasi Anda sendiri. Sebagai layanan yang dibayar sesuai penggunaan, komputasi awan bukan hanya akan banyak mengurangi biaya perangkat keras, tetapi juga biaya sumber daya manusia dan penggunaan listrik. Selain itu, berkurangnya waktu yang dihabiskan untuk mengatasi masalah TI akan memberi lebih banyak waktu untuk berfokus pada tujuan Anda.
- Pemulihan bencana: Mencadangkan semua file dan data penting Anda ke awan memberi perlindungan ekstra yang sangat penting. Anda menghadapi risiko yang besar jika menyimpan semuanya di satu tempat saja—peristiwa bencana alam, pemadaman listrik tiba-tiba, hingga serangan malware bisa membuat Anda kehilangan semuanya dalam waktu singkat. Oleh karena itu, penyimpanan awan memberikan layanan yang sangat penting dengan mencadangkan data Anda di beberapa server di berbagai lokasi.
- Perlindungan dan keamanan data: Terlepas dari apa yang diyakini beberapa orang, layanan komputasi awan memberikan keamanan awan yang sangat baik untuk data pribadi Anda. Anda mungkin menganggap bahwa menyimpan semua data di tempat yang bisa Anda lihat akan lebih aman, tetapi bayangkanlah penyimpanan awan itu seperti brankas di bank. Penyedia layanan awan akan memprioritaskan keamanan dan perlindungan data Anda yang akan dienkripsi. Dalam banyak kasus, Anda masih dapat menentukan pengaturan keamanan penyimpanan awan Anda sendiri. Sama seperti brankas di bank yang dirancang sebagai cara teraman untuk menyimpan barang berharga, penyimpanan awan dirancang menjadi cara teraman untuk menyimpan data.
- Skalabilitas: Komputasi awan menawarkan fleksibilitas ekstra kepada bisnis untuk berkembang, atau dalam beberapa kasus untuk melakukan perampingan. Semakin besar bisnis Anda, semakin besar pula ruang, waktu, dan uang yang dibutuhkan untuk menjalankannya. Dapat menggunakan cloud sesuai kebutuhan dan saat dibutuhkan akan menyediakan lingkungan virtual yang memfasilitasi pertumbuhan ini. Sebaliknya, ketika bisnis mengalami penurunan, Anda tahu bahwa Anda tidak perlu membayar peralatan atau sumber daya yang tidak lagi dibutuhkan, karena dengan layanan komputasi awan Anda hanya membayar sesuai penggunaan.
- Fleksibilitas: Setelah semuanya yang disimpan dan dijalankan lewat awan, maka Anda bisa leluasa bekerja dari mana pun di seluruh dunia. Seiring dengan konsep tempat kerja tradisional yang terus berkembang dengan cepat, komputasi awan memiliki peran yang sangat fundamental agar perusahaan dapat berjalan secara virtual. Komputasi awan juga memfasilitasi kemampuan mengakses dan mengerjakan file dan data dari perangkat seluler, yang semakin penting.
- Kolaborasi: Demikian juga, bisa menyimpan file di awan serta membuat dan mengeditnya di awan mendorong kolaborasi yang lebih efisien. Dengan komputasi awan, Anda dapat memiliki sebuah tim beranggotakan sepuluh orang yang mengerjakan dokumen yang sama dari lokasi berbeda, sehingga manajemen organisasi dan sumber daya di dalam tim menjadi lebih mudah.
Kelebihan cloud computing untuk penggunaan pribadi
Di luar penggunaan untuk kantor, ada banyak cara anda dapat memperoleh manfaat dari penggunaan solusi cloud di rumah. Kelebihan paling jelas tentu saja adalah ruang yang akan Anda hemat. Jika saat ini Anda belum memanfaatkan penyimpanan cloud, sebagian besar file Anda mungkin disimpan di komputer atau smartphone. Jika Anda kehabisan ruang di perangkat itu, Anda dapat memilih hard disk eksternal, dan jika itu pun juga akhirnya penuh, Anda akan membeli hard disk eksternal kedua, dan seterusnya. Tiba-tiba, semuanya menjadi lebih rumit ketika Anda harus mencari dokumen lama yang sangat Anda butuhkan.

Menyimpan semua file Anda di satu tempat virtual, yang sama sekali tidak menghabiskan ruang pribadi Anda akan membantu menata dan mengontrol semua yang Anda simpan, sembari menghemat uang karena tidak perlu memberi perangkat keras. Performa perangkat Anda juga akan meningkat jika banyak file Anda dipindahkan ke cloud.

Sementara itu, perangkat lunak ramah pengguna berbasis cloud seperti Dropbox Paper—tidak seperti aplikasi yang perlu diunduh dan diinstal—juga akan menghemat banyak ruang dan menjaga semuanya tetap tertata dengan baik. Banyak dari perangkat lunak ini yang dapat digunakan pada aplikasi mobile atau web, sehingga memakai perangkat lunak berbasis cloud berarti bahwa Anda dapat bekerja dan berkreasi dari perangkat mana saja—dari mana saja.

Berbagi dengan orang yang Anda sayangi juga akan jauh lebih mudah, sehingga misalnya Anda bisa menyiapkan album foto kolaboratif yang bisa diakses oleh siapa saja di keluarga Anda.

### Manfaat cloud computing


Manfaat cloud computing terbukti entah Anda menggunakannya di rumah atau di tempat kerja: cloud dapat meningkatkan produktivitas, meningkatkan pengorganisasian, meningkatkan kolaborasi, dan mengurangi biaya—sembari menjaga data Anda tetap aman dan terlindungi.
