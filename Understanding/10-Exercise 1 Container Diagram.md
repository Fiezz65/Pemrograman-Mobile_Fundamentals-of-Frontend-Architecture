# 23/02/2026

Hari ini saya menyelesaikan Exercise 1: “Container Diagram”. Latihan ini merupakan kelanjutan dari pembahasan materi ”The C4 Model” sebelumnya yang dikenalkan oleh Simon Brown. Fokusnya ada di level 2, yaitu Container Diagram, di mana kita melakukan zoom in dari System Context Diagram untuk melihat isi sistem secara lebih detail. Latihan ini menggunakan project spec dari GitHub Fullsnack System sebagai contoh yang menggambarkan aplikasi pesan-antar makanan. Di sini saya menggunakan draw.io untuk menggambar Container Diagram karena lebih mudah digunakan.

![Container Diagram](Container-Diagram.png)

# Insight

Dari latihan dan project spec pada GitHub, saya memahami bahwa Fullsnack System terdiri dari 3 aktor, yaitu driver, restoran, dan customer. Selain itu, ada beberapa container utama seperti Customer Web App yang dipakai pelanggan untuk memesan makanan, Restaurant Web App untuk restoran menerima dan memperbarui pesanan, dan Driver Mobile App untuk driver mengambil dan mengantar pesanan. Semua container ini berkomunikasi dengan Core API (Java Spring Boot), yang kemudian terhubung ke Core Database (MySQL) untuk menyimpan data, dan Websockets Server (Socket.io) untuk mengirim update secara real-time ke pengguna. Selain itu, Core API juga berfungsi sebagai penghubung ke sistem eksternal seperti Admin Systems untuk admin Fullsnack dan Third Party Payment untuk memproses transaksi. Insight utama saya adalah bahwa Container Diagram ini membantu saya melihat isi sistem secara lebih jelas, bukan hanya sekadar gambaran umum Fullsnack System seperti di level System Context.

## Impact

Latihan ini membuat saya sadar bahwa membagi sistem ke dalam container itu benar-benar membantu tim. Dengan diagram ini, developer bisa jadi lebih gampang melihat container mana yang terhubung ke API, database, atau layanan lain di luar sistem. Menurut saya, membuat Container Diagram yang jelas itu penting banget, karena diagram ini jadi penghubung antara gambaran umum di level konteks dan detail yang lebih teknis di level komponen. Latihan ini juga membuat saya lebih kebayang bagaimana arsitektur sistem pesan-antar makanan seperti Fullsnack System ini bisa berjalan dalam kegunaannya sehari-hari.