# 11/02/2026

Hari ini saya menyelesaikan materi "Software Design vs Architecture". Materi ini membahas perbedaan antara arsitektur dan desain.

## Insight

Dari penjelasan pada video, saya memahami bahwa arsitektur dan desain itu bukan dua hal yang terpisah, melainkan sebuah spektrum. Di sisi arsitektur, keputusan biasanya sulit diubah, sifatnya strategis, dan berada di level yang lebih tinggi. Sedangkan di sisi desain, keputusan lebih mudah diubah, sifatnya taktis sehari hari, dan lebih detail di level kode.

Contoh yang diberikan juga cukup membantu saya untuk memahaminya. Misalnya, memilih gaya arsitektur seperti Micro-Frontends atau Monolithic SPA jelas masuk ke arsitektur karena sulit diubah dan punya dampak besar jangka panjang. Sedangkan keputusan seperti berbagi global state dengan signals posisi spektrumnya agak di tengah-tengah. Ada di sisi arsitektural karena melibatkan tim dan punya dampak, tapi juga ada di sisi desain karena menyangkut implementasi kode.

## Impact

Dari materi ini, saya sadar bahwa tidak semua keputusan itu punya bobot yang sama. Ada keputusan besar yang harus benar-benar dipikirkan secara matang karena dampaknya panjang, dan juga ada keputusan kecil yang tidak perlu terlalu lama diperdebatkan. Dengan memahami spektrum antara arsitektur dan desain, saya merasa lebih bisa menilai seberapa serius sebuah keputusan harus diperlakukan. Intinya, dari yang saya tangkap adalah jangan meremehkan keputusan arsitektural, tapi jangan juga membesar-besarkan hal-hal kecil di level desain.