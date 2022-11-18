---
title: "Tide Data"
description: 
date: 2022-11-18T18:28:38+07:00
image:
categories:
    - golang
tags:
    - golang 
math: 
license: 
hidden: false
comments: true
draft: false
---

go menyediakan banyak tipe data yang dapat digunakan seprti numeric, string, boolean, error dan kemampuan untuk membuat tipe data secara custom atau kita yang membuat sebuah tipe data.

ketika mendeklarasikan variabel maka akan secara otomatis nilai vatiabel diberi null. contohnya 'var s string' s disini akan berisi '""' string kosong.

dibawah ini contoh tipe data

```golang
  const a int32 = 12 //32bit integer
  const b float32 = 20.2 //32bit float
  var c complex128 = 1 + 4i //128 bit complex number
  var d uint16 =14 //16bit unsigned integer

  n := 1 //int
  pi := 3.14 //float64
  x, y := true, false //boolean
  z := "golang" //string
```