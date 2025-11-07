# Deteksi Objek Real-Time di Raspberry Pi 3B

Ini adalah proyek pribadi saya untuk menjalankan model *machine learning* (deteksi objek) secara *real-time* di Raspberry Pi 3B.

## 🚀 Tujuan

Proyek ini menggunakan **TensorFlow Lite (TFLite)** dan **OpenCV** untuk mengambil *feed* dari kamera USB dan mendeteksi objek yang ada di depannya.

## 🛠️ Setup

* **Perangkat:** Raspberry Pi 3B
* **Sistem Operasi:** Raspberry Pi OS Lite (64-bit)
* **Lingkungan:** Dijalankan di dalam *virtual environment* Python (`venv`).
* **Dependensi Utama:**
    * `tflite-runtime`
    * `opencv-python-headless`
    * `numpy`

## 🏃 Cara Menjalankan

1.  Masuk ke *virtual environment*:
    ```bash
    source ../proyek_ml/bin/activate
    ```
2.  Jalankan skrip deteksi:
    ```bash
    python3 detect.py
    ```
