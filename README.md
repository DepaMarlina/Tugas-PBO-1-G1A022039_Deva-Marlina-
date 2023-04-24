<<<perbedaan functional programming dan object oriented programming dalam bahasa pemrograman pyhon>>>
Functional programming dan object-oriented programming (OOP) adalah paradigma pemrograman yang berbeda dalam cara pendekatan untuk menyelesaikan suatu masalah. Berikut adalah perbedaan antara functional programming dan OOP dalam bahasa pemrograman Python:

1. Pendekatan Pemrograman

Functional Programming (FP): FP merupakan paradigma pemrograman yang berfokus pada fungsi. Dalam FP, program dibangun dengan membuat fungsi-fungsi yang memproses data input dan mengembalikan nilai output.

Object-Oriented Programming (OOP): OOP merupakan paradigma pemrograman yang berfokus pada objek. Dalam OOP, program dibangun dengan membuat objek-objek yang memiliki atribut dan perilaku tertentu.

2. Immutability

FP: Pada FP, data dianggap sebagai tidak berubah (immutable) dan setiap operasi yang dilakukan terhadap data mengembalikan nilai baru tanpa memodifikasi data asli.

OOP: Pada OOP, data dianggap sebagai mutable, dan perubahan dapat dilakukan langsung pada objek tersebut.

3. Inheritance

FP: Pada FP, tidak ada konsep inheritance (pewarisan) seperti yang ada di OOP.

OOP: Pada OOP, inheritance merupakan konsep penting, di mana kelas anak dapat mewarisi atribut dan perilaku dari kelas induk.

4. Polymorphism

FP: Pada FP, konsep polimorfisme (berbagai objek dapat memiliki perilaku yang sama) tidak digunakan secara eksplisit.

OOP: Pada OOP, konsep polimorfisme sangat penting, di mana objek-objek yang berbeda dapat memiliki perilaku yang sama melalui inheritance dan penggunaan method overriding dan overloading.

5. Fokus pada Pengolahan Data

FP: Pada FP, fokus utama adalah pada pengolahan data, di mana program dibangun dengan serangkaian fungsi yang menerima input dan mengembalikan output.

OOP: Pada OOP, fokus utama adalah pada objek, di mana program dibangun dengan membuat objek-objek yang memiliki atribut dan perilaku tertentu.

Kesimpulannya, perbedaan antara FP dan OOP dalam bahasa pemrograman Python terletak pada pendekatan pemrograman yang digunakan (fungsi vs objek), penggunaan imutabilitas (mutable vs immutable), inheritance, polimorfisme, dan fokus pada pengolahan data atau objek. Pilihan antara FP dan OOP tergantung pada karakteristik dan kebutuhan dari masalah yang ingin dipecahkan.


<<<contoh pengimplementasian dari oop>>>
Berikut adalah contoh pengimplementasian dari OOP (Object-Oriented Programming) menggunakan bahasa pemrograman Python:

# Membuat kelas "Mobil"

class Mobil:

    # Fungsi constructor

    def __init__(self, merk, model, tahun, harga):

        self.merk = merk

        self.model = model

        self.tahun = tahun

        self.harga = harga

    

    # Fungsi untuk menampilkan informasi mobil

    def info(self):

        print("Mobil:", self.merk, self.model)

        print("Tahun:", self.tahun)

        print("Harga:", self.harga)

# Membuat objek "mobil1" dari kelas "Mobil"

mobil1 = Mobil("Toyota", "Avanza", 2021, 200000000)

# Memanggil fungsi "info" dari objek "mobil1"

mobil1.info()


        
Pada contoh di atas, telah dibuat sebuah kelas Mobil yang memiliki atribut merk, model, tahun, dan harga. Kemudian, terdapat sebuah fungsi constructor __init__ yang digunakan untuk menginisialisasi nilai dari atribut-atribut tersebut ketika objek dari kelas Mobil dibuat.        
Selain itu, terdapat juga sebuah fungsi info yang digunakan untuk menampilkan informasi mobil seperti merk, model, tahun, dan harga. Fungsi info ini dapat dipanggil dari objek mobil1 yang telah dibuat sebelumnya.
Dengan menggunakan OOP, kita dapat dengan mudah membuat objek-objek yang memiliki atribut dan perilaku yang serupa. Hal ini dapat mempermudah dalam membuat program yang kompleks dan mudah untuk dipahami dan dipelihara.
