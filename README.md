# lab-2-web
Langkah pertama adalah membuat struktur dasar HTML pada index.html seperti berikut 
![Screenshot (101)](https://github.com/user-attachments/assets/a8cc7f3c-dd78-40ef-b943-8c54af87958b)
ini menunjukkan tampilan dasar halaman HTML sebelum ditambahkan gaya CSS yang diterapkan.

Langkah 2: Menambahkan CSS Internal
Selanjutnya tambahkan CSS internal di dalam tag : 
![Screenshot (102)](https://github.com/user-attachments/assets/40523fe0-0da1-4960-89ba-0da3218f6817)
Tangkapan layar ini menunjukkan perubahan tampilan setelah CSS internal dan inline diterapkan, seperti perubahan warna teks dan tata letak.

Langkah 3: Menambahkan CSS Inline
CSS inline diterapkan langsung di elemen: 
![Screenshot (103)](https://github.com/user-attachments/assets/5576f23a-14df-462c-98ab-d7c924e39e18)
Di tangkapan layar ini, file CSS eksternal telah diterapkan, sehingga gaya pada navigasi dan elemen lainnya menjadi lebih terstruktur.

Langkah 4: Menambahkan CSS Eksternal
Buat file eksternal ( assets/css/style.css) dan hubungkan ke dokumen HTML: 
![Screenshot (104)](https://github.com/user-attachments/assets/7b30f22d-7444-428f-9e09-db6d19c34ab6)
Ini adalah hasil akhir setelah semua jenis CSS (internal, inline, dan eksternal) diterapkan, termasuk penggunaan selector ID, class, dan elemen.

Langkah 5: Menggunakan Selector CSS
Gunakan selector CSS seperti ID dan class:
![Screenshot (105)](https://github.com/user-attachments/assets/88cd8163-f157-4743-ab5b-cb142ba9108d)
Ini adalah hasil akhir setelah semua jenis CSS (internal, inline, dan eksternal) diterapkan, termasuk penggunaan selector ID, class, dan elemen.

Pertanyaan
1. Perbedaan Elemen Pemilih ( h1 {...}) vs. ID Pemilih ( #intro h1 {...}): h1 {...}: Ini adalah selector tag. Deklarasi ini akan mengaplikasikan aturan CSS ke semua elemen h1 yang ada di halaman HTML. #intro h1 {...}: Ini adalah selector gabungan yang lebih spesifik. Deklarasi ini hanya akan mengaplikasikan aturan CSS ke elemen h1 yang ada di dalam elemen dengan ID intro.
2. Urutan Prioritas CSS Internal, Eksternal, dan Inline: Ketika sebuah elemen memiliki CSS yang dideklarasikan secara internal, eksternal, dan inline untuk elemen yang sama, CSS inline memiliki prioritas tertinggi. Ini karena aturan spesifisitas CSS, di mana inline lebih spesifik dibandingkan deklarasi internal dan eksternal.
Urutan prioritas: Inline CSS (paling spesifik) Internal CSS (jika berada di dalam tag <style> di halaman yang sama) Eksternal CSS (dideklarasikan di file CSS terpisah) 3.ID Pemilih Prioritas dan Kelas: Jika elemen HTML memiliki ID dan class sekaligus, dan masing-masing selector terdapat deklarasi CSS, maka prioritasnya bergantung pada spesifisitas. Selector ID lebih spesifik dibandingkan class, sehingga deklarasi CSS pada ID akan mengesampingkan deklarasi pada class.
