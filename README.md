**Nama**: Alyssa Layla Sasti  <br /> 
**Kelas**: AdPro B  <br />
**NPM**: 2306152052 <br />

## REFLECTION MODULE 10 BROADCAST-CHAT
2.1 Original code of broadcast chat
- Server
![broadcast1](images/broadcast1.png)
- Client 1
![broadcast2](images/broadcast2.png)
- Client 2
![broadcast3](images/broadcast3.png)
- Client 3
![broadcast4](images/broadcast4.png)

1. Bagaimana cara run server? <br />
Jalankan command `cargo run --bin server`
2. Bagimana cara run 3 client? <br />
Jalankan command `cargo run --bin client` pada 3 terminal berbeda
3. What happens when you type some text in the clients. <br />
Ketika menjalankan server, server akan terconnect atau listening kepada request yang masuk di port 2000. Terlihat ketika client 1, client 2, dan client 3 connect, pada server akan muncul "New connection from ...(port berapa). Kemudian pada setiap terminal client akan ada "From server:..." Menandakan client sudah terconnect dengan server. Dengan begitu semua server dan client akan terhubung satu sama lain. Server akan mendapat semua pesan yang dikirimkan masing - masing clientnya. Kemudian pesan dari satu client akan didapatkan oleh client-client yang lain via server.
