![image](https://github.com/user-attachments/assets/2b3e1413-0a44-4bd9-95e0-ea5dc008ac34)

STM8 adalah keluarga mikrokontroler 8-bit yang dikembangkan oleh STMicroelectronics. Mikrokontroler ini dirancang untuk aplikasi tertanam (embedded systems) dengan konsumsi daya rendah, performa tinggi, dan harga yang terjangkau. STM8 banyak digunakan dalam perangkat elektronik rumah tangga, sistem otomasi industri, sensor pintar, dan proyek DIY (Do It Yourself).                  


Spesifikasi Utama STM8 :

Mikrokontroler STM8 adalah mikrokontroler 8-bit dari STMicroelectronics dengan kecepatan hingga 24 MHz, memori Flash 4 KB - 128 KB, RAM 1 KB - 6 KB, dan EEPROM 128B - 2 KB. Mendukung GPIO, ADC 10-bit, PWM, serta komunikasi UART, SPI, dan I2C. Beroperasi pada tegangan 2.95V - 5.5V dengan fitur hemat daya dan tersedia dalam varian STM8S (standar), STM8L (hemat daya), dan STM8AF (otomotif).


Komponen Utama Unit Kontrol:

Unit kontrol dengan mikrokontroler STM8 terdiri dari beberapa komponen utama, termasuk mikrokontroler STM8 sebagai pusat pemrosesan, regulator tegangan untuk menstabilkan daya, serta oscillator/kristal sebagai sumber clock. Selain itu, terdapat memori EEPROM/Flash untuk penyimpanan data, sensor seperti LDR atau DHT11 untuk membaca kondisi lingkungan, serta driver output (relay, MOSFET, atau transistor) untuk mengontrol perangkat seperti lampu atau motor. Sistem ini juga dilengkapi dengan komunikasi serial (UART, SPI, I2C) untuk berinteraksi dengan modul eksternal, serta tombol dan LED indikator untuk input manual dan tampilan status operasi.


Cara Kerja Unit Kontrol:

Unit kontrol berbasis mikrokontroler STM8 bekerja dengan membaca input dari sensor atau tombol, memproses data sesuai dengan program yang telah diprogram, lalu mengontrol output seperti lampu, motor, atau buzzer. Pertama, regulator tegangan menstabilkan daya yang masuk agar sesuai dengan kebutuhan STM8. Kemudian, sensor atau modul komunikasi (UART, SPI, I2C) mengirimkan data ke mikrokontroler, yang akan memprosesnya berdasarkan algoritma yang ditanamkan dalam memori Flash. Setelah itu, hasil pemrosesan digunakan untuk mengaktifkan driver output seperti relay atau MOSFET untuk mengendalikan perangkat eksternal. Selama operasi, LED indikator dan tombol dapat digunakan untuk memantau serta mengontrol sistem secara manual.




1.Mulai

2.Inisialisasi Sistem (STM8, Sensor, dll)

3.Baca Input (Sensor/Tombol)

4.Proses Data (Sesuai Program)

5.Keputusan? (Sesuai Kondisi)

Jika Ya, lanjut ke Aktifkan Output

Jika Tidak, kembali ke Baca Input

6.Aktifkan Output (Relay/Motor/LED)

7.Tampilkan Status (LED/Display)

8.Ulangi Proses atau Berhenti


Kesimpulan:

Mikrokontroler STM8 adalah pilihan yang sangat baik untuk proyek embedded system yang membutuhkan biaya rendah, konsumsi daya hemat, dan fitur lengkap. Dengan berbagai model seperti STM8S (standar), STM8L (hemat daya), dan STM8AF (otomotif), STM8 cocok untuk berbagai aplikasi mulai dari elektronik ru IoT.
