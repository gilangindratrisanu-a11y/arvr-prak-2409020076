# Praktikum AR/VR - Pertemuan 1

- Nama : Gilang Indra Trisanu
- NIM  : 2409020076
- Link : https://github.com/gilangindratrisanu-a11y/arvr-prak-2409020076

Project ini berisi scene WebXR pertama menggunakan A-Frame 1.7.1 (Ruang Perkenalan Diri).

---

## Jawaban Pertanyaan Refleksi

1. **Mengapa posisi objek yang terlihat pertama kali oleh pengguna memakai nilai z negatif?**
   Sistem koordinat A-Frame menggunakan sumbu Z di mana arah pandang awal kamera menghadap ke arah Z negatif. Oleh karena itu, agar objek berada di depan mata pengguna saat pertama kali scene dimuat, koordinat Z-nya harus bernilai negatif.

2. **Mengapa WebXR hanya aktif pada HTTPS atau localhost?**
   WebXR memerlukan *secure context* (lingkungan yang aman) untuk melindungi privasi dan keamanan pengguna, terutama terkait izin akses sensor perangkat, kamera, dan data spasial. Alamat HTTP biasa (non-localhost) dianggap tidak aman oleh peramban modern.

3. **Jelaskan perbedaan peran WebXR Device API, three.js, dan A-Frame dengan bahasa Anda sendiri?**
   - **WebXR Device API** adalah standar tingkat rendah dari peramban untuk berkomunikasi langsung dengan perangkat keras XR (seperti headset VR atau ponsel).
   - **three.js** adalah pustaka grafik 3D berbasis JavaScript yang mempermudah pembuatan objek, cahaya, dan kamera tanpa harus menulis kode WebGL murni yang rumit.
   - **A-Frame** adalah kerangka kerja di atas three.js yang membungkus fungsi-fungsi 3D tersebut ke dalam tag-tag HTML yang sederhana dan mudah digunakan.
