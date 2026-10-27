# fkhadami.github.io

Website pribadi Faruq Khadami — CV dan tools pengolahan data oseanografi.
Dibangun dengan template [Academic Pages](https://github.com/academicpages/academicpages.github.io) (Jekyll) dan di-deploy otomatis ke GitHub Pages lewat GitHub Actions (`.github/workflows/jekyll.yml`).

## Struktur penting

| Path | Isi |
|---|---|
| `_config.yml` | Nama, bio sidebar, tautan profil (Scholar, ORCID, GitHub) |
| `_data/navigation.yml` | Menu atas (CV, Tools) |
| `_pages/about.md` | Halaman Home |
| `_pages/cv.md` | Halaman CV (menampilkan `files/cv-faruq-khadami.html`) |
| `_pages/tools.md` | Daftar tools |
| `tools/*.html` | Tools HTML mandiri (disalin apa adanya) |
| `author.avatar` di `_config.yml` | Foto profil sidebar (kosong = tanpa foto; taruh file di `images/` lalu isi namanya) |

## Menambah tool baru

1. Simpan file HTML ke folder `tools/`, misal `tools/gelombang.html`.
2. Tambahkan satu kartu di `_pages/tools.md` (salin blok `<div class="tool-card">`), dan bila perlu satu baris di `_pages/about.md`.
3. Commit dan push — website diperbarui otomatis dalam 1–2 menit.

## Menjalankan lokal (opsional)

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```
