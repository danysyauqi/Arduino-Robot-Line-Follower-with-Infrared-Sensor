### Arduino Line Follower with Infrared Sensor
---
## UAS SENSOR DAN TRENDUSER
```
Zaky Khairul Fajar Arlya 2100950
```
```
Dany Syauqi Nazhif 2101034
```
```
Fauzan Muhammad Fahrezi 2104480
```
```
Agung Satria Pamungkas 2104773
```
```
Raisyah Vidia Rahayu 2106401
```

## Problem
> Sebuah alat transportasi distribusi pada umumnya membutuhkan manusia sebagai pengemudi untuk menentukan arah tujuannya. Namun apabila manusia mengemudikan kendaraan dalam rentang waktu yang lama dapat menyebabkan kondisi stamina manusia menurun. Akibatnya dapat menciptakan kecelakaan dalam berkendara. Akhirnya di ciptakan robot line follower sebagai solusi untuk kendaraan dapat bergerak tanpa membutuhkan pengemudi 

## Solution
> Dari permasalah tersebut solusi yang dibuat adalah menciptakan *robot line follower* yang cara kerjanya menggunakan gabungan mikrokontroller Arduino Uno yang sudah di berikan script, sensor infrared sebagai pendeteksi serta komponen lainnya yang ada pada rangkaian skematik dibawah.
```
pembuatan robot line follower merupakan implementasi secara mikro dan sederhana
```

## Analisis
> <img alt="Infrared" src="https://i.postimg.cc/4N9DzzCH/unnamed.jpg" width="40%" height="40%">
> 
> 
> 
> Line Follower  adalah robot yang sangat sederhana yang ideal untuk elektronik pemula. Robot berjalan di sepanjang garis menggunakan sensor iR. Sensor memiliki dua dioda, satu dioda mengirimkan cahaya inframerah, dioda lainnya menerima cahaya yang dipantulkan dari permukaan. Ketika sinar infra merah jatuh di permukaan putih, mereka dipantulkan kembali. Ketika sinar inframerah jatuh pada permukaan hitam, cahaya diserap oleh permukaan hitam dan tidak ada sinar yang dipantulkan kembali, sehingga fotodioda tidak menerima cahaya. Sensor mengukur jumlah cahaya yang dipantulkan dan mengirimkan nilainya ke arduino. Ada potensiometer pada sensor, yang dengannya kita dapat menyesuaikan sensitivitas sensor.
>
> 
>  
>    <img alt="Arah gerak" src="https://i.postimg.cc/T1CJbNdv/lineflower-kierunek.png" width="40%" height="40%">
>
>
>Arduino sekarang harus membuat keputusan berdasarkan data yang diterima dari sensor, sampai sensor tidak mendeteksi garis hitam maka akan maju. Jika sensor kiri mendeteksi garis hitam, robot berbelok ke kanan, dan jika sensor kanan mendeteksi garis hitam, robot berbelok ke kiri. Robot akan berhenti ketika kedua sensor mendeteksi garis hitam secara bersamaan.

---

## Rujukan
> Sumber referensi yang di pakai
> + [YouTube DIY Builder](https://www.youtube.com/watch?v=t7k9D1jDEtk)
> + [URL Website](https://indobot.co.id/blog/line-follower-sederhana-dengan-ir-obstacle-sensor/)
