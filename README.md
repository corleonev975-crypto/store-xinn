# XinnStore Full Starter

Ini starter project untuk flow yang kamu minta:
- homepage ala marketplace top up
- klik game -> halaman detail top up
- pilih nominal
- pilih payment (DANA/QRIS/GoPay)
- sticky button bawah
- admin panel
- flow DANA manual -> admin klik LUNAS -> backend trigger top up API stub

## Jalankan frontend cepat
Buka folder `public` dengan static server apa saja.

## Jalankan backend
```bash
cd backend
npm install
cp .env.example .env
npm start
```

## Login admin demo
- email: admin@xinnstore.com
- password: ChangeMe123!

## Catatan penting
- Desain ini terinspirasi dari flow marketplace top up, bukan clone mentah situs lain.
- Untuk transaksi real yang benar-benar otomatis, kamu tetap harus isi kredensial supplier/API milikmu sendiri.
- Flow pembayaran pada starter ini adalah DANA/QRIS manual, lalu admin verifikasi pembayaran sebelum kirim diamond.
