---
title: "Array"
description: "belajar array pada golang"
date: 2022-11-19T13:24:13+07:00
image: 
math: 
categories:
    - golang
tags:
    - golang 
license: 
hidden: false
comments: true
draft: false
---

biasanya sebuah variable hanya dapat menampung satu jenis nilai saja, tetapi ada sebuha cara untuk menampung banyak nilai dengan hanya menggunakan satu variable. Dengan menggunakan array kita dapat menampung banyak nilai sekaligus di dalam satu variabel.

tidak hanya array dalam golang juga ada interface, slice dan map yang juga dapat menampung banyak nilai di dalam satu variabel.

pada golang mendeklarasikan array harus dengan menyertakan ukuran dan tipe datanya.

```golang
  var animals = [3]string{"cat, "dog", "hamster"}
```

untuk mengaksesnya dapat dilakukan perulangan

```golang
  for i : = 0; i < len(animals); i++ {
    lists := animals[i]
    fmt.Prinln(i, lists)
  }
```