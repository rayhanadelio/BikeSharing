# Bike Sharing Analysis Dashboard

## Fitur
- Visualisasi Pengaruh Cuaca terhadap jumlah penyewaan sepeda di hari kerja dan hari libur.
- Perbandingan Pengguna Kasual vs Terdaftar dalam hal jumlah penyewaan sepeda.
- Menu Interaktif untuk memudahkan pengguna dalam memilih jenis analisis yang diinginkan.

## Persyaratan
Pastikan Anda memiliki komponen berikut sebelum menjalankan aplikasi:
- Python 3.7 atau lebih baru.
- Streamlit untuk membangun dashboard.
- Pandas untuk manipulasi data.
- Matplotlib untuk visualisasi.

## Instalasi

1. Clone repositori ini:
    ```sh
    git clone https://github.com/username/BikeSharingDataset.git
    ```
    Gantilah `username` dengan nama pengguna GitHub Anda.

2. Navigasi ke folder repositori:
    ```sh
    cd BikeSharingDataset
    ```

3. Membuat virtual environment (Opsional tapi disarankan):
    ```sh
    python -m venv streamlit_env
    ```

4. Aktivasi virtual environment:
    - Linux/MacOS:
      ```sh
      source streamlit_env/bin/activate
      ```
    - Windows:
      ```sh
      streamlit_env\Scripts\activate
      ```

5. Instal dependensi:
    ```sh
    pip install -r requirements.txt
    ```
    Pastikan Anda memiliki file `requirements.txt` yang berisi dependensi berikut:
    ```
    streamlit
    pandas
    matplotlib
    seaborn
    ```

## Menjalankan Dashboard

1. Jalankan aplikasi Streamlit:
    ```sh
    streamlit run bike_sharing_dashboard.py
    ```

2. Buka Browser: Setelah perintah di atas dijalankan, aplikasi akan membuka browser secara otomatis di alamat `http://localhost:8501/`. Jika tidak terbuka, salin dan tempel URL tersebut di browser Anda.

## Struktur Repositori

