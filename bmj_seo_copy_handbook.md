# Dokumen Pegangan SEO & Copywriting — Bumi Mekarsari Jaya

Disusun 14 Oktober 2026. Dokumen ini menyimpan keputusan, data keyword, dan rencana yang kita sepakati, sebagai acuan analisis lanjutan di localhost. Data lengkap ada di `bmj_keyword_planner_master.csv`.

## 1. Keputusan yang sudah disepakati

| Topik | Keputusan |
|---|---|
| Posisi usaha | Supplier dan grosir tanaman hias. Pasokan dari stok kebun BMJ dan jaringan kelompok tani/nursery rekanan di sentra Cipanas. **Tidak ada klaim produksi, budidaya, pembibitan, atau "kebun produksi"** (NIB hanya memuat KBLI perdagangan besar). |
| Pasar | Grosir, reseller, kontraktor lanskap, proyek. **Retail tidak dipakai** (NIB tidak memuat KBLI eceran; MOQ tidak cocok). |
| Jangkauan | Melayani seluruh Indonesia. Rumusan "34 provinsi" vs "seluruh Indonesia" harus diseragamkan, dan syarat karantina tumbuhan antar-area perlu diverifikasi. |
| Garansi | Teks lama berupa data contoh (mock), ditulis ulang dari nol. Istilah yang dipakai: **kebijakan klaim kerusakan pengiriman**. Aturan angka (batas waktu, bukti, solusi) masih menunggu dari BMJ. |
| Alamat | Kantor (legal, sesuai NIB): Kp. Lebak Pasar, Desa Palasari, Kec. Cipanas, Kab. Cianjur 43253. Kebun: Desa Cimacan, Kec. Cipanas (Google Maps: "Kebun bunga hias mekarsari", koordinat -6.716325, 107.0199963). Situs menampilkan keduanya. |
| Nama kebun | Nama listing Google tidak boleh diubah. Dipakai sebagai nama kebun: **Kebun Bunga Hias Mekarsari**, milik PT Bumi Mekarsari Jaya. Belum ada plang nama, disarankan dipasang. |
| Kegiatan di kebun | Perawatan stok, sortir, packing, dan **kunjungan klien dengan janji temu**. Kata yang aman: stok kebun BMJ, sortir kondisi, packing. Kata yang dihindari: produksi, budidaya, petani kami. |
| Kontak | Nomor di situs identik dengan nomor di NIB, padahal nomor operasional yang benar berbeda. **Nomor yang benar masih ditunggu.** |
| Tahun operasi | Operasi formal sejak 2024; 2022 adalah operasional non formal. **Tidak dijadikan poin jual** di situs. Samakan juga di Indotrading dan Google Business Profile. |
| Foto | Ditunda. Foto sumber marketplace/medsos akan diganti foto asli. |
| Cakupan produk (diperbarui) | Tanaman hias **plus** media tanam, pot, tanah (termasuk top soil untuk proyek), dan bonsai taman. Masuk katalog sekarang. Keputusan pemilik: KBLI tidak dijadikan penghambat. |
| Keyword utama | **"tanaman hias" ditambahkan sebagai keyword utama (head term)**, berdampingan dengan "supplier tanaman hias" dan "grosir tanaman hias". |
| Varian lokal | Dipakai, karena BMJ melayani seluruh Indonesia. Lihat bagian 6. |

## 2. Data keyword (Google Keyword Planner, Indonesia)

- **Seed**: 271 keyword (`bmj_seed_keywords.csv`) dimasukkan ke "Get search volume and forecasts".
- **Ide dari URL situs**: 743 keyword dari "Discover new keywords". Tempelan pertama berisi 499 dari 500 baris yang tertera, jadi **satu baris belum teridentifikasi** dan tidak ada di master. Tempelan kedua utuh (243 baris).
- **Ide dari seed "jual tanaman"**: 74 keyword (tempelan ketiga, tanpa baris total di tampilan). Sebanyak 31 di antaranya baru, sisanya sudah ada di master.
- **Master**: 1379 keyword unik (sebagian muncul di lebih dari satu sumber, ditandai di kolom `sumber`). **1198** punya data volume (termasuk pita 0–10), **181** tidak (tanda "—").
- Export CSV dari Keyword Planner gagal, jadi data disalin manual. Kolom "ad impression share" kosong semua dan tidak disertakan.

### Cara membaca
- **Volume berupa rentang** (10–100, 100–1K, 1K–10K, 10K–100K), karena akun tanpa iklan aktif. `vol_min` dan `vol_max` adalah batas rentang, bukan angka pasti.
- **"—" berarti tidak ada data**, bukan nol. Volume sangat kecil sering tampil kosong.
- **Perubahan 3 bulan dan YoY** dihitung dari angka dasar sangat kecil, jangan ditafsirkan.
- **"Persaingan" adalah persaingan pengiklan** (Google Ads), bukan kesulitan SEO. **Bid** (IDR) menandakan nilai komersial bagi pengiklan.
- **Klaster dan relevansi (1–5) adalah heuristik berbasis kata**, dibuat otomatis, bukan penilaian manual. Perlu dikoreksi saat analisis. `skor_prioritas` = relevansi × tingkat volume (0–4).

Jumlah per klaster: Produk/kategori 319, Edukasi/informasional 291, B2B inti 136, Komersial/transaksional 134, Konsumen indoor/rumah 91, Di luar cakupan katalog 82, Umum 78, Bonsai (taman) 67, Material & perlengkapan 53, Bunga (ambigu) 39, Calon reseller (edukasi bisnis) 25, Lokal/kota 25, Konsumen lokal (terdekat) 16, English 9, Brand 7, Kompetitor/marketplace 4, Head term 3.

## 2b. Putaran 2: seed A sampai F

Enam hasil Keyword Planner tambahan (label sumber `r2A` sampai `r2F`). Tiap tempelan hanya memuat **100 baris teratas** dari daftar yang jauh lebih panjang di Planner (A 3.476, B 3.742, C 1.067, D 1.255 baris). Baris di bawahnya tidak tertangkap. E (29 baris) dan F (12 baris) lengkap.

| Kode | Seed (yang tertera di Planner) | Baris |
|---|---|---|
| r2A | jual tanaman hias, grosir tanaman | 100 |
| r2B | toko tanaman hias, grosir tanaman, harga tanaman hias | 99 dari 100 (satu baris tidak teridentifikasi) |
| r2C | tanaman untuk taman, tanaman hias taman, tanaman penutup tanah, pohon untuk taman | 100 |
| r2D | tidak tertera; ide seputar pohon, palem, bonsai, aglaonema, bromelia | 100 |
| r2E | supplier tanaman untuk reseller / toko tanaman / kontraktor / developer, supplier tanaman landscape, tanaman untuk usaha tanaman hias | 29 |
| r2F | sentra tanaman hias, tanaman hias cipanas, supplier/jual/nursery tanaman Cipanas, supplier tanaman Cianjur dan Jawa Barat | 12 |

**Aturan gabung:** satu baris per keyword. Jika keyword sudah ada tanpa data dan putaran ini punya data, data baru dipakai (3 keyword). Jika bid kosong dan putaran ini punya bid, bid diisi (3 keyword). Selain itu data pertama dipertahankan. Bid antar putaran bisa sedikit berbeda dan itu normal.

**Pita baru "0 – 10":** keyword yang dicari sangat sedikit. Berbeda dari "—" (tidak ada data).

### Temuan putaran 2

1. **Keyword supplier B2B hampir tidak dicari.** Semua frasa berikut hanya 0–10 per bulan: supplier tanaman untuk reseller, toko tanaman, kontraktor, developer; supplier tanaman landscape; supplier tanaman Cipanas, Cianjur, Jawa Barat; jual tanaman Cipanas; nursery tanaman Cipanas; sentra tanaman hias Cianjur. Ini menegaskan bahwa SEO hanya pendukung, dan penemuan oleh pembeli B2B datang dari relasi, Google Business Profile, Indotrading, dan penjangkauan langsung.
2. **"sentra tanaman hias" 100–1K, persaingan iklan rendah.** Ini jauh lebih besar dari "supplier tanaman hias" (10–100) dan "tanaman hias cipanas" (10–100), dan sesuai dengan identitas BMJ. Usulan (belum diterapkan): masukkan frasa ini secara natural di meta description dan satu heading beranda atau Tentang Kami.
3. **Pencarian harga per jenis pohon cukup besar.** Rentang 100–1K untuk harga pohon tabebuya, ketapang kencana, kamboja, trembesi, pucuk merah, sikas, palem kuning, palem merah, cemara, bougenville, beringin, anting putri, dan harga rumput gajah mini permeter. Ini mendukung halaman produk "Harga [nama tanaman]" di katalog. Karena harga BMJ saat ini "By Request", perlu keputusan bisnis soal menampilkan kisaran harga partai di halaman produk.
4. **Nama varietas "varigata/variegata" dicari** (ketapang kencana varigata, anting putri varigata, bougenville variegata, beringin varigata, randu varigata, 100–1K), dan "bougenville bidadari" 1K–10K. Hanya relevan jika BMJ memang memiliki varietas itu.
5. **Calon reseller mencari panduan bisnis.** "berbisnis tanaman hias" 100–1K, serta "cara memulai bisnis tanaman hias", "bisnis tanaman hias yang menguntungkan", "cara menjual tanaman hias" (10–100). Ini peluang artikel Wawasan untuk jalur reseller, yang mengarah ke penawaran grosir.
6. **Pencarian "terdekat" besar tetapi bukan pasar BMJ.** "toko tanaman terdekat" 10K–100K, "jual tanaman hias terdekat" 1K–10K. Itu pembeli retail lokal. Satu-satunya pengaruh adalah Google Business Profile.
7. **Banyak keyword di luar cakupan katalog** (anggrek, benih, tanaman sintetis dan plastik, sayuran, hidroponik) ditandai klaster "Di luar cakupan katalog" dengan relevansi 1.
8. **Keyword lanskap bernilai komersial tinggi** (bid atas): hias taman (14.431), tanaman untuk taman (5.752), tanaman untuk taman depan rumah (6.864), rumput hiasan taman (8.414), rumput untuk taman (7.388), pohon untuk taman (4.439), tanaman penutup tanah (4.071). Sebagian besar berniat konsumen rumah tangga. Keyword yang paling pas dengan kategori BMJ: tanaman penutup tanah, pohon untuk taman, pohon rindang untuk taman, tanaman taman tahan panas.
9. **Pot punya volume besar tetapi klik murah:** pot gantung (1K–10K, bid atas IDR 381), pot plastik (bid atas IDR 264), harga pot bunga (bid atas IDR 508). Nilai komersialnya rendah dibanding pohon.

## 3. Temuan utama

**a. Pasar B2B di Google kecil, retail besar.** Keyword inti B2B bervolume 10–100, sedangkan "tanaman hias" 10K–100K, "jual tanaman hias" 1K–10K, "toko tanaman hias" 1K–10K. Hampir seluruh keyword proyek/lanskap/tender/BOQ tidak punya data. SEO akan jadi pendukung. Pilar penemuan lain: Google Business Profile, Indotrading, Instagram, penjangkauan langsung.

**b. "tanaman hias" sebagai head term.** Volumenya tinggi, tetapi niat pencarinya didominasi konsumen dan kompetisinya berat. Perlakuan yang disarankan: dipakai berdampingan dalam frasa B2B (mis. "grosir tanaman hias", "katalog tanaman hias") di title/H1, bukan berdiri sendiri. Halaman kategori dan MOQ yang jelas menyaring pengunjung konsumen.

**c. Peluang terbesar ada di halaman per jenis dan per nama tanaman.** Banyak nama tanaman di katalog BMJ punya volume 100–1K sampai 1K–10K (lihat tabel). Nama Latin ikut dicari (saraca indica, lagerstroemia indica, wrightia religiosa, osmoxylon lineare, syzygium oleina). Nama Latin di katalog harus diverifikasi sebelum dipakai di judul halaman.

**d. Cakupan baru (media tanam, pot, tanah, bonsai) punya permintaan nyata.** "media tanam" 10K–100K, "pot tanaman" 1K–10K, banyak variasi tanah dan pot 100–1K. Pembeli proyek (top soil) kemungkinan memakai istilah berbeda yang belum tercakup di data ini.

**e. Nilai komersial tertinggi (bid atas):** bunga murah (20.406, niat bunga/florist), kontraktor taman (21.379), jual beli tanaman hias (19.423), cemara udang (15.142), jual tanaman (12.728), jual bunga (11.098).

**f. Seed "jual tanaman" menghasilkan niat konsumen murni.** Volume besar ("jual tanaman" 1K–10K, "jual bunga" 1K–10K, "jual bibit tanaman" 1K–10K) tetapi pencarinya pembeli individu, banyak yang mencari "murah" atau bunga (florist). Tidak ada keyword B2B baru dari seed ini. Pengecualian yang berguna: **jual pohon, harga pohon, jual bibit pohon, pohon hias taman** (100–1K, bid atas IDR 3.534–5.290) yang selaras dengan kategori Pohon Peneduh. Klaster "Bunga (ambigu)" ditandai relevansi rendah karena belum jelas apakah relevan dengan stok BMJ. Istilah "bibit" di sini berarti tanaman muda yang dijual, bukan klaim pembibitan, jadi aman dipakai bila BMJ memang menjual tanaman muda.

## 4. Tabel keyword terpilih

### Head, B2B, dan lanskap
| Keyword | Volume/bln | Persaingan iklan | Bid atas (IDR) |
|---|---|---|---|
| tanaman hias | 10K – 100K | Low | 4631 |
| tanaman indoor | 1K – 10K | High | 2967 |
| grosir tanaman | 100 – 1K | Low | – |
| supplier tanaman | 10 – 100 | Low | 7286 |
| supplier tanaman hias | 10 – 100 | Low | 6590 |
| agen tanaman hias | 10 – 100 | Low | – |
| distributor tanaman | 10 – 100 | Low | – |
| distributor tanaman hias | 10 – 100 | Medium | – |
| grosir tanaman hias | 10 – 100 | Low | – |
| katalog tanaman hias | 10 – 100 | Low | – |
| pohon lanskap | 10 – 100 | Low | – |
| pusat grosir tanaman hias | 10 – 100 | Low | – |
| tanaman hias lanskap | 10 – 100 | Low | – |
| tanaman lanskap | 10 – 100 | Low | – |
| tanaman proyek | 10 – 100 | Low | – |

### Produk/kategori (non-indoor)
| Keyword | Volume/bln | Persaingan iklan | Bid atas (IDR) |
|---|---|---|---|
| cemara udang | 1K – 10K | Low | 15142 |
| pohon hias | 1K – 10K | Medium | 6211 |
| pohon hiasan | 1K – 10K | Medium | 6211 |
| calathea lutea | 1K – 10K | Low | 5099 |
| pohon peneduh | 1K – 10K | Medium | 4015 |
| palem botol | 1K – 10K | Low | 3374 |
| kamboja fosil | 1K – 10K | Medium | 3026 |
| tanam sukulen | 1K – 10K | Low | 2871 |
| palem ekor tupai | 1K – 10K | Low | 2397 |
| tanaman rambat | 1K – 10K | Medium | 1969 |
| tanam hias daun | 1K – 10K | Low | – |
| tanaman hias daun | 1K – 10K | Low | – |
| tanaman pohon | 100 – 1K | Low | 5949 |
| tanaman taman | 100 – 1K | Medium | 5239 |
| hias taman | 100 – 1K | Low | 4863 |
| pohon hias taman | 100 – 1K | Medium | 4704 |
| pohon hiasan taman | 100 – 1K | Medium | 4704 |
| pohon pelindung | 100 – 1K | Low | 3772 |
| pohon peneduh yang cepat tumbuh | 100 – 1K | Medium | 3582 |
| adam hawa tanaman | 100 – 1K | Low | 1539 |
| aglaonema lipstik | 100 – 1K | Low | 725 |
| tanaman hias aglaonema | 100 – 1K | Low | 566 |
| agave putih | 100 – 1K | Low | – |
| aglaonema commutatum | 100 – 1K | Low | – |

### Material & perlengkapan (media tanam, pot, tanah)
| Keyword | Volume/bln | Persaingan iklan | Bid atas (IDR) |
|---|---|---|---|
| media tanam | 10K – 100K | Medium | 1314 |
| pot tanaman | 1K – 10K | High | 2999 |
| pot tanaman hias | 100 – 1K | High | 4907 |
| tanaman pot hias | 100 – 1K | High | 4907 |
| tanah tanam | 100 – 1K | High | 1288 |
| tanah buat tanaman pot | 100 – 1K | High | 1178 |
| media tanam harga | 100 – 1K | High | 614 |
| pot hias | 100 – 1K | Medium | – |
| toko pot tanaman | 100 – 1K | Low | – |
| harga tanaman pot | 10 – 100 | Low | – |
| media tanam bogor | 10 – 100 | Medium | – |
| media tanam depok | 10 – 100 | Low | – |
| media tanam hias | 10 – 100 | High | – |
| media tanam indoor | 10 – 100 | High | – |

### Bonsai
| Keyword | Volume/bln | Persaingan iklan | Bid atas (IDR) |
|---|---|---|---|
| tanaman hias bonsai | 100 – 1K | Medium | – |
| toko bonsai | 100 – 1K | Low | – |
| bonsai hias | 10 – 100 | Medium | – |
| bonsai tanaman hias | 10 – 100 | Medium | – |
| harga tanaman hias bonsai | 10 – 100 | Low | – |
| pohon bonsai hias | 10 – 100 | Medium | – |
| pohon buat bonsai | 10 – 100 | Low | – |
| pohon hias bonsai | 10 – 100 | Medium | – |
| pohon yang bisa dibikin bonsai | 10 – 100 | – | – |
| pohon yang bisa dibuat bonsai | 10 – 100 | High | – |

### Varian lokal/kota yang punya data
| Keyword | Volume/bln | Persaingan iklan | Bid atas (IDR) |
|---|---|---|---|
| tanaman hias bogor | 100 – 1K | Low | – |
| tanaman hias jakarta | 10 – 100 | Medium | 7478 |
| jual tanaman hias jakarta | 10 – 100 | Medium | 5950 |
| bogor nursery | 10 – 100 | Low | – |
| jual tanaman hias bogor | 10 – 100 | Low | – |
| jual tanaman hias cipanas | 10 – 100 | – | – |
| jual tanaman hias di bogor | 10 – 100 | Low | – |
| jual tanaman hias di jakarta | 10 – 100 | Medium | – |
| kebun bunga cipanas | 10 – 100 | Low | – |
| media tanam bogor | 10 – 100 | Medium | – |
| media tanam depok | 10 – 100 | Low | – |
| penjual tanaman hias di bogor | 10 – 100 | Low | – |
| petani tanaman hias cipanas | 10 – 100 | Low | – |
| supplier tanaman hias bogor | 10 – 100 | Low | – |
| supplier tanaman hias jakarta | 10 – 100 | – | – |
| tanaman bandung | 10 – 100 | Low | – |
| tanaman bogor | 10 – 100 | Low | – |
| tanaman depok | 10 – 100 | Low | – |
| tanaman di bogor | 10 – 100 | Medium | – |
| tanaman di jakarta | 10 – 100 | Low | – |
| tanaman hias cianjur | 10 – 100 | Low | – |
| tanaman hias cipanas | 10 – 100 | Low | – |
| tanaman hias depok | 10 – 100 | Low | – |
| tanaman hias di bogor | 10 – 100 | Low | – |

## 5. Peta keyword per halaman (diperbarui)

| Halaman | Keyword utama | Pendukung |
|---|---|---|
| Beranda | supplier tanaman hias, grosir tanaman hias | tanaman hias (dalam frasa), grosir tanaman, supplier tanaman, tanaman lanskap |
| Katalog (hub) | katalog tanaman hias | harga tanaman hias, grosir tanaman, nama latin tanaman hias |
| Kategori Pohon | pohon peneduh, pohon pelindung | tanaman peneduh, tanaman pelindung, pohon hiasan taman, pohon lanskap |
| Kategori Rambat | tanaman rambat | tanaman rambat hias, tanaman rambat pagar, tanaman rambat pergola |
| Kategori Sukulen/Agave | tanaman hias sukulen | pohon agave, tanam sukulen |
| Kategori Penutup Tanah & Border | penutup tanah, tanaman border | tanaman pembatas taman, tanaman semak |
| Kategori Berbunga | tanaman hias berbunga | tanaman berbunga, bougenville |
| Kategori Daun Hias | tanaman hias daun, tanaman daun hias | nama jenis (aglaonema, calathea, dracaena, hanjuang) |
| Kategori Palem | palem botol, palem ekor tupai | palem raja, sikas |
| **Baru:** Media Tanam & Tanah | media tanam, tanah tanam | top soil, media tanam harga, tanah buat tanaman pot |
| **Baru:** Pot | pot tanaman, pot tanaman hias | toko pot tanaman, supplier pot tanaman |
| **Baru:** Bonsai Taman | bonsai hias, tanaman hias bonsai | pohon hias bonsai, harga tanaman hias bonsai |
| Layanan Proyek | supplier tanaman proyek, tanaman lanskap | pengadaan tanaman (data kosong, untuk konversi) |
| Tentang Kami / Kunjungi Kebun | tanaman hias cipanas, kebun tanaman hias | kebun bunga cipanas, petani tanaman hias cipanas |
| Wawasan | topik edukasi per artikel | lihat saran di bawah |

Saran topik Wawasan yang punya data: RAB taman, nama latin tanaman hias, cara packing tanaman hias, cara mengirim tanaman hidup, cara kirim tanaman ke luar pulau, tanaman tahan panas untuk taman, tanaman peneduh jalan, tanaman rambat pagar. Artikel "Menghitung Kebutuhan Ground Cover" menargetkan keyword yang tidak punya data.

## 6. Rencana varian lokal (melayani seluruh Indonesia)

- Keyword kota yang punya data baru: Bogor, Jakarta, Jakarta Barat, Depok, Bandung, Medan (volume kecil, 10–100 sampai 100–1K). Kota besar lain (Surabaya, Semarang, Yogyakarta, Makassar, Bali, Palembang, Balikpapan, dst.) **belum diuji**.
- Hindari puluhan halaman kota yang kontennya sama (berisiko dianggap halaman doorway). Buat **beberapa halaman area layanan** (mis. Jabodetabek, Jawa Barat, Jawa Tengah-DIY, Jawa Timur, Sumatera, Kalimantan, Sulawesi, Bali-Nusra) dengan isi nyata: estimasi waktu kirim, ekspedisi, packing, syarat karantina, dan contoh pengiriman.
- Google Business Profile: atur area layanan, bukan hanya alamat kebun.
- Putaran Keyword Planner berikutnya: tambahkan "supplier/grosir tanaman hias + kota", "top soil proyek", "media tanam grosir", "pot tanaman grosir", "bonsai taman".

## 7. Glosarium copy (konsisten di semua halaman)

**Pakai:** supplier tanaman hias, grosir, partai, reseller, kontraktor lanskap, proyek lanskap, stok kebun BMJ, jaringan petani Cipanas, sentra Cipanas, BOQ, penawaran, MOQ, kebijakan klaim kerusakan pengiriman, dikurasi/dicek sebelum dikirim, Kebun Bunga Hias Mekarsari (nama kebun).

**Hindari:** produksi, budidaya, pembibitan, penyemaian, "kebun produksi", "sejak 2022" atau klaim lama berdiri/berpengalaman (operasi formal baru 2024), retail, pembelian rumah, koleksi (untuk konsumen), garansi, terjamin, kualitas terbaik, "siap kirim" untuk semua produk, "murah".

## 8. Hal yang masih menunggu / perlu diputuskan

1. Nomor kontak yang benar (menggantikan nomor di situs yang sama dengan NIB).
2. Aturan klaim kerusakan pengiriman (batas waktu, bukti, solusi, ongkir).
3. Kepastian jangkauan pengiriman dan syarat karantina antar-area.
4. Verifikasi status PKP (Indotrading menulis "Non PKP") dan jawaban FAQ invoice.
5. Verifikasi nama Latin dan kategori produk di katalog (mis. "soka" vs *Saraca indica*, *Agave* vs *Furcraea*, Bougenville di kategori Daun Hias).
6. Selaraskan profil Indotrading (masih menyebut produksi, retail, dan bonsai).
7. Jam kunjungan kebun (situs 08.00–17.00, Google Maps 09.00–17.00) dan pemasangan plang.
8. Total produk 219 vs 218 (jumlah delapan kategori) dan penambahan kategori baru.

## 9. Memuat data di localhost

```python
import pandas as pd
df = pd.read_csv("bmj_keyword_planner_master.csv")
# keyword dengan data volume, urut prioritas
d = df[df.vol_tier > 0].sort_values(["skor_prioritas","bid_atas_idr"], ascending=False)
# per klaster
print(df.groupby("klaster").agg(n=("keyword","count"), vol_maks=("vol_max","max")))
```

Kolom: keyword, sumber (seed, ideas_url, ideas_jual_tanaman, r2A sampai r2F, atau gabungan dengan tanda +), volume_bulanan, vol_min, vol_max, vol_tier (0–4; pita "0 – 10" bertingkat 0 tetapi `volume_bulanan` terisi), perubahan_3bln, perubahan_yoy, persaingan_pengiklan, bid_bawah_idr, bid_atas_idr, di_plan_planner, klaster, relevansi_bmj_1_5, lokasi, skor_prioritas.
