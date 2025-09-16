# RadarMiniCuaca
Dokumentasi dan kode untuk desain Radar Mini Cuaca berbasis SDR + motor kontrol
# Radar Mini Cuaca
Proyek riset untuk merancang radar mini cuaca berbasis Software Defined Radio (SDR), antena microstrip, dan kontrol motor stepper.

## Fitur
- Akuisisi data SDR (Ettus N210, Nuand bladeRF)
- Pulse Compression (Chirp + Matched Filter)
- Visualisasi PPI (PyQt5/Matplotlib)
- Kontrol motor azimuth & elevasi (Arduino Mega 2560)
- Logging & error handling

## Struktur
- `docs/` → Dokumentasi
- `src/` → Source code Python
- `gui/` → GUI radar
- `data/` → Contoh data radar
# Radar Mini Cuaca

Proyek ini bertujuan untuk mengembangkan sistem **Radar Mini Cuaca** berbasis SDR (Software Defined Radio), antena microstrip, dan kontrol motor stepper.  
Implementasi ditargetkan untuk **bandara perintis, waduk, dan pemantauan cuaca di area terpencil**.

---

## 🚀 Fitur Utama
- Akuisisi data radar dengan **SDR (Nuand bladeRF / Ettus N210)**
- **Kontrol motor stepper** (azimuth & elevasi) berbasis Arduino
- **Pulse compression radar** (chirp + matched filter)
- **Visualisasi GUI** (PyQt5 / Streamlit)
- Penyimpanan data radar ke format `.npy` / `.csv`
- Dokumentasi teknis terstruktur di folder `docs/`

---

## 📂 Struktur Folder (Diagram Tree)

```text
RadarMiniCuaca/ 
│── docs/                # Dokumentasi Markdown
│    ├── 01_Overview.md
│    ├── 02_SDR_Setup.md
│    ├── 03_Python_Modules.md
│    ├── 04_Logging.md
│    ├── 05_GUI.md
│── src/                 # Source code Python
│    ├── radar_main.py
│    ├── motor_control.py
│    ├── sdr_acquisition.py
│── gui/                 # File GUI PyQt/Streamlit
│    ├── radar_gui.py
│── data/                # Contoh data radar (.npy, .csv)
│── LICENSE
│── README.md
