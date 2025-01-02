# Cara-menghapus-bloatware-aplikasi-sistem-di-android

cara menghapus bloatware ada berbagai cara, tapi yang saya bahas itu lewat perintah ADB dan tanpa PC/Laptop.

# langkah pertama 
yaitu mengetahui perintah hapus dan memulihkan bloatware 
### perintah ini untuk menghapus bloatware=
 pm uninstall --user 0 (com.pakageyangmaudihapus)
### perintah ini untuk memulihkan bloatware=
 pm install-existing --user 0 (com.pakageyangmaudipulihkan)

Note:() tanda ini tidak dipakai,dan perintah pemulihan hanya bisa digunakan untuk memulihkan bloatware, jika aplikasi itu bukan bawaan tidak dapat dipulihkan menggunakan perintah tersebut.

# Langkah kedua
tentukan bloatware mana yang mau dihapus dan salin nama pakage yang mau dihapus.

# Langkah ketiga
salin perintah yang diatas lalu sesuai dengan pakage bloatware yang mau dihapus.

note: nama pakage dapat dicari di info aplikasi, jika tidak menemukan bisa menggunakan apk pakage viewer.

# Langkah keempat 

