---
title: "Sekolah Tinggi Intelijen Negara"
date: 2023-09-18T07:44:00+07:00
authors: ['Diman Alfon']
tags: ['xx1000']
draft: false
math: true
url: "0074"
---
{{< toc >}}

## Selamat Datang

![Logo Sekolah Tinggi Intelijen Negara](https://upload.wikimedia.org/wikipedia/id/d/d9/Logo_Sekolah_Tinggi_Intelijen_Negara.png)

Sekolah Tinggi Intelijen Negara atau *STIN* adalah sebuah perguruan tinggi kedinasan yang berada di bawah naungan [**Badan Intelijen Negara**](https://id.wikipedia.org/wiki/Badan_Intelijen_Negara_Republik_Indonesia). Kampusnya terletak di daerah Sentul, Bogor, Jawa Barat. Berdirinya STIN bertujuan untuk menyiapkan ***Taruna*** nya menjadi anggota masyarakat intelijen yang memiliki kemampuan akademik dan/atau keahlian profesional sehingga dapat menerapkan dan mengembangkan ilmu intelijen, ilmu pengetahuan, teknologi, dan/atau seni bidang intelijen untuk menjaga persatuan dan kesatuan Negara Kesatuan Republik Indonesia.

{{< youtube npr6hITUklw >}}

> "Apa yang kamu dengar,apa yang kamu lihat,dan apa yang kamu rasakan,
> hanya untuk dirimu sendiri"

## Jadwal Kegiatan Taruna
No | Jam | Kegiatan | Lokasi
:-: | :- | -: | :-:
1 | 04.00 | Bangun Pagi | Mess
2 | 04.30 | Ibadah Subuh | Masjid Baitul Ilmi
3 | 05.00 | Olahraga Pagi| Lapangan Hitam
4 | 06.00 | Pembersihan | Mess
5 | 06.30 | Makan Pagi | Ruang Makan A.J.Kumaat
6 | 07.00 | Apel Pagi | Lapangan Hitam
7 | 08.00 | Kuliah | Smart Campus
8 | 13.30 | Makan Siang | Ruang Makan A.J Kumaat
9 | 14.00 | Kuliah | Smart Campus
10 | 17.00 | *UKT*/Oraum | -
11 | 17.30 | Pembersihan | Mess
12 | 18.00 | Ibadah Sore | Masjid Baitul Ilmi
13 | 19.00 | *UKt*/Belajar Mandiri | -
14 | 21.00 | Apel Malam | Lapangan Tenis
15 | 22.00 | Istirahat Malam | Mess


## Unit Kegiatan Taruna(UKT)
+ UKT Wajib
	- Drum Corps
	- Orchestra
    - Paduan Suara
    - Tarung Derajat
+ UKT Pilihan
    - Basket
    - Futsal
    - Voli
    - Renang
    - Menembak
    - Robotik
    - Catur

## Statistik Anggota UKT
{{< chart 90 200 >}}
{
    type: 'bar',
    data: {
        labels: ['Orchestra', 'Paduan Suara', 'Drum Corps', 'Tarung Derajat'],
        datasets: [{
            label: 'Bar Chart',
            data: [70, 40, 80, 50],
            backgroundColor: [
                'rgba(255,99,132,0.2)',
                'rgba(54,162,235,0.2)',
                'rgba(255,206,86,0.2)',
                'rgba(75,192,192,0.2)'
            ],
            borderColor: [
                'rgba(255,99,132,1)',
                'rgba(54,162,235,1)',
                'rgba(255,206,86,1)',
                'rgba(75,192,192,1)'
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


{{< html >}}
<style>
 button {
    background-color: red;
    color: white;
    padding: 10px 20px;
    border: none;
        }
</style>
<script>
var b1_visible = false;
var b2_visible = false;

function show(e, i) {
  p = document.getElementById(i);
  if(!b1_visible) {
    p.style.display = "block";
  } else {
    p.style.display = "none";    
  }
  b1_visible = !b1_visible;

  if(!b2_visible) {
    p.style.display = "block";
  } else {
    p.style.display = "none";    
  }
  b2_visible = !b2_visible;
}
</script>
<button onclick="show(event, 'intro');">Visi</button>
<p id="intro" style="display: none;">
Menjadi perguruan tinggi intelijen bertaraf internasional (world class inteligence college) yang mempunyai keunggulan dan kewibawaan dalam mendukung terwujudnya keamanan nasional pada tahun 2045.
{{< /html >}}

## Alur Penerimaan Calon Taruna STIN
{{< mermaid >}}
flowchart LR
A["Pendaftaran Online
dari website BKN"] --> B["Seleksi Administrasi"]
B --> C["Tes
SKD"]
C --> D["Psikotest"]
D --> E["Tes
Kesehatan"]
E --> F["Tes
Jasmani"]
F --> G["Tes
Mental & Ideologi"]
G --> H["Sidang
Pantukhir"]
H --> I["Masuk
STIN"]

{{< /mermaid >}}

## svg
{{< html >}}
  <svg style="background: #eee;">
    <rect x="0" y="50" width="50" height="50">
      <animate
        attributeName="x"
        from="0" to="300"
        begin="0s" dur="1s"
        repeatCount="indefinite" />
    </rect>
  </svg>
  {{< /html >}}

  {{< html >}}
  <svg style="background: #eee;" width="500" height="500">
    <rect x="100" y="100" width="100" height="100"></rect>
	<rect x="300" y="100" width="100" height="100"></rect>
	<rect x="200" y="200" width="100" height="150"></rect>
	<rect x="150" y="250" width="50" height="150"></rect>
	<rect x="300" y="250" width="50" height="150"></rect>
  </svg>
  {{<	 /html >}}

## equation

$$
\mathbf{M} =
\left[
\begin{matrix}
1 & 2 & 3 & 4 & 5 \newline
1 & 2 & 3 & 4 & 5 \newline
1 & 2 & y^2 & z & x \newline
\end{matrix}
\right]
$$

$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

$$\tag{23}
y = ax^2 + bx + c
$$