# Image Processing with Streamlit

## Image Manipulation App

Aplikasi ini adalah sebuah aplikasi sederhana yang memanipulasi gambar menggunakan Streamlit dan Scikit-Image. Dengan aplikasi ini, Anda dapat melakukan beberapa operasi pada gambar, termasuk Convex Hull, Skeletonization, dan Active Contour.

### Cara Penggunaan

1. Clone repositori ini ke lokal Anda.
   ```shell
   git clone https://github.com/RianFauza/Citra-Per11.git
   ```

2. Masuk ke direktori proyek.
   ```shell
   cd citra
   ```

3. Instal semua dependensi yang diperlukan.
   ```shell
   pip install streamlit scikit-image matplotlib
   ```

4. Jalankan aplikasi Streamlit.
   ```shell
   streamlit run app.py
   ```

5. Aplikasi akan berjalan dan akan terbuka di browser Anda. Di sidebar, Anda dapat memilih salah satu dari tiga tugas pengolahan citra:
   - **Convex Hull**: Menampilkan gambar subset dari dataset LFW dan menghitung convex hull untuk masing-masing gambar.
   - **Skeletonization**: Menampilkan skeletonization dari gambar kuda.
   - **Active Contour**: Menampilkan segmentasi active contour pada gambar astronaut.

### Penjelasan Fitur

1. **Convex Hull**: 
   - Menampilkan 20 gambar dari subset dataset LFW.
   - Setiap gambar akan dihitung dan ditampilkan convex hull-nya.

2. **Skeletonization**:
   - Menampilkan gambar asli kuda.
   - Menampilkan gambar hasil skeletonization dari gambar kuda tersebut.

3. **Active Contour**:
   - Menampilkan gambar asli astronaut.
   - Menampilkan gambar hasil segmentasi active contour dengan inisialisasi dan hasil akhir kontur.
