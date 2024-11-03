<h1 align="center"> NLP With Hugging Face Transformers </h1>
<p align="center"> Berisi tentang pipeline dari Hugging Face Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

<h2 align="center"> Analisis </h2>

- **Zero-Shot Classification: Inovasi dalam Klasifikasi Teks**  
  Zero-shot classification adalah metode yang dapat digunakan untuk mengklasifikasikan teks ke dalam kategori tertentu tanpa memerlukan data pelatihan khusus pada kategori tersebut. Bagi saya, metode ini merupakan solusi inovatif dengan fleksibilitas tinggi, terutama ketika kategori yang dibutuhkan sangat dinamis atau cepat berubah, misalnya dalam analisis tren media sosial atau untuk keperluan bisnis yang membutuhkan adaptasi cepat.

  **Kelebihan Zero-Shot Classification**:
  - **Adaptasi terhadap Topik yang Beragam**: Metode ini memudahkan kita untuk mengklasifikasikan teks ke berbagai topik yang mungkin belum pernah diprediksi sebelumnya. Hal ini sangat bermanfaat untuk aplikasi yang memerlukan penyesuaian terus-menerus, seperti pengawasan isu terkini yang berkembang.
  - **Kesederhanaan dan Efisiensi**: Dengan pipeline dari Hugging Face, zero-shot classification bisa diterapkan hanya dengan menyediakan label kandidat tanpa harus melatih model baru. Ini adalah pendekatan yang cepat dan tidak memerlukan persiapan dataset yang besar.
  - **Penggunaan Sumber Daya yang Efisien**: Karena tidak memerlukan data pelatihan tambahan, zero-shot classification menghemat penggunaan sumber daya komputasi dan biaya pelatihan. Hal ini menjadikannya pilihan ideal untuk proyek dengan anggaran terbatas atau waktu pengembangan yang singkat.

- **Pengalaman Menggunakan Model `facebook/bart-large-mnli`**  
  Model `facebook/bart-large-mnli` menunjukkan performa baik dalam mengidentifikasi kategori utama dari berbagai teks yang diuji. Saya menemukan model ini cukup akurat dalam mengidentifikasi kategori teks dengan tingkat keyakinan yang tinggi. Namun, dalam beberapa kasus dengan label yang memiliki keterkaitan atau tumpang tindih, seperti "ekonomi" dan "politik", model terkadang kesulitan memilih kategori yang paling tepat. Hal ini mengajarkan saya pentingnya menyediakan label yang berbeda secara jelas untuk mendapatkan hasil yang lebih baik.

- **Potensi Penggunaan di Berbagai Bidang**  
  Zero-shot classification membuka peluang baru dalam berbagai aplikasi yang memerlukan klasifikasi cepat tanpa persiapan data pelatihan. Saya melihat metode ini sangat berguna untuk:
  - **Automasi Klasifikasi Email**: Mengklasifikasikan email atau pesan sesuai prioritas atau kategori seperti "urgent", "informational", atau "spam", yang dapat meningkatkan produktivitas.
  - **Pendukung Keputusan**: Memberikan klasifikasi awal untuk data dalam jumlah besar yang membantu pengambilan keputusan cepat di bidang seperti manajemen risiko atau analisis pasar.
  - **Pemantauan Berita atau Tren**: Mengidentifikasi topik-topik terbaru secara otomatis berdasarkan teks, sehingga dapat membantu dalam analisis tren atau pelaporan berita.

- **Tantangan yang Saya Temui**  
  Salah satu tantangan utama dalam menggunakan zero-shot classification adalah kebutuhan untuk memahami batasan akurasi ketika diterapkan pada konteks spesifik. Model ini mungkin kurang optimal jika digunakan dalam konteks yang memerlukan tingkat ketepatan tinggi untuk kategori yang saling berkaitan. Dalam situasi seperti ini, saya menyarankan kombinasi antara zero-shot classification sebagai langkah awal yang diikuti dengan analisis mendalam menggunakan model khusus. Pengalaman ini memberikan wawasan tentang pentingnya menyesuaikan metode klasifikasi dengan konteks dan tujuan analisis agar hasil yang didapat lebih akurat.

---

Analisis ini memberikan gambaran bagaimana zero-shot classification dapat diterapkan dalam proyek NLP dengan fleksibilitas tinggi dan efisiensi waktu. Pengalaman pribadi saya menunjukkan bahwa metode ini sangat praktis untuk pengaplikasian awal yang cepat, meskipun memiliki keterbatasan dalam situasi yang memerlukan spesifikasi yang lebih mendalam.
