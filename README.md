# WebGIS Model Bahaya Titik Api – Provinsi Papua Barat Daya

PjBL GD4103 Sistem Informasi Geografis 2026 · Kelompok 3 K-02

Model: H = 0,347 Titik panas + 0,234 Curah hujan + 0,216 Gambut + 0,085 NDVI + 0,081 LST + 0,037 DEMNAS
Kelas: < 1,8 Sangat rendah · 1,8–2,6 Rendah · 2,6–3,4 Sedang · 3,4–4,2 Tinggi · ≥ 4,2 Sangat tinggi

## Isi
- `index.html` – halaman WebGIS (Leaflet)
- `data/*.png` – raster kelas, nilai H, dan 6 parameter (diperkecil ±180 m, proyeksi Web Mercator, nilai asli tersimpan di piksel)
- `data/titik_panas.geojson` – 105 titik panas VIIRS + skor model
- `data/stats.json` – luas per kelas (dihitung dari raster 30 m)
- `unduh/` – GeoTIFF kelas bahaya resolusi asli dan CSV titik panas

Buka lewat link GitHub Pages; jika `index.html` dibuka langsung dari laptop (klik dua kali), data tidak akan termuat.
