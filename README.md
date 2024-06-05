# Jarkom
1950-an-1960-an: Perkembangan Awal
1950-an: Konsep jaringan muncul dengan sistem komputer awal yang menggunakan pemrosesan batch.
1960: Ide packet switching, sebuah teknologi jaringan mendasar, diperkenalkan oleh Paul Baran dan Donald Davies secara independen.
1969: ARPANET
ARPANET: Jaringan Badan Proyek Penelitian Lanjutan, yang didanai oleh Departemen Pertahanan A.S., menjadi jaringan pertukaran paket operasional pertama dan pendahulu internet.
Koneksi Pertama: Pesan pertama dikirim dari UCLA ke Stanford Research Institute.
1970-an: Pertumbuhan Konsep Jaringan
Ethernet: Dikembangkan oleh Robert Metcalfe dan rekan-rekannya di Xerox PARC, Ethernet menjadi teknologi LAN yang dominan.
TCP/IP: Vint Cerf dan Bob Kahn mengembangkan Transmisi Control Protocol dan Internet Protocol (TCP/IP), yang menjadi landasan komunikasi internet modern.
1980-an: Ekspansi dan Standardisasi
1983: ARPANET mengadopsi TCP/IP, memungkinkan terciptanya jaringan yang saling berhubungan, atau internet.
Sistem Nama Domain (DNS): Diperkenalkan untuk menyederhanakan pengalamatan di internet dengan menggunakan nama domain yang dapat dibaca manusia, bukan alamat IP numerik.
1990-an: Era Internet
World Wide Web: Diciptakan oleh Tim Berners-Lee, World Wide Web mempopulerkan internet dengan menyediakan antarmuka yang ramah pengguna untuk mengakses informasi.
Komersialisasi: Internet dapat diakses secara luas oleh masyarakat, menyebabkan booming dot-com dan menjamurnya layanan dan aplikasi berbasis web.
2000-an-Sekarang: Kemajuan dan Keberadaan di mana-mana
Broadband: Meluasnya adopsi akses internet broadband secara signifikan meningkatkan kecepatan dan kegunaan internet.
Jaringan Nirkabel: Teknologi seperti Wi-Fi dan jaringan seluler memungkinkan akses internet seluler dan di mana-mana.
Internet of Things (IoT): Munculnya IoT yang menghubungkan perangkat sehari-hari ke internet, menciptakan dunia yang lebih saling terhubung.
Cloud Computing: Pertumbuhan layanan cloud memungkinkan sumber daya komputasi yang terukur dan fleksibel melalui internet.
![image](https://github.com/6ixa6/UTS-Strukdat/assets/149500578/8529597b-a5b3-4849-b976-16a822d35b24)
# Definisi Jarkom
Jaringan komputer adalah sistem yang terdiri dari beberapa komputer dan perangkat jaringan lainnya seperti router, switch, dan hub yang terhubung melalui kabel atau nirkabel untuk bertukar data dan sumber daya seperti printer, penyimpanan data, dan koneksi internet.
Jaringan pada komputer memungkinkan perangkat-perangkat untuk saling terkoneksi dan saling berkomunikasi.
Untuk menjalankan jaringan yang efektif dan efisien, dibutuhkan layanan-layanan yang dapat mengatur pembagian sumber daya.
Dibutuhkan aturan-aturan (protocols) yang mengatur komunikasi dan layanan-layanan secara umum untuk seluruh sistem jaringan.
![image](https://github.com/6ixa6/UTS-Strukdat/assets/149500578/e5d3732e-b35c-4f27-9525-6fcc2ffe931c)
# Jenis Jarkom
Berdasarkan arsitektur: 
Client/server
Peer-to-peer
Hybrid
Berdasarkan skala:
Local Area Network (LAN)
Metropolitan Area Network (MAN)
Wide Area Network (WAN)
Berdasarkan topologi:
Bus
Star
Ring, dll
![image](https://github.com/6ixa6/UTS-Strukdat/assets/149500578/82e191ff-0e32-45c2-8ef6-52107ecdf8c2)

# 
# GIT
repository : database yang menyimpan history/ riwayat perubahan
snapshot : potret kondisi file dan folder pada saat tertentu
commit : snapshot yang disimpan di repository
branch : serangkaian commit yang berkaitan sehingga kalau digambar seperti garis lurus berisi banyak commit. Satu repository bisa berisi banyak branch.
master : nama branch default yang diberikan git pada waktu kita membuat repository. Branch master ini tidak istimewa. Dia bisa dihapus dan direname sesuka hati.
head : ujung branch, commit terbaru di dalam branch
HEAD : head yang sedang aktif. Walaupun satu repository bisa memiliki banyak branch, tapi cuma satu yang aktif.
working folder : folder berisi file dan folder tempat kita bekerja. Biasanya working folder berisi banyak file source code untuk aplikasi yang sedang kita buat. Git memantau working folder ini, dan bisa mengetahui file dan folder mana yang sudah berbeda dari posisi commit terakhir. Perbedaan atau perubahan ini bisa disimpan menjadi commit baru, atau dikembalikan ke kondisi sebelum diubah.
staging area : snapshot dari working folder yang akan kita simpan pada saat commit. Ini adalah fitur unik Git yang tidak dimiliki version control lain. Dengan adanya staging area, kita bisa memilih perubahan mana yang akan di-commit dan mana yang tidak.
object store : ini adalah database tempat semua commit disimpan.
