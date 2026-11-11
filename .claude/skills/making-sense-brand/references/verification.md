# Verifikasi Berita AI — Making Sense

## Hierarki sumber

| Tier | Contoh | Peran |
|---|---|---|
| **1 — Primer** | Blog/rilis resmi perusahaan, dokumentasi & changelog, paper (arXiv/jurnal), model card, filing & rilis regulator, repo resmi, transkrip/rekaman acara resmi | Dasar klaim |
| **2 — Media kredibel** | Media teknologi/bisnis besar dengan reporter bernama dan rekam jejak koreksi | Konfirmasi, konteks |
| **3 — Sekunder** | Newsletter, analis, pakar independen | Opini/analisis, bukan fakta utama |
| **4 — Tidak cukup** | Akun anonim, screenshot tanpa sumber, "katanya", agregator, konten AI-generated, thread viral tanpa tautan | Hanya petunjuk untuk dicari, tidak boleh jadi dasar |

## Alur verifikasi

1. **Tangkap klaim** secara tepat: siapa, melakukan apa, kapan, angka berapa.
2. **Telusuri ke primer.** Cari pengumuman asli. Jika berita hanya mengutip media lain, ikuti rantainya sampai ujung.
3. **Cek kronologi.** Tanggal terbit asli? Bukan berita lama yang beredar ulang?
4. **Cek angka.** Benchmark: siapa yang mengukur, metodenya, dibandingkan dengan apa? Klaim "x% lebih baik" harus punya baseline.
5. **Cek kutipan.** Ada di sumber asli, konteks utuh, terjemahan tidak mengubah makna.
6. **Cari bantahan.** Apakah perusahaan/pihak terkait sudah membantah atau meluruskan?
7. **Tentukan label** (Terkonfirmasi / Dilaporkan / Rumor) dan tulis apa yang **belum diketahui**.
8. **Catat sumber** (judul, penerbit, URL, tanggal terbit, tanggal akses).

## Red flag hoax AI

- Tanpa tautan ke sumber primer; hanya screenshot.
- Klaim dramatis: "AI sadar diri", "AI menolak dimatikan", "AI ciptakan bahasa sendiri", "AGI sudah tercapai" tanpa paper/pernyataan resmi.
- Kutipan tokoh (CEO, peneliti) yang tidak bisa ditemukan di wawancara/akun resmi.
- Angka sangat bulat atau terlalu bagus, tanpa metodologi.
- Domain mirip situs resmi, atau tulisan yang jelas dihasilkan otomatis.
- Gambar/video/suara yang mungkin deepfake atau hasil generate.
- Urgensi emosional: "SEBARKAN SEBELUM DIHAPUS".
- Rilis "bocor" yang hanya diberitakan satu akun.

## Aturan khusus

- **Rilis produk/model**: sumber primer cukup, tapi angka performa dilabeli "klaim perusahaan" sampai ada evaluasi independen.
- **Benchmark**: sebut siapa yang menjalankan dan versi/tanggalnya.
- **Regulasi/hukum**: rujuk teks regulasi atau rilis resmi, bukan ringkasan media saja.
- **Pendanaan/valuasi/akuisisi**: tanpa konfirmasi resmi atau ≥2 media kredibel → label "Dilaporkan".
- **Keselamatan/risiko AI**: bedakan temuan riset, pernyataan opini, dan skenario hipotetis.
- **Prediksi**: selalu dilabeli prediksi, dengan nama pemberi prediksi.

## Format pencatatan sumber (untuk caption/deskripsi)

```
Sumber:
1. [Penerbit] — "[Judul]" (terbit DD MMM YYYY) — URL
2. ...
Status: ✅ Terkonfirmasi | 🟡 Dilaporkan
Terakhir dicek: DD MMM YYYY
```

## Koreksi

Jika ditemukan kesalahan setelah publikasi: (1) perbaiki konten, (2) tambahkan catatan "Koreksi: ..." dengan tanggal, (3) jangan hapus jejak kesalahan, (4) sebutkan perubahan secara singkat dan jelas.
