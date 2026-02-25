# 24/02/2026

Hari ini saya menyelesaikan materi “Architectural Decisions”. Materi ini menjelaskan bahwa keputusan arsitektural biasanya muncul di tahap awal proyek karena belum ada kode yang bisa dijadikan dasar untuk keputusan desain. Keputusan ini sifatnya lebih mendasar, susah diubah, dan punya dampak jangka panjang. Contohnya memilih framework frontend, cara mengatur repositori, apakah perlu vendor pihak ketiga untuk fitur tertentu, sampai urusan monitoring dan reliabilitas.

## Insight

Dari penjelasan video dan dokumen adr.md di GitHub, saya jadi lebih paham bahwa yang penting itu bukan cuma apa yang diputuskan, tapi juga alasan di balik keputusan itu. Untuk mendokumentasikan hal itu digunakan format ADR atau Architectural Decision Record yang berisi konteks, keputusan, dan konsekuensinya. Di proyek FullSnack misalnya, tim memutuskan menggunakan Next.js sebagai framework frontend dan meng-hosting aplikasi di AWS dengan SST. Alasannya karena tim sudah terbiasa dengan Next.js, waktu pengerjaan terbatas, dan ekosistemnya cukup besar sehingga bisa membantu mempercepat proses pengembangan. Dari situ saya melihat bahwa setiap keputusan pasti punya konsekuensi. Ada sisi positif seperti pengembangan yang lebih cepat dan fleksibel, tapi ada juga sisi negatif seperti tanggung jawab penuh terhadap infrastruktur. Ini membuat saya sadar bahwa keputusan arsitektur memang tidak pernah benar-benar tanpa risiko.

## Impact

Materi ini membuat saya jadi paham bahwa keputusan arsitektural bukan sekadar memilih teknologi, tapi juga soal mendokumentasikan alasan dan dampaknya. Dengan begitu, kalau misal suatu saat ada yang bertanya kenapa pilihan ini dibuat, jawabannya sudah jelas tertulis. Materi ini juga membantu saya menyadari bahwa ADR bisa jadi alat sederhana tapi penting untuk menjaga konsistensi dan transparansi dalam perjalanan arsitektur sebuah sistem.