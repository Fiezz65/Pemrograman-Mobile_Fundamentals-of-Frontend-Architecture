# 24/02/2026

Hari ini saya menyelesaikan Exercise 2: “Architectural Requirements”. Latihan ini melanjutkan pembahasan dari materi sebelumnya tentang requirements dalam arsitektur. Fokusnya adalah menyaring dari daftar functional requirements menjadi influential functional requirements, yaitu fitur-fitur yang paling berpengaruh terhadap desain arsitektur sistem. Latihan ini menggunakan project spec dari GitHub Fullsnack System sebagai acuan lalu saya menyusunnya sendiri dalam bentuk tabel agar lebih jelas hubungan antara fitur, fungsi, dan alasan kenapa fitur tersebut saya anggap penting.

| Fitur | Fungsi | Alasan |
|-------|--------|--------|
| Fitur Rekomendasi Makanan | Aplikasi memberi rekomendasi restoran dan makanan sesuai selera dan riwayat pesanan pelanggan. | Arsitektur sistem harus sanggup memproses perhitungan data riwayat yang lumayan berat. |
| Fitur Penjadwalan Pesanan | Pelanggan bisa mengatur jadwal pengiriman atau pengambilan pesanan. | Sistem membutuhkan mekanisme untuk menyimpan antrean pesanan dan mengeksekusinya secara otomatis pada waktu yang tepat. |
| Fitur Simpan Info Pembayaran | Pelanggan bisa menyimpan data pembayaran untuk pesanan berikutnya. | Penyimpanan data rahasia seperti nomor kartu kredit memunculkan risiko keamanan yang sangat tinggi. |
| Fitur Filter Pencarian Restoran | Pelanggan bisa menyaring hasil pencarian restoran berdasarkan jarak dan waktu pengiriman. | Database bekerja ekstra keras untuk menghitung jarak lokasi antara pelanggan dan restoran secara langsung. |
| Fitur Notifikasi Pesanan dan Ulasan | Pelanggan mendapat notifikasi status pesanan dan balasan ulasan dari restoran. | Aplikasi berpotensi terasa lambat atau berhenti sejenak jika proses pengiriman notifikasi mengganggu alur kerja utama. |
| Promo/Voucher | Pelanggan bisa pakai kode promo atau voucher. | Sistem harus punya mekanisme validasi promo atau voucher yang aman dan tidak mengganggu proses order. |
| Favorit/restoran rekomendasi | Pelanggan bisa menyimpan restoran favorit. | Sistem harus menyimpan preferensi user dan memengaruhi rekomendasi. |

## Insight

Dari latihan ini saya jadi paham kalau tidak semua fitur benar-benar mengubah arsitektur. Ada yang sekadar bikin aplikasi lebih nyaman dipakai, tapi ada juga yang bikin sistem harus dipikirin lebih serius, seperti rekomendasi makanan, penjadwalan pesanan, simpan info pembayaran, filter pencarian, notifikasi, promo, dan favorit restoran. Insight utama saya adalah bahwa daftar influential functional requirements ini membantu saya melihat fitur mana yang benar-benar berpengaruh ke arsitektur sistem, bukan hanya sekadar daftar fungsi umum dari Fullsnack System.

## Impact

Latihan ini bikin saya sadar kalau arsitektur sistem itu bukan sekadar memenuhi semua kebutuhan yang tertulis, tapi juga harus siap menghadapi fitur-fitur yang punya konsekuensi besar. Dengan begitu saya bisa lebih fokus ke hal-hal yang penting, misalnya keamanan data pembayaran, performa database, dan fitur real-time. Jadi makin jelas buat saya kenapa dokumen requirements itu penting, yaitu supaya keputusan arsitektur nggak asal-asalan, tapi benar-benar sesuai dengan kebutuhan aplikasi di dunia nyata.