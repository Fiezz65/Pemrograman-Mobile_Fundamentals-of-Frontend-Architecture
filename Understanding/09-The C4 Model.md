# 22/02/2026

Hari ini saya menyelesaikan materi “The C4 Model”. Model ini dikenalkan oleh Simon Brown. Materi ini menjelaskan cara melihat arsitektur sistem dengan empat level diagram, yang bisa diibaratkan seperti Google Maps untuk kode. Kita bisa zoom in dan zoom out untuk melihat Gambaran besar sampai detail terkecil.

## Insight

Dari penjelasan pada video, saya memahami bahwa ada empat level utama dalam model C4. Level. Yang pertama adalah System Context Diagram, yang menunjukkan sistem kita dan hubungannya dengan pengguna serta sistem eksternal. Level kedua adalah Container Diagram, di mana kita membuka sistem dan melihat isinya seperti web app, mobile app, API, atau database. Level ketiga adalah Component Diagram, yang  memperlihatkan komponen di dalam sebuah container, misalnya controller atau service. Terakhir, level keempat adalah Code Diagram, yang menggambarkan detail di tingkat kode seperti class diagram atau entitiy relationship diagram. Penjelasan ini membantu saya memahami kalau setiap level itu punya tujuan yang berbeda, mulai dari gambaran besar untuk stakeholder non-teknis sampai detail teknis untuk developer.

## Impact

Materi ini bikin saya lebih sadar bahwa arsitektur bukan hanya soal menulis kode, tapi juga bagaimana cara menyajikan gambaran sistem dengan jelas sesuai kebutuhan klien. Context Diagram bisa dipakai untuk menjelaskan ke orang non-teknis, sementara Component Diagram dan Code Diagram lebih cocok untuk tim developer yang lebih ke arah teknis. Melalui tahapan yang ada di model C4 ini, penjelasan arsitektur jadi lebih mudah dipahami dan tidak membingungkan. Saya merasa bahwa penting banget untuk bisa memilih level diagram yang tepat, supaya arsitektur bisa dipahami oleh semua pihak baik orang yang teknis hingga non-teknis sekalipun dengan cara yang sesuai.