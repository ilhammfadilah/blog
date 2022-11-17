---
title: "Variable"
description: "belajar variable pada golang"
slug: "belajar-variable-pada-golang"
date: 2022-11-17T12:04:42+07:00
image: 
categories:
    - golang
tags:
    - golang
---

variable merupakan sebuah nama yang diisi dengan sebuah nilai. jika kita memanggil sebuah variable, maka yang di acu adalah nilai yang ada di dalam variable tersebut. Pada golang untuk memakai sebuah variable, sebelumnya kita harus mendaklarasikan nya terlebih dahulu. Dalam golang juga ketika kita mendeklarasikan sebuah variable tetapi variable tersebut tidak dipakai maka itu akan terjadi error.

```golang
  var nilai string
```

kode di atas merupakan deklarasi variable dengan nama nilai dan memiliki type data string.

deklarasi juga dapat dilakukan secara grouping
```golang
  var(
    a int
    b bool
    c float64
  )
```

cara lain mendeklarasikan sebuah variable bisa dengan menggunakan operator ':=' dengan menggunakan operator tersebut itu artinya kita mendeklarasikan sekaligus mengisi nilai variable tersebut.

```golang
  a := 42             //inisialisasi dan mengisi nilai variable tunggal
  b, c := true, 12.5  //inisialisasi dan mengisi nilai variable majemuk
```