# Silivent
Aplikasi web informasi lomba & event

## Nama kelompok dan anggota :
<table>
    <thead>
        <tr>
            <th></th>
            <th>Nama</th>
            <th>Nim</th>
            <th>Role</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>Muhammad Rayhan Adyatma</td>
            <td>G64180064</td>
            <td>Full-Stack</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Alvin Ferdiansyah</td>
            <td>G64180079</td>
            <td>Full-Stack</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Riyad Firdaus</td>
            <td>G641800899</td>
            <td>Full-Stack</td>
        </tr>
    </tbody>
</table>

## Latar belakang
Tingkat antusiasme mahasiswa IPB dalam mengikuti event dan lomba dapat dikatakan sangat tinggi. Namun, banyak kesulitan yang dialami mahasiswa dalam mencari informasi event, lomba, dan administrasi pembiayaan untuk mengikuti lomba yang diadakan oleh penyelenggara. Oleh karena itu kami ingin membuat aplikasi web untuk memudahkan mahasiswa dalam mencari informasi tersebut.

## Tujuan
1. Mempermudah mahasiswa IPB dalam mencari informasi lomba
2. Mempermudah mahasiswa IPB dalam mencari informasi event
3. Membuat wadah untuk panitia penyelenggara event untuk mempromosikan kegiatannya

## Ruang lingkup
### Minimum requirement
<table>
    <thead>
        <tr>
            <th></th>
            <th>Windows Requirement</th>
            <th>Mac Requirement</th>
            <th>Linux Requirement</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Operating System</td>
            <td>Windows 7 atau diatasnya</td>
            <td>Mac OS X Yosemite 10.10 or later</td>
            <td>64-bit Ubuntu 4.04+,Debian 8+,openSUSE 13.3+, or Fedora Linux 24+</td>
        </tr>
        <tr>
            <td>Processor</td>
            <td colspan=3 style="text-align:center">2.0 Ghz Processor</td>
        </tr>
        <tr>
            <td>Memory</td>
            <td colspan=3 style="text-align:center">2 GB minimum, 4 GB recommended</td>
        </tr>
        <tr>
            <td>Screen Resolution</td>
            <td colspan=3 style="text-align:center">800x600 atau diatasnya</td>
        </tr>
        <tr>
            <td>Internet Access</td>
            <td colspan=3 style="text-align:center">Diperlukan</td>
        </tr>
    </tbody>
</table>


### Software Design
- Software memiliki desain antarmuka yang ramah bagi pengguna
- Memiliki unsur ergonomis dan responsif
- Memiliki Keamanan yang baik

### Engineering Process
Software dibuat dengan proses Waterfall Model

## Deskripsi perangkat lunak
Silivent merupakan sebuah website pusat informasi berbagai perlombaan yang bisa diikuti oleh mahasiswa IPB. Para pelaksana event & lomba dapat menaruh informasi dan detail acara mereka di website ini, kemudian lomba-lomba tersebut diurutkan dan diorganisasikan sesuai dengan jenis dan kategorinya. User kemudian dapat mendaftarkan akun dan mengakses seluruh informasi & data perlombaan yang tersedia. User yang telah mendapatkan informasi secara detail, akan lebih dimudahkan untuk berfokus mencari kebutuhan selanjutnya seperti administrasi dan biaya perlombaan.

## Analisis user (user profile)
Target dari aplikasi kita adalah mahasiswa yang kesulitan dalam mencari informasi event & lomba. Kebanyakan mahasiswa memiliki kesulitan karena informasi event & lomba yang ada di internet tersebar dan tidak terpusat dalam satu platform.

## User story
- Sebagai seorang mahasiswa, saya ingin mencari informasi event & lomba dengan mudah tanpa harus membuka banyak website secara terpisah
- Sebagai seorang mahasiswa, saya ingin tahu informasi event & lomba secara lengkap dan utuh
- Sebagai seorang mahasiswa, saya ingin memiliki tempat mengumpulkan informasi event & lomba favorit saya.

## Use case diagram

![UseCaseDiagram](img/use_case.png)
## UseCaseDescription
![UseCaseDescription](img/UCD1.png)
![UseCaseDescription](img/UCD2.png)
![UseCaseDescription](img/UCD3.png)
![UseCaseDescription](img/UCD4.png)
![UseCaseDescription](img/UCD5.png)
![UseCaseDescription](img/UCD6.png)

## Gantt chart
![GanttChart](img/gantt_chart.png)

## ERD
![ERD](img/ERD.jpg)


# Hasil implementasi perangkat lunak

Berikut adalah hasil screenshoot dari fitur fitur yang ada pada aplikasi kami beserta sedikit penjelasan.

## USER

Terdapat 3 jenis User yang memiliki akses berbeda terhadap fitur di dalam aplikasi, yaitu sebagai berikut

1. Guest ( User yang tidak mendaftar ) <a href="Silivent/index.php">Link Code</a>

![Aplikasi](img/1.png)

    Guess hanya memiliki akses ke fitur lihat semua event/lomba, yang berisi list event/lomba yang tersedia.


2. Registered User ( User yang telah mendaftar ) <a href="Silivent/user/index.php">Link Code</a>

![Aplikasi](img/2.png)

    Registered User memiliki akses ke fitur lihat semua event/lomba, membuat dan submit event/lomba , melihat daftar event/lomba yang pernah dibuat, dan mengakses profile serta mengedit profile.


3. Admin <a href="Silivent/admin/index.php">Link Code</a>

![Aplikasi](img/3.png)

    Admin memiliki semua akses terhadap fitur, termasuk memverifikasi submitan registered user dan melakukan pengaturan terhadap semua event/lomba yang tersedia.


## FITUR

1. Home <a href="Silivent/index.php">Link Code</a>

Pada Fitur Home, terdapat arahan menuju fitur sesuai akses user, dan terdapat 3 Rekomendasi Event/Lomba Favorit pada home.

![Aplikasi](img/4.png)

![Aplikasi](img/5.png)
    Versi Zoom Out


2. Log In <a href="Silivent/logIn.php">Link Code</a>

![Aplikasi](img/10.png)

    Guess dapat Log In sebagai Registered User jika telah mendaftar. Admin perlu Log In terlebih dahulu sebelum mengakses semua fitur admin.


3. Sign Up <a href="Silivent/signUp.php">Link Code</a>

    Guess dapat melakukan registrasi, agar dapat login sebagai registered user.

![Aplikasi](img/11.png)


4. Profile <a href="Silivent/user/profile.php">Link Code</a>
    
    Saat Registered User telah Log In, pada pojok kanan atas terdapat Dropdown button yang berisi pintasan menuju fitur yang bisa diakses, salah satunya yaitu profile.

![Aplikasi](img/12.png)

![Aplikasi](img/15.png)
    Tampilan Profile User


5. Edit Profile <a href="Silivent/user/profile.php">Link Code</a>

    Registered User dapat melakukan edit profile untuk melakukan pengubahan data

![Aplikasi](img/16.png)


6. Lihat Event/Lomba <a href="Silivent/list.php">Link Code</a>

    Fitur ini berisi daftar semua event/lomba ataupun per kategori, terdapat bar yang berfungsi untuk menentukan apakah ingin menampilkan semua list Event/Lomba, atau hanya menampilkan kategori tertentu.

![Aplikasi](img/6.png)

![Aplikasi](img/7.png)
    Tampilan Zoom Out, Show All Event

![Aplikasi](img/8.png)
    Tampilan Event sesuai kategori tertentu

![Aplikasi](img/9.png)
    Tampilan Event sesuai kategori tertentu
    
![Aplikasi](img/detailevent.png)
    Tampilan detail Event (<a href="Silivent/detailLivent.php">Link Code</a>)


7. Submit Event/Lomba <a href="Silivent/user/profile.php">Link Code</a>

    Registered User dapat menambahkan dan submit Event sendiri melalui fitur ini

![Aplikasi](img/13.png)


8. Event Saya <a href="Silivent/user/tambahLivent.php">Link Code</a>

    Registered User dapat melihat list event/lomba yang pernah dibuat melalui akun tersebut.

![Aplikasi](img/14.png)


9. Verifikasi Event/Lomba <a href="Silivent/admin/verifikasiLivent.php">Link Code</a>

    Event yang telah disubmit registered user, harus diverifikasi oleh admin terlebih dahulu sebelum dapat ditampilkan.

![Aplikasi](img/17.png)


10. Pengaturan Semua Event/Lomba <a href="Silivent/admin/listLiventDiajukan.php">Link Code</a>

    Admin dapat melakukan pengaturan berupa Edit,Hapus, atau Melihat semua Event/Lomba yang ada secara bebas.

![Aplikasi](img/18.png)
