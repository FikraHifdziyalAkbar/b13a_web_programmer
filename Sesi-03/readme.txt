class = tidak unik (satu element bisa memiliki lebih dari 1 class) -> .
id = unik (1 element hanya bisa memiliki 1 id) -> #

property = sifat2 yg ingin diterapkan pada selector isinya adalah value (setelah tanda ":")

#Style Placement

1. Inline css
    di dalam element css
    <p style='color: #ff0000;'>some white tex</p>

2. Internal css (bila baris file css sedikit)
    <head>
        <style>
            p { 
                color: #ff0000;
            }
        </style>
    </head>
    

3 External css (bila baris file css terlalu bnyak)
    <head>
        <link rel='stylesheet' type='text/css'
        href='asset/css/stylesheet.css' />
    </head>

Margin adalah sisi luar dari sebuah element. misalnya anda ingin mengatur jarak antar element.
-> margin-top    
-> margin-bottom    
-> margin-left    
-> margin-right
-> margin = atas, bawah, kanan, kiri

Padding adalah sisi dalam dari sebuah element.
kita bisa menggunakan syntax padding untuk mengatur jarak pada sisi dalam sebuah element yang kita tentukan
-> padding-top    
-> padding-bottom    
-> padding-left    
-> padding-right
-> padding = atas, bawah, kanan, kiri

font => font-size   : ukuran font
        font-weight : ketebalan font
        font-family : jenis font
        font-style  : gaya font
        font-color  : warna

Position
    Static : Value static merupakan nilai default dari position suatu element. Value static akan membuat suatu element bertumpukan . Untuk melihat hasil dari penggunaan value static buat file html dengan code berikut.
    Relative :Value relative digunakan untuk membuat suatu element bisa dipindah pindahkan . By default elemen memang tumpukan sebagaimana pada value static, tetapi kita bisa memindahkan elemen tersebut dengan property seperti top , left. Sehingga elemen tersebut akan menindihi layernya elemen lain
    Absolute : Value absolute digunakan untuk membuat suatu elemen bisa dipindahkan dan membuat elemen mengambang ke atas dibanding element lain.
    Fixed : Value fixed digunakan untuk membuat elemen mengambang di antara elemen elemen lain dan juga bisa dipindahkan posisinya. 

