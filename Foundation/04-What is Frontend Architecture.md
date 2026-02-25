# 11/02/2026

Hari ini saya menyelesaikan materi “What is Frontend Archictecure?”. Materi ini membahas bagaimana definisi arsitektur perangkat lunak dalam frontend, dan keputusan tentang bagaimana kita mengatur lapisan frontend supaya mendukung kualitas yang diinginkan.

## Insight

Dari penjelasan pada video, saya memahami bahwa frontend architecture adalah hal-hal penting di lapisan frontend yang harus dipikirkan sejak awal. Dulu membedakan frontend dan backend itu terasa mudah. Kalau berjalan di client berarti frontend, kalau di server berarti backend. Tapi sekarang batasnya tidak sesimpel itu dan lebih tepat disebut spektrum. Di satu sisi ada HTML, CSS, JavaScript, di sisi lain ada database dan API, sementara framework modern seperti Next.js atau Nuxt ada di tengah. Bahkan ada React Server Components yang bisa melewati sisi keduanya. Namun, dalam materi ini fokusnya ada di area tengah spektrum dan lebih condong ke sisi frontend.

Yang membuat saya tertarik adalah pada contoh dua arsitektur yang berbeda. Pertama, arsitektur dengan gaya Micro-Frontends yang cocok untuk tim besar karena menekankan scalability, deployability, dan maintainability. Kedua, arsitektur dengan gaya Monolithic React Server Components yang lebih cocok untuk tim kecil karena menekankan performance, agility, dan reliability. Walaupun hasil akhirnya mungkin bisa terlihat sama bagi pengguna, ternyata cara kerjanya di balik layar sangat berbeda.

## Impact

Dari materi ini, saya sadar bahwa frontend architecture bukan cuma soal teknis atau sekadar memilih framework, tapi lebih ke arah bagaimana keputusan yang kita buat bisa memengaruhi jalannya aplikasi ke depan. Dua arsitektur yang kelihatannya sama di mata pengguna ternyata bisa punya perbedaan besar di dalamnya. Hal itu membuat saya merasa bahwa setiap keputusan arsitektural memang tidak boleh asal, tetapi harus benar-benar dipikirkan sesuai kebutuhan tim dan kualitas yang ingin dicapai.