---
date: 2022-08-30
title: Simaster V1.7
categories:
  - openclash
description: Cara penggunaan simaster v1.7
type: Document
---

## Cfa Simaster V1.7

![image](https://user-images.githubusercontent.com/46000841/187411953-411d676b-c19c-47e1-8ec9-2772fdff0ed0.png)

Cara Penggunaan config simaster v1.7

1. Download File [DISNI](https://masterwifinetworksolution.tech/download3)
2. Masuk Openclash di Openwrt
3. Masuk ke menu Config Manage
4. Pilih tabel dengan `Backup`

![image](https://user-images.githubusercontent.com/46000841/187412457-c0a5964d-b4fe-40f2-9c16-150690623588.png)

5. Masukkan file backup `backup-simaster-V1.7.tar.gz`
6. Tekan Upload
7. Masuk menu Config Editor

![image](https://user-images.githubusercontent.com/46000841/187412770-463ec17d-f046-4543-b643-c30a9163bc19.png)

8. Masuk Proxy_Provider
9. Pilih `account-master1.yaml` atau `account-master2.yaml` lalu tekan Edit
10. Masukkan akun kalian masing-masing dan tekan save

Kini anda sudah bisa menggunakan config `Simaster V1.7`

## Change Log Simaster V1.7

1. Multi WAN Loadbalance tanpa mwan3
2. Bisa pilih suka hati `Loadbalance` atau `Url-Test` atau `Fallback` atau `Relay` atau `Select`.
3. Support UDP dan TCP
4. Support Port Game Mobile Legends, Free Fire, Pubg, Stumble, Garena, Dota2.
5. Support port remote Zerotier.
6. Direct Whatsapp tersedia

## Cara setting 2 modem

1. masuk menu `server grup` di openclash.
2. pada `proxy group` edit bagian `wan1` dan `wan2` sesuai dengan interface kalian masing masing.
3. tekan commit jika sudah lalu geser ke bawah dan tekan commit lagi kemudian apply

kini mode Loadbalance + pisah trafik 2 isp telah aktif di perangkat kalian.

## Cara setting 1 modem


1. masuk menu `server grup` di openclash.
2. pada `proxy group` edit bagian `wan1` dan `wan2` hapus interface di dalamnya.
3. tekan commit jika sudah lalu geser ke bawah dan tekan commit lagi kemudian apply

kini mode Pisah trafik 1 isp telah aktif di perangkat kalian.
