# Sales Dashboard Automation

Proyek ini adalah otomatisasi laporan penjualan menggunakan **n8n**, **Google Sheets**, dan **Google Data Studio / Looker Studio**.  
Laporan akan ter-update secara otomatis berdasarkan data yang masuk.

## Alur Proyek

1. Data penjualan otomatis masuk ke Google Sheets (via n8n workflow).
2. n8n melakukan pemrosesan data (filter, agregasi).
3. Hasil data disimpan ke sheet `Summary`.
4. Dashboard visual dibuat di Google Sheets / Looker Studio.
5. hasil Penjualan per Hari akan di kirim Otomatis ke Telegram.

## Contoh Output

- Workflow n8n: `workflow-n8n.png`
- Dashboard penjualan: `Dashboard.png`
- Ringkasan data: `Summary.png`
- Laporan penjualan per Hari: `Laporan penjualan melalui telegram.png`

## Teknologi yang Digunakan

- **n8n** (otomatisasi workflow)
- **Google Sheets** (penyimpanan data)
- **Google Data Studio / Looker Studio** (visualisasi dashboard)
- **Telegram Bot** (laporan penjualan otomatis per hari)

## Catatan

- Proyek ini bisa dikembangkan untuk menambahkan notifikasi otomatis ke Telegram / Slack.
- Bisa juga diperluas untuk data multi-cabang atau multi-produk.
