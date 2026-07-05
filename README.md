# Risk Ledger

Kalkulator position sizing dan jurnal trading dalam satu halaman — bantu kamu menjaga risiko per trade tetap disiplin dan mengevaluasi performa sistem trading secara objektif dari data real, bukan asumsi.

Dibuat sebagai single-file web app (HTML/CSS/JS murni, tanpa build step), jalan langsung di browser dan menyimpan data secara lokal.

## Fitur

**Kalkulator Risiko**
- Hitung nilai risiko per trade dari modal, persentase risiko, RR, dan winrate sistem
- Hitung expectancy sistem (dalam R dan dolar) untuk tahu apakah edge kamu positif
- Hitung ukuran posisi otomatis dari harga entry & stop loss
- Simulasi drawdown dari losing streak beruntun (compounding)

**Jurnal Trading**
- Catat setiap trade: tanggal, pair, arah, hasil, R multiple, dan catatan evaluasi
- Statistik otomatis: winrate real, expectancy per trade, total trade, streak berjalan
- Kurva ekuitas dan visualisasi pola menang/kalah
- Export riwayat trade ke CSV

**Lainnya**
- Mode gelap & terang
- Data tersimpan otomatis di perangkat (tidak hilang saat refresh)

## Cara pakai

Buka `index.html` langsung di browser, atau deploy sebagai static site (GitHub Pages, Vercel, Netlify, dll) — tidak ada dependency atau proses build yang dibutuhkan.

## Disclaimer

Alat bantu evaluasi dan manajemen risiko, bukan sinyal trading atau saran finansial. Keputusan trading tetap sepenuhnya tanggung jawab pengguna.

## Lisensi

MIT
