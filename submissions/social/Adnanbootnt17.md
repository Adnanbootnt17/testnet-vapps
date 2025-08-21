# vApp Proposal

## Informasi Dasar
- **Nama Aplikasi:** ChainCircle
- **Kategori:** Sosial
- **Penulis:** Adnanbootnt17
- **GitHub:** [https://github.com/Adnanbootnt17](https://github.com/Adnanbootnt17)
- **Discord ID:** [bootadnan6647](https://discordapp.com/users/bootadnan6647)
## Deskripsi Singkat
ChainCircle adalah platform media sosial berbasis Soundness Layer dengan fokus pada **komunitas on-chain**.  
Pengguna dapat membuat postingan, berinteraksi (like, komentar), dan membangun reputasi yang tervalidasi secara kriptografis menggunakan identitas & zkProofs.  

## Masalah yang Diselesaikan
- Media sosial tradisional tidak transparan & rentan manipulasi (bot/fake account).  
- Sulit membuktikan reputasi atau kontribusi pengguna secara on-chain.  
- Privasi sering dikorbankan karena data dikuasai platform terpusat.  

## Solusi
- Gunakan **Soundness Layer** untuk validasi identitas dan reputasi komunitas.  
- Posting dan interaksi disimpan on-chain sebagai bukti kontribusi.  
- zkProofs menjamin privasi (misalnya: bisa membuktikan reputasi tanpa membuka detail riwayat).  
- Sistem reward berbasis token untuk aktivitas positif.  

## Arsitektur Teknis
- **Frontend:** React + Tailwind (UI sosial mirip forum/timeline).  
- **Backend:** Node.js + GraphQL API.  
- **Blockchain Layer:** Soundness Layer (testnet).  
- **Integrasi:**  
  - SL SDK → otentikasi & reputasi.  
  - IPFS/Arweave → penyimpanan konten (post, komentar).  
  - zkProofs → validasi reputasi tanpa bocor data pribadi.  

## Timeline Pengembangan
1. **Minggu 1–2**: Riset & desain arsitektur, setup repo.  
2. **Minggu 3–4**: Implementasi otentikasi wallet + reputasi dasar.  
3. **Minggu 5–6**: Bangun UI timeline (post, like, komentar).  
4. **Minggu 7**: Tambahkan zkProofs untuk reputasi.  
5. **Minggu 8**: Testing & deploy PoC.  

## Manfaat untuk Ekosistem
- Menunjukkan use case **sosial terdesentralisasi** di Soundness Layer.  
- Memberikan alternatif media sosial bebas bot dengan reputasi on-chain.  
- Menarik komunitas web3 untuk membangun ekosistem sosial yang lebih sehat.
