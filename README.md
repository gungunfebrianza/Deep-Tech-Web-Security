# Deep-Tech Web Security

**Gun Gun Febrianza**

Event Dadakan 7 January 2021

------------

## <img src="assets/MemeWebSecurity.jpg" style="zoom:100%;" />

# Web Security

**Web Security** adalah salah **branch** dalam ilmu keamanan komputer. **Web Security** fokus mengkaji keamanan suatu **Web Application** mulai dari **front-end** hingga ke **back-end**. Kajian keamanan komputer merupakan area yang kompleks karena masing-masing **branch** menjadi **integral part** untuk yang satu dan lainnya.

<img src="assets/WebSecurityRoot.png" style="zoom:100%;" />

Sekup pembahasan **Web Security** sering kali meluas dengan area Ilmu Keamanan komputer yang lain seperti **Operating System Security**, **Application Server Security**, **Network Security**, **Social Engineering** dan hingga ke yang paling kompleks dan keren menggunakan **Artificial Intelligence**. 

Misal pada paper penelitian di bawah ini, penerapan **Machine Learning** sebagai salah satu cabang **Artificial Intelligence** untuk membaca PIN yang kita typing (misal) melalui ATM (Mesin Transaksi Keuangan). Metode yang digunakannya adalah **Acoustic Emanations** dengan tingkat akurasi untuk **recover** **PIN** mencapai 60%!

<img src="assets/ComplexComputerSecurity.JPG" style="zoom:100%;" />

Contoh di atas termasuk kedalam **emerging computer security**, setiap minggu, bulan dan tahun hal hal baru muncul baik itu inovasi untuk eksploitasi keamanan komputer atau improvisasi ilmu keamanan komputer itu sendiri.

## Cybercrime

Faktor yang mempelopori masalah web security menjadi masalah kontemporer, karena adanya kegiatan cybercrime. Where there is **commerce**, there is also the risk for **cybercrime**. [1]

**Cybercrime** adalah  kriminal (**crime**) di dunia nyata yang bertransformasi ke dalam dunia maya di era **the age of information**.  

## Cost of Cybercrime

Berdasarkan laporan Steve Morgan dalam technical reportnya yang berjudul Hackerpocalypse, estimasi cost kerugian yang ditimbulkan oleh cybercrime sampai tahun 2021 estimasinya bisa mencapai 6 Trilyun US Dollar. [2] 

<img src="assets/CostCybercrime.png" style="zoom:100%;" />

## Cybercrime Adagium

Berdasarkan laporan yang berjudul Global Economic Crime Survey, tahun 2016 hampir 1/3 perusahaan mengalami gangguan cybercrime. Meskipun rata-rata 61% seorang CEO concern dengan keadaan cyber security dalam perusahaannya. [3]

<img src="assets/CyberCrimeAdagium.PNG" style="zoom:100%;" />

# Website Defacement

Dalam Jurnal yang ditulis Marco dan Nik yang berjudul ***"Hacktivism dan Website Defacement : Motivation, Capabilities and Potential Threat."***, dikatakan bahwa **Hacktivism** dan **Website Defacement** seringkali memiliki keterkaitan. 

**Website Defacement** adalah serangan yang ditujukan untuk mengubah tampilan suatu **website**. 

**Website Defacement** terjadi ketika seorang **Attacker** sudah berada dalam **stage post exploitation**, **attacker** berhasil melakukan **privilege escalation** menembus **server**, mengubah tampilan halaman depan (**index**) pada **Web Server**.

Di bawah ini adalah salah satu **website** pemerintahan Tiongkok yang berhasil di **deface** oleh entitas yang perannya adalah seorang **hacktivist**, motivasi seorang **hacktivist** adalah permasalahan politik. [4] 

<img src="assets/ChinaWebsiteDefaced.jpg" style="zoom:100%;" />

Source : https://www.wsj.com/articles/BL-CJB-15573

## Website Defacement Damage

Website Defacement termasuk kedalam serangan berbahaya karena attacker memiliki probabilitas tinggi kontrol penuh terhadap remote server. Kerugian yang dapat ditimbulkan sudah saya high;ight apa saja yang paling prominent, diantaranya adalah :

1. Bocornya informasi customer dapat menimbulkan tuntutan hukum
2. Kekayaan Intelektual berpotensi menimbulkan kerugian bisnis
3. Data keuangan menyebar menuju kompetitor atau umum

<img src="assets/WebSecurityDamage.png" style="zoom:100%;" />

## Web Shell

**Web Shell** sering kali disebut dengan **Web Server Malware**, sebuah **malicious script** yang digunakan **attacker** agar **attacker** memiliki kontrol terhadap suatu **Remote Server**. Setiap **Web Shell** memiliki **payload** yang dapat digunakan **attacker** untuk melakukan **shell command execution**, **code execution**, **database enumeration**, dan **file management**.

**Web Shell** dapat ditulis menggunakan berbagai bahasa pemrograman, PHP paling menonjol karena banyak sekali penggunanya baik dari sisi pengembang **Web Application** ataupun **Attacker**. 

Potensi kerusakan dapat menimpa anda apapun **runtime engine** untuk **Web Server** yang anda gunakan, atau **Content Management System (CMS)** yang anda gunakan. Jika anda pengguna **CMS Wordpress**, kerentanan sistem dapat terjadi di sisi **CMS** itu sendiri atau melalui **plugins** yang anda gunakan.

**In Early Development**, mostly anti viruses tidak bisa mendeteksi **Web Shell** sebagai **Virus** karena **Web** **Shell** bukan **file executable**, **nowadays anti viruses** sudah memiliki kemampuan **heuristic** yang lebih **advance**. Seperti **Static Code Analysis** untuk mendeteksi **Web Shell**.

-------------

[1] RSA Whitepaper. 2016. *2016: Current State of Cybercrime*. Technical Report. RSA. 1–7.

[2] Steve Morgan. 2016. *Hackerpocalypse : A Cybercrime Revelation*. Technical Report. Cybersecurity Ventures. 1–24.

[3] PwC. 2016. *Global Economic Crime Survey 2016: Adjusting the Lens on Economic Crime*. Technical Report. PwC. 1–31.

[4] Hacktivism: A Short History. http://www.foreignpolicy.com/articles/2013/04/29/hacktivism [accessed on 13.06.13].

# Web Browser

Berbicara tentang Web Security, bisa dimulai dari aplikasi browser. Sebuah pintu tempat customer kita berinteraksi dengan aplikasi yang kita ciptakan. Tugas dari aplikasi browser adalah melakukan rendering halaman web agar dapat dimengerti oleh manusia.

# HTTP

# HTTP Headers

# HTTP Cookies

# Your Security State

# Threats

# DDoS Attack

# Bug Bounty

