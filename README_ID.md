# NAKA AAC — publikasi GitHub Pages

## Fitur
- Papan komunikasi AAC dengan kartu bergambar.
- Kartu dan penghapusan kartu disimpan di browser/perangkat yang sedang digunakan.
- Pengaturan suara perangkat, kecepatan, dan nada; pilihan suara bergantung pada perangkat/browser.
- PWA dengan cache offline setelah pertama kali dimuat dan manifest untuk instalasi.

## Cara mengaktifkan GitHub Pages
1. Buat repository baru di GitHub, misalnya `naka-aac`.
2. Unggah **isi folder ini** ke root repository: `index.html`, `manifest.webmanifest`, `sw.js`, folder `icons`, dan README.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
5. Tunggu sampai GitHub menampilkan URL `https://USERNAME.github.io/naka-aac/`, lalu buka URL tersebut.
6. Tes tambah kartu, refresh halaman, dan buka ulang. Instalasi PWA memerlukan HTTPS dan browser yang mendukung.

## Instalasi perangkat
- **Android:** buka URL HTTPS di Chrome → menu ⋮ → *Install app* / *Tambahkan ke layar utama*.
- **iPhone/iPad:** buka URL di Safari → tombol Share → *Add to Home Screen*.
- **Windows/macOS/Linux:** buka URL di Chrome atau Edge → ikon instal di address bar atau menu browser.

## Penting tentang penyimpanan
Kartu tersimpan lokal pada browser/perangkat tempat kartu dibuat. Data tidak otomatis tersinkron antar perangkat atau browser. Jangan hapus data situs/browser jika ingin mempertahankannya. Untuk sinkronisasi akun antar perangkat diperlukan backend/database dan autentikasi tambahan.

## Penting tentang suara
Aplikasi memakai Speech Synthesis yang disediakan perangkat/browser. Daftar suara berbeda-beda dan suara anak Bahasa Indonesia mungkin tidak tersedia. Slider mengatur kecepatan dan nada yang didukung browser; ini bukan rekaman suara anak asli.
