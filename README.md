# CNN Project

Proyek ini menggunakan Convolutional Neural Network (CNN) untuk klasifikasi gambar kucing dan anjing.

## Struktur Folder

```
├── cnn.ipynb              # Notebook utama dengan model CNN
├── training_set/          # Data training (kucing & anjing)
├── test_set/              # Data testing (kucing & anjing)
├── single_prediction/     # Folder untuk prediksi individual
└── results/               # Model yang sudah dilatih
    └── best_model.keras   # Model terbaik yang disimpan
```

## Requirements

- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib
- Pillow

## Instalasi

```bash
pip install tensorflow numpy matplotlib pillow
```

## Penggunaan

Buka dan jalankan `cnn.ipynb` di Jupyter Notebook untuk:
- Melatih model CNN
- Mengevaluasi performa model
- Melakukan prediksi pada gambar baru

## Notes

- Training dan test data tidak disertakan dalam repository (file besar)
- Model sudah dilatih tersimpan di `results/best_model.keras`
