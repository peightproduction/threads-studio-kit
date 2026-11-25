# Threads Studio (percuma)

Bantuan **Claude** untuk Threads kau: tulis post, rancang jadual, tengok nombor kau, dan (ikut pilihan) post terus dari dashboard.
Dibuat oleh [@asmosautoflow](https://www.threads.com/@asmosautoflow). Percuma, lesen MIT.

## Pilih satu

| | Untuk siapa | Apa kau dapat | Apa kau perlu | Masa |
|---|---|---|---|---|
| **Mudah**: [`START.md`](START.md) | Semua orang, termasuk Claude percuma | Dashboard dalam chat (Hari ni, Studio, Kalendar, Analitik, Menang, Nota), draf, poster Canva, post **satu tekan** melalui pautan rasmi Threads | Hanya akaun Claude | 2 minit |
| **Zernio (beta)**: [`START-ZERNIO.md`](START-ZERNIO.md) | Nak post, jadual dan simpan draf dari dashboard tanpa bina apa-apa | Semua di atas + butang Post / Jadual / Simpan draf melalui penyambung Zernio | Akaun Zernio percuma (2 akaun pertama), Threads disambung melalui akaun Instagram Business atau Creator. Claude percuma: ini jadi satu-satunya custom connector | 15 minit |
| **Penuh**: [`SETUP-FULL.md`](SETUP-FULL.md) | Yang sanggup setup sendiri | Connector sendiri: jadual automatik, bank gambar, nombor sebenar, komen | Akaun Meta developer, GitHub, Vercel, cron-job.org, komputer riba | 30 hingga 45 minit |

## Cara guna (sama untuk semua)
1. Klik nama fail di atas, contohnya `START.md`.
2. Tekan ikon **Copy raw file** (dua segi empat kecil, di atas kanan kotak fail).
3. Buka **chat baharu** di claude.ai, tampal, tekan Enter, dan taip `start`. Claude pandu kau langkah demi langkah.

## Jujur tentang had
- **Mudah:** Claude tak boleh baca atau ubah akaun Threads kau. Kau sendiri tekan butang Post. Tiada jadual automatik.
- **Zernio:** Zernio ialah perkhidmatan pihak ketiga. **Zernio pegang sambungan ke akaun Threads kau** dan menerima setiap post yang dihantar melaluinya; harga dan syaratnya ikut Zernio dan boleh berubah. Pilihan ini masih **beta**: belum diuji penuh dengan akaun Zernio sebenar. Dashboard tak boleh hantar sendiri; butang menyalin satu arahan, kau tampal dalam chat dan Claude yang hantar.
- **Penuh:** ambil masa, dan kau tanggung akaun Meta, Vercel dan Redis kau sendiri. Pelan percuma Vercel (Hobby) untuk kegunaan peribadi, bukan komersial.
- Post yang sudah live di Threads tak boleh diedit (Threads tiada edit). Masa dalam waktu Malaysia.

## Keselamatan
- **Jangan tampal kata laluan, token, API key atau kod log masuk dalam chat Claude, dalam isu GitHub atau di mana-mana.** Fail-fail ini tak pernah minta. Kalau Claude atau sesiapa minta, berhenti.
- Fail asli **hanya** ada dalam repo ini (`peightproduction/threads-studio-kit`). Fail yang tampal dalam chat Claude ialah arahan yang Claude akan ikut, jadi ambil dari sini sahaja, bukan daripada salinan orang lain.
- Nak pastikan fail tak diubah? Bandingkan cap jari dengan `SHA256SUMS.txt`. Di Windows (PowerShell): `Get-FileHash START.md -Algorithm SHA256`.
- Jumpa masalah keselamatan? Baca [`SECURITY.md`](SECURITY.md).

## Lesen
MIT, dengan kredit kepada ASMOS Autoflow. Lihat `LICENSE`.
