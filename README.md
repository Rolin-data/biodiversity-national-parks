# Biodiversity in National Parks

Analisis status konservasi spesies di empat taman nasional (data National Park Service).

## Isi folder

| File | Keterangan |
|---|---|
| `biodiversity.ipynb` | Notebook analisis (sudah dijalankan, lengkap dengan output & grafik) |
| `Biodiversity_Rolin.pptx` | Slide deck **versi Inggris** |
| `Biodiversity_Rolin_ID.pptx` | Slide deck **versi Indonesia** |
| `Biodiversity_Rolin.pdf` / `Biodiversity_Rolin_ID.pdf` | Versi PDF dari slide deck |
| `preview.html` | Hasil notebook dalam bentuk HTML |
| `assets/` | Grafik (chart1, chart2) dan foto taman nasional |

## Cara menjalankan notebook

1. Buka folder ini di VS Code atau Jupyter.
2. Buka `biodiversity.ipynb`, pilih kernel Python 3.
3. Jalankan dari atas ke bawah (Shift + Enter).

Library yang dipakai: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`.

## Ringkasan hasil

- Sebagian besar spesies berstatus **No Intervention** (5.633 dari 5.824).
- Spesies yang berstatus dilindungi hanya **191** (sekitar 3,3%).
- Proporsi dilindungi tertinggi: **Mamalia (17,0%)** dan **Burung (15,4%)**; terendah tumbuhan (~1%).
- Uji chi-square: `chi2 = 628,58`, `p ≈ 2,46 × 10⁻¹¹⁷` → hubungan signifikan (p < 0,05).
- Observasi terbanyak: **Yellowstone (1.587.641)**, lalu Yosemite, Bryce Canyon, dan Great Smoky Mountains.

## Sumber

- Data: National Park Service (dataset proyek Codecademy).
- Foto taman: Wikimedia Commons.
