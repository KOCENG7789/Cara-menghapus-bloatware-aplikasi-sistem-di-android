# Cara-menghapus-bloatware-aplikasi-sistem-di-android

cara menghapus bloatware ada berbagai cara, tapi yang saya bahas itu lewat perintah ADB dan tanpa PC/Laptop.

# langkah pertama 
yaitu mengetahui perintah hapus dan memulihkan bloatware 
### perintah ini untuk menghapus bloatware=
 pm uninstall --user 0 (com.packageyangmaudihapus)
### perintah ini untuk memulihkan bloatware=
 pm install-existing --user 0 (com.packageyangmaudipulihkan)

Note:() tanda ini tidak dipakai,dan perintah pemulihan hanya bisa digunakan untuk memulihkan bloatware, jika aplikasi itu bukan bawaan tidak dapat dipulihkan menggunakan perintah tersebut.

# Langkah kedua
tentukan bloatware mana yang mau dihapus dan salin nama package yang mau dihapus.

# Langkah ketiga
salin perintah yang diatas lalu sesuai dengan package bloatware yang mau dihapus.

note: nama package dapat dicari di info aplikasi, jika tidak menemukan bisa menggunakan apk package name viewer.

# Langkah keempat A(menggunakan bugjaeger)
note: Langkah lanjutan nya ada di code pilih yang sesuai.

# Langkah keempat B(menggunakan brevent)
note: Langkah lanjutan nya ada di code pilih yang sesuai.


