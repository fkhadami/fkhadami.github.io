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
    <p class="tool-tag">Arus · Modul praktikum</p>
    <h2>Bengkel Arus</h2>
    <p>Mengikuti Modul 3 Pengolahan Data Arus: konversi vektor, <em>averaging</em>, matriks frekuensi kejadian, visualisasi (termasuk <em>current rose</em>), dan pelaporan. Semua perhitungan berjalan lokal di peramban, dan gambar resolusi cetak siap diunduh.</p>
    <p><a class="btn btn--primary" href="{{ '/tools/bengkel-arus.html' | relative_url }}">Buka Bengkel Arus</a></p>
  </div>

  <div class="tool-card">
    <p class="tool-tag">Pasang surut · Aplikasi Python</p>
    <h2>Tide Agent</h2>
    <p>Aplikasi Streamlit untuk analisis data pasut: unggah CSV, statistik ringkas, pembersihan <em>spike</em> (filter Hampel), spektrum FFT, analisis harmonik UTide, peta stasiun, interpretasi opsional berbasis LLM, dan ekspor laporan PDF. Berjalan daring di Streamlit Community Cloud.</p>
    <p><a class="btn btn--primary" href="https://tidereport.streamlit.app/" target="_blank" rel="noopener">Buka Tide Agent</a></p>
  </div>

</div>
