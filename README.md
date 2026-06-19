# starrocks-mysql-1fe3be-docker
Dari compose ini, cukup 1 server fisik/VM untuk menjalankan semua container, karena semua service berada dalam 1 Docker Compose:
1 container FE
3 container BE

Total resource yang diminta:
CPU  = 4 + 6 + 6 + 6 = 22 vCPU
RAM limit = 8 + 20 + 20 + 20 = 68 GB
RAM reservation = 6 + 14 + 14 + 14 = 48 GB

Jadi rekomendasi minimum server:
1 server
Minimal: 24 vCPU, 64 GB RAM
Lebih aman: 32 vCPU, 96 GB RAM
Storage: SSD/NVMe, tergantung data StarRocks
 
Punya kami 1 VM 32 vCPU, 82 GB RAM
 
