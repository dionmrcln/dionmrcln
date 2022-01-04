# Program Sederhana Python Perulangan

Setelah saya posting "Labspy02", sekarang saya ingin memposting cara membuat program sederhana. Yang di butuhkan for dan while.

Struktur Algoritma Latihan01

    1.Mulai
    2.Tampilkan n bilangan acak yang lebih kecil dari 0.5
    3.Nilai n diisi pada saat runtime
    4.Anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya.
    5.Gunakan fungsi random() yang dapat diimport terlebih dahulu.
    6.Selesai

Step pada source code latihan01

    import random
    jumlah = int (input("Masukkan jumlah n:"))
    for i in range(jumlah):
    i=random.uniform(0.0,0.5)
    print("Data Ke:", i) 
    print("Selesai")

Screenshoot Code latihan01

![Screenshot (65)](https://user-images.githubusercontent.com/53388439/68937324-c059f600-07ce-11ea-8916-016bc6149111.png)

Struktur Algoritma Latihan 02

    1.Mulai
    2.Inisiasi bil1,bil2,bil3 sebagai integer.
    3.Baca bil1.
    4.Baca bil2.
    5.Baca bil3.
    6Jika bil1 > bil2 dan bil1 > bil3 maka kerjakan langkah 8, selain itu
    7.Jika bil2 > bil1 dan bil2 > bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10.
    8.Cetak “Bilangan Terbesar Bilangan Pertama”.
    9.Cetak “Bilangan Terbesar Bilangan Kedua”.
    10.Cetak “Bilangan Terbesar Bilangan Ketiga”.
    11.Selesai

Step pada source code latihan02

print ('program untuk menentukan bilangan terbesar dan terkecil')

def pengulangan():

    print ('masukkan 3 bilangan yang diinginkan!')
    a=int(input('bilangan1 = '))
    b=int(input('bilangan2 = '))
    c=int(input('bilangan3 = '))
    
    if a>b and a>c:
    if b>c:
        print (a, 'terbesar dan', c, 'terkecil')
    else:
        print (a, 'terbesar dan', b, 'terkecil')
    elif b>a and b>c:
    if a>c:
        print (b, 'terbesar dan', c, 'terkecil')
    else:
        print (b, 'terbesar dan', a, 'terkecil')
    else:
    if a>b:
        print (c, 'terbesar dan', b, 'terkecil')
    else:
        print (c, 'terbesar dan', a, 'terkecil')

    print ('')
    print ('ingin coba lagi? (ya/tidak)')
    x=input()
    if x=='ya':
    return pengulangan()
    if x=='tidak':
    print('terimakasih telah menggunakan program ini.')

pengulangan()

Gambaran Flowchart

![67663464-2bff2f00-f998-11e9-9af4-8b55e2346a7d](https://user-images.githubusercontent.com/53388439/68938664-673f9180-07d1-11ea-92d2-14c316831424.jpg)

Screenshoot Code latihan02

![Screenshot (66)](https://user-images.githubusercontent.com/53388439/68938843-c7363800-07d1-11ea-930c-546c24ee3f92.png)
