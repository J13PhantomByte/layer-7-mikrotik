# Langkah-Langkah Membuat Layer 7 Protocol di MikroTik

## 1. Masuk ke Menu Firewall dan Pilih Layer 7 Protocol
- Buka antarmuka **MikroTik RouterOS** Anda.
- Navigasikan ke menu **Firewall**.
- Pilih **Layer 7 Protocol** dari daftar yang tersedia.

## 2. Buat Layer 7 Protocol Baru
- Klik tombol **Add** untuk menambah aturan baru.
- Berikan nama yang sesuai untuk protokol baru ini, misalnya: `Blokir Linux dan Ubuntu`.

## 3. Masukkan Regular Expression untuk Blokir Situs
- Pada kolom **Regex**, masukkan ekspresi reguler berikut untuk memblokir situs terkait Linux dan Ubuntu:
  
  ```regex
  ^.+(linux.org|ubuntu.com).*$ 
