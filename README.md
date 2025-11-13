# Praktikum-Jaringan-Komputer

# Percobaan 2 - Build a Switch and Router Network

Percobaan ini bertujuan untuk membangun dan mengonfigurasi jaringan sederhana yang terdiri dari satu router, satu switch, dan dua PC. Setiap perangkat diatur sesuai dengan tabel alamat IP yang berbeda subnet, kemudian dilakukan konfigurasi dasar pada router dan switch agar dapat saling terhubung.
Langkah-langkah dalam percobaan mencakup pemberian alamat IP pada interface, pengaturan password dan banner keamanan, aktivasi interface dengan perintah no shutdown, serta pengujian konektivitas menggunakan perintah ping.
Pada awalnya, ping antar-PC gagal karena router belum dikonfigurasi sebagai penghubung antar subnet. Setelah konfigurasi interface dan routing diaktifkan, koneksi berhasil dilakukan.
Percobaan ini menunjukkan pentingnya konfigurasi IP, aktivasi interface, dan fungsi router sebagai penghubung antar jaringan (gateway) agar komunikasi data dalam jaringan dapat berjalan dengan baik.

Link Youtube : https://youtu.be/-Zp0zXUaDZ4

# Percobaan 3 - Configure Vlans and Trunking

Percobaan “Packet Tracer – Configure VLANs and Trunking (Physical Mode)” ini bertujuan untuk memahami konsep dan implementasi VLAN (Virtual Local Area Network) serta trunking pada jaringan switch. Pada percobaan ini, dilakukan konfigurasi jaringan dengan dua switch (S1 dan S2) dan dua PC (PC-A dan PC-B). Langkah-langkahnya meliputi pembuatan topologi jaringan, konfigurasi dasar perangkat, pembuatan beberapa VLAN seperti Management (VLAN 99), Operations (VLAN 10), Parking_Lot (VLAN 20), dan Native VLAN (VLAN 1000), serta pengaturan port switch agar terhubung dengan VLAN yang sesuai. Selanjutnya, dilakukan konfigurasi trunking menggunakan protokol 802.1Q agar VLAN dapat dikirimkan melalui satu jalur antar switch tanpa kehilangan identitas VLAN-nya. Hasil akhir menunjukkan bahwa komunikasi antar host dalam VLAN yang sama dapat berjalan dengan baik, sedangkan antar VLAN berbeda membutuhkan Layer 3 device untuk inter-VLAN routing. Percobaan ini memberikan pemahaman tentang bagaimana VLAN meningkatkan keamanan, efisiensi, dan performa jaringan dengan membagi domain broadcast menjadi beberapa segmen logis.

Link Youtube : https://youtu.be/JL5f3u2-DsU 
