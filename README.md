# UAS-Algoritma-dan-Struktur-Data
Ini adalah tugas (Graph) UAS Algoritma dan Struktur Data dari kami yang beranggotakan 
1. FAISHAL ANWAR HASYIM (32602300021)
2. FITRI NUR KHOLIFAH (32602300035)
3. SILVIYANA (32602300038)
4. NAUFAL FAIRUZAJ (32602300034)
5. Navila Syiva Dwi Maulidiana (32602300029)

CARA PENGGUNAAN APLIKASI YANG TELAH DIBUAT
CARA PENGGUNAAN APLIKASI DARI MASING2 APLIKASI YANG SUDAH KAMI BUAT

LINKED LIST
1.	User diminta untuk menambahkan data diri nasabah, input no rekening, nama, alamat dan saldo awal. 
2.	Ketika user ingin menghapus data diri maka sistem akan otomatis menampilkan : Belum ada nasabah dan data diri dihapus dengan menampilkan no rekening dari user. 
3.	Ketika user telah memasukkan data diri dengan benar maka sistem otomatis menyimpan data dari user tersebut. 
4.	Apabila user ingin mencari no rekening layar akan menampilkan untuk memasukkan no. rekening user dan menampilkan “Data yang Anda Cari Ditemukan” dengan menampilkan nama user dan juga rekening. Apabila, user sebelumnya menghapus data diri dan mencari data dirinya kembali maka layar menampilkan “Belum Ada Nasabah”
5.	User ingin melakukan transaksi maka user memasukkan no rekening dan memilih pilihan yang tersedia pada layar : Tarik tunai atau isi saldo. Jika user ingin mengisi saldo maka akan ditampilkan saldo awal dan user memasukkan saldo yang ingin di setor, layar menampilkan total saldo maka transaksi berhasil. 
Ketika user ingin Tarik tunai maka akan ditampilkan saldo awal dan user memasukkan jumlah uang yang ingin ditarik. Jika, saldo kurang layar akan menampilkan “Saldo anda kurang” jika transaksi berhasil layar akan menampilkan “Sisa saldo.” User salah memilih transaksi layar akan menampilkan “Data Tidak Ditemukan”
6.	User ingin mengecek apakah saldo masih ada. Maka user harus memasukkan no rekening dan layar akan menampilkan sisa saldo saat ini, jika user salah memasukkan no rekening layar akan menampilkan “Data Tidak Ditemukan.”
7.	Jika user salah memilih 1-4 maka layar akan menampilkan perintah pada layar “Input salah, silahkan input ulang!”


SORT
1.	User diminta tambahkan data pembeli lainnya sesuai kebutuhan
2.	Pindahkan elemen-elemen yang lebih besar satu posisi ke kanan
3.	Tambahkan input data pembeli lainnya sesuai kebutuhan
Masukkan nomor antrian pembeli ke-1: 3
Masukkan nomor antrian pembeli ke-2: 1
Masukkan nomor antrian pembeli ke-3: 7
Masukkan nomor antrian pembeli ke-4: 5
Masukkan nomor antrian pembeli ke-5: 2
Menampilkan antrian sebelum diurutkan
4.	Mengurutkan antrian
Antrian Pembeli Sebelum Diurutkan:
Nomor Antrian Pembeli: 2
Nomor Antrian Pembeli: 6
Nomor Antrian Pembeli: 1
Nomor Antrian Pembeli: 4
Nomor Antrian Pembeli: 9
5.	Menampilkan antrian setelah diurutkan
Nomor Antrian Pembeli: 1
Nomor Antrian Pembeli: 2
Nomor Antrian Pembeli: 4
Nomor Antrian Pembeli: 6
Nomor Antrian Pembeli: 9


TREE
1.	Pengguna membuka file C++ menggunakan aplikasi Visual Code Studio/ DevC++
2.	Pengguna dapat menambahkan node data yang diinginkan menggunakan fungsi addNode di int main dengan char abjad.
3.	Jika ingin menambahkan sebuah node, maka pengguna harus mengurutkan terlebih dahulu mulai dari akar, menuju kiri / kanan sesuai keinginan pengguna.
Dibawah ini adalah kumpulan addNode untuk pengurutan data tree:
    addNode(&akar, abjad = ' R ');
    addNode(&akar->kiri, abjad = ' A ');	
    addNode(&akar->kanan, abjad = ' E ');
    addNode(&akar->kiri->kiri, abjad = ' S ');
    addNode(&akar->kiri->kanan, abjad = ' F ');
    addNode(&akar->kanan->kanan, abjad = ' B '); 
    addNode(&akar->kanan->kanan->kiri, abjad = ' D ');
    addNode(&akar->kanan->kanan->kanan, abjad = ' C ');
    addNode(&akar->kiri->kiri->kiri, abjad = ' I ');
    addNode(&akar->kiri->kiri->kanan, abjad = ' T ');

4.	Fungsi dari printf("\t       R\n\t      / \\\n\t     A   E\n\t    / \\   \\\n\t   S   F   B\n\t  / \\     / \\\n\t I   T   D   C\n\n"); adalah untuk membuat tampilan gambar struktur data tree, dibuat secara manual dan terpisah dengan fungsi addNode, maka jika pengguna menambahkan node di addNode, tolong di ingat untuk menambahkannya juga di tampilan gambar struktur data tree.
5.	Semisal jika ingin membuat fungsi addNode dibagian S, Maka kamu membuatnya mulai dari akar (root) yakni node R, menuju ke node A (kiri), menuju ke node S (kiri). Jadi gambaran kode akan seperti ini:


addNode(&akar->kiri->kiri, abjad = ' S ');

6.	Jika ingin menambahkan node setelah node I, maka kamu harus mengurutkannya mulai dari akar menuju ke I, berarti mulai dari node R, A, S, hingga I, bila node I dibuat dengan addNode(&akar->kiri->kiri->kiri, abjad = ' I '); maka kamu membuat addNode lagi dengan urutan addNode(&akar->kiri->kiri->kiri,->(kiri/kanan), abjad = '  huruf apapun '); sesuai keinginanmu, mau menambahkannya di kiri atau di kanan.
7.	Preorder, Inorder, dan Postorder adalah pengurutan data tree
8.	Preorder mengurutkan dari node akar menuju ke kiri, kemudian kanan. 
9.	Inorder mengurutkan dari node paling kiri menuju akar, kemudian kanan.
10.	Postorder mengurutkan dari node paling kiri menuju kanan, kemudian akar.
11.	pengurutan data tree memprioritaskan urutannya sesuai fungsinya.
12.	Ketika program dijalankan, maka akan terlihat gambar struktur data tree beserta hasil dari pengurutan Preorder, Inorder, dan Postorder.



GRAPH
1. user diminta untuk memasukan banyak node yang ingin dibuat
2. user diminta untuk menginputkan jarak secara matriks misal: node nya adalah 3
        0 3 9
        1 0 5
        6 2 0
3. user diminta untuk menginputkan lokasi asal
4. user diminta untuk menginputkan lokasi tujuan
5. setelah user menginputkan data datanya maka proses dijalankan untuk mencari rute terpendek
6. user diberikan pilihan untuk mmengulang proses atau tidak (y untuk yes) dan (n untuk no)

LINK YOUTUBE
LINKED LIST
https://youtu.be/IE-fV8Rrp9I?si=3wMX6sruMrHbNs3t

SORT
https://youtu.be/k1_oR_cNFQ0?si=nIYkqBeX7-q7MMjX

TREE
https://youtu.be/kmBKjiDC_S8?si=9fuKPyTm7PBMNFMx

GRAPH
https://youtu.be/DOA1HLrxyuA?si=ItEDV29kl9VfFhet
