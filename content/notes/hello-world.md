---
title: "Penggunaan Kendaraan"
date: 2023-09-18T07:44:00+07:00
authors: ['Ayara Yenima']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
{{< toc >}}

## Angkutan Pribadi
Angkutan pribadi adalah angkutan yang menggunakan kendaraan pribadi, seperti :
- Mobil pribadi
- Sepeda Motor
- Sepeda

## Angkutan Umum
Angkutan Umum adalah angkutan penumpang yang dilakukan dengan sistem sewa atau bayar. Termasuk dalam pengertian angkutan umum penumpang adalah :
- Bus
- Minibus
- Kereta Api
- DLL


## Data Jumlah Kendaraan Bermotor Tahun 2021
No. | Jenis Kendaraan | Jumlah Kendaraan Tahun 2021
:-: | :-:| :-
1| Mobil Penumpang | 16.413.348
2| Mobil Barang | 5.299.361
3| Mobil Bis | 237.566


## Kelebihan dan Kekurangan Alat Transportasi Umum dan Pribadi
{{< youtube iYCwCjcp5kA >}}

## Perbandingan Volume Transportasi Umum dan Pribadi
Gambar dibawah ini menunjukan Perbandingan Volume atau Kepadatan antara Transportasi Umum dan Pribadi pada Arus Lalu lintas.

![](https://i.redd.it/wuqrl6km0jp31.jpg)

Penggunaan Transportasi Umum lebih efisien jika dibandingkan dengan Penggunaan Transportasi Pribadi, dikarenakan ruang yang digunakan lebih sedikit. Sehingga, tidak mengakibatkan Kemacetan pada Arus Lalu Lintas


## Animation
{{< html >}}
<svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
  <img src="bus.svg"/>
  <rect x="10" y="10" width="50" height="50" fill="blue">
    <animate attributeName="width" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="height" from="50" to="150" dur="2s" begin="0s" repeatCount="indefinite" />
    <animate attributeName="fill" values="blue;red;green;blue" dur="4s" begin="0s" repeatCount="indefinite" />
  </rect>
</svg>
{{< /html >}}

## Animation rect
{{< html >}}
<svg width="400" height="300" xmlns="http://www.w3.org/2000/svg">
  <!-- Rectangle with gradients -->
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:rgb(255,0,0);stop-opacity:1" />
      <stop offset="100%" style="stop-color:rgb(0,0,255);stop-opacity:1" />
    </linearGradient>
  </defs>

  <rect x="20" y="20" width="200" height="100" fill="url(#grad1)" stroke="green" stroke-width="3" />

  <!-- Text element -->
  <text x="30" y="160" font-family="Arial" font-size="24" fill="black">Complex SVG</text>

  <!-- Circle with animation -->
  <circle cx="250" cy="150" r="20" fill="orange">
    <animate attributeName="r" from="20" to="50" dur="2s" begin="0s" repeatCount="indefinite" />
  </circle>
</svg>
{{< /html >}}

## Moda Transportasi yang Paling Sering digunakan
Data Bulan September Tahun 2022
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['PRIBADI', 'OJEK ONLINE', 'TAKSI ONLINE', 'UMUM', 'TAXI'],
        datasets: [{
            label: 'Bar Chart',
            data: [41, 28, 5, 2, 0.2, ],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
            ],
            borderWidth: 1
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            yAxes: [{
                ticks: {
                    beginAtZero: true
                }
            }]
        }
    }
}
{{< /chart >}}
Survei Polling Institute mengungkap, ojek online bukan menjadi transportasi utama masyarakat Indonesia. Bahkan, penggunaan transportasi umum di tanah air cenderung sangat rendah.

Berdasarkan riset tersebut, kebanyakan responden menggunakan kendaraan pribadi 41.4%. Responden yang menggunakan ojek online dan taxi online menjadi pilihan transportasi terbanyak kedua masyarakat Indonesia untuk mobilitas.

## Siklus Penggunaan Kendaraan
{{< mermaid >}}
flowchart LR
    B --> I --> P --> O --> E
    B(("v"))
    I(("Peningkatan Pemahaman"))
    P(("Perubahan Metode Ajar"))
    O(("Perubahan Faktor Sosbud"))
    E(("SAMPAI KE TEMPAT"))
{{< /mermaid >}}

## Sumber
+ [Data Kendaraan] (https://www.bps.go.id/indicator/17/57/1/jumlah-kendaraan-bermotor.html)
+ [Perbandingan Moda Transportasi] (https://www.google.com/url?sa=i&url=https%3A%2F%2Fdataboks.katadata.co.id%2Fdatapublish%2F2022%2F09%2F14%2Fbukan-ojol-ini-moda-transportasi-mayoritas-warga-indonesia&psig=AOvVaw1SMhYkbvAMIBgKYR6FqGxD&ust=1695112152576000&source=images&cd=vfe&opi=89978449&ved=0CBIQjhxqFwoTCOC0wP3es4EDFQAAAAAdAAAAABAI)
+ [Github] (https://Github.com/ayarayenima)
