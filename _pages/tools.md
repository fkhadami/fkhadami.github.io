---
layout: single
title: "Tools Pengolahan Data Oseanografi"
permalink: /tools/
author_profile: true
---

Kumpulan aplikasi web yang saya kembangkan untuk membantu pengolahan data oseanografi dalam perkuliahan, praktikum, dan riset. Tools berbasis peramban berjalan sepenuhnya di komputer Anda: data yang dimasukkan tidak dikirim ke server mana pun. Daftar ini akan terus bertambah.

<div class="tool-list">

  <div class="tool-card">
    <p class="tool-tag">Pasang surut · Datum</p>
    <h2>Pemandu Datum Pasut</h2>
    <p>Membantu memilih standar datum yang tepat (IHO Res. 3/1919, S-44, C-13, IOC Manual 14, NOAA CO-OPS, SNI 7646:2010) sesuai tujuan dan panjang data muka air. Dilengkapi rumus dan langkah perhitungan tiap datum, kalkulator LAT/HAT dari konstanta harmonik (prediksi 18,61 tahun dengan koreksi nodal), transfer datum, daftar singkatan, dan referensi.</p>
    <p><a class="btn btn--primary" href="{{ '/tools/datum-pasut.html' | relative_url }}">Buka Pemandu Datum Pasut</a></p>
  </div>

  <div class="tool-card">
    <p class="tool-tag">Gelombang · Modul praktikum</p>
    <h2>Bengkel Gelombang</h2>
    <p>Mengikuti Modul 2 Pengolahan Data Gelombang, dalam tiga bagian terpisah. <strong>Materi</strong>: parameter gelombang, metode <em>zero up-crossing</em> dan <em>zero down-crossing</em>, statistik Hs/Ts, matriks frekuensi, <em>wave rose</em>, dan sistematika laporan, dengan contoh interaktif dari bahan kuliah. <strong>Olah data elevasi η(t)</strong> untuk rekaman mentah <em>wave logger</em>/<em>pressure sensor</em>: koreksi muka air, deteksi gelombang individu per burst, statistik, hingga laporan. <strong>Olah data Hs, Tp, Dir</strong> untuk keluaran ADCP/AWAC: QC, <em>time series</em>, statistik, matriks, <em>wave rose</em>, dan laporan. Gambar resolusi cetak siap diunduh.</p>
    <p><a class="btn btn--primary" href="{{ '/tools/bengkel-gelombang.html' | relative_url }}">Buka Bengkel Gelombang</a></p>
  </div>

  <div class="tool-card">
    <p class="tool-tag">Arus · Modul praktikum</p>
    <h2>Bengkel Arus</h2>
    <p>Mengikuti Modul 3 Pengolahan Data Arus: konversi vektor, <em>averaging</em>, matriks frekuensi kejadian, visualisasi (termasuk <em>current rose</em>), dan pelaporan. Semua perhitungan berjalan lokal di peramban, dan gambar resolusi cetak siap diunduh.</p>
    <p><a class="btn btn--primary" href="{{ '/tools/bengkel-arus.html' | relative_url }}">Buka Bengkel Arus</a></p>
  </div>

  <div class="tool-card">
    <p class="tool-tag">Arus · ADCP · Data mentah PD0</p>
    <h2>PD0 ADCP Processor</h2>
    <p>Tools untuk mengolah data ADCP langsung dari file keluaran RDI ADCP (format biner PD0), khususnya <strong>Sentinel V50</strong>, dengan alur kerja seperti perangkat lunak Velocity. Membaca konfigurasi instrumen dan seluruh ensemble, memotong data saat instrumen belum/sudah tidak di air, transformasi koordinat <em>beam</em> → instrumen → bumi (ENU) dengan koreksi deklinasi magnetik, QC (korelasi, intensitas gema, <em>percent good</em>, kecepatan galat, kemiringan, <em>side-lobe</em>), rata-rata waktu, dan rotasi ke sumbu utama (<em>along/cross channel</em>). Visualisasi kontur, <em>time series</em> dengan <em>quiver</em>, profil, <em>scatter</em>, diagram vektor progresif dan <em>current rose</em> (8/16 mata angin, per bin atau rata-rata kedalaman), serta tab analisis <em>backscatter</em> (Sv absolut atau relatif dari <em>echo intensity</em>, metode Deines 1999 dengan koreksi derau Mullison 2017); setiap gambar dan datanya bisa diunduh, serta ekspor ke MATLAB (.mat) dan CSV. File juga bisa dari Workhorse, Ocean Surveyor dan VmDas. Semua pengolahan berjalan lokal di peramban.</p>
    <p><a class="btn btn--primary" href="{{ '/tools/adcp-pd0.html' | relative_url }}">Buka PD0 ADCP Processor</a></p>
  </div>

  <div class="tool-card">
    <p class="tool-tag">Pasang surut · Aplikasi Python</p>
    <h2>Tide Agent</h2>
    <p>Aplikasi Streamlit untuk analisis data pasut: unggah CSV, statistik ringkas, pembersihan <em>spike</em> (filter Hampel), spektrum FFT, analisis harmonik UTide, peta stasiun, interpretasi opsional berbasis LLM, dan ekspor laporan PDF. Berjalan daring di Streamlit Community Cloud.</p>
    <p><a class="btn btn--primary" href="https://tidereport.streamlit.app/" target="_blank" rel="noopener">Buka Tide Agent</a></p>
  </div>

</div>
