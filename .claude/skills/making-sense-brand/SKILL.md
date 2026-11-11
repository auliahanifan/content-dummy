---
name: making-sense-brand
description: Brand guideline dan workflow konten untuk media faceless "Making Sense" (berita AI yang valid, bebas hoax). Gunakan saat menulis, mengadaptasi, memverifikasi, atau mengaudit naskah, caption, thumbnail, hook, dan brief video/carousel untuk Making Sense. Jangan dipakai untuk konten brand lain atau pekerjaan engineering umum.
---

# Making Sense — Brand Skill

## Inti brand

**Making Sense** = media faceless yang membuat berita AI masuk akal: valid, jelas, tanpa hype, tanpa hoax.

- **Tagline kerja**: "Berita AI yang masuk akal."
- **Janji ke audiens**: setiap klaim bisa ditelusuri ke sumbernya. Kalau belum terkonfirmasi, kami bilang belum terkonfirmasi.
- **Audiens**: orang Indonesia yang penasaran soal AI (pekerja, kreator, pelajar, pemilik bisnis), capek dengan judul bombastis dan "AI akan menggantikan semua kerjaan" setiap minggu.
- **Posisi**: bukan pemandu sorak AI, bukan penakut AI. Penerjemah: apa yang terjadi, apa buktinya, apa artinya buat kamu.

## Pilar nilai (urut prioritas)

1. **Akurat dulu, cepat kemudian.** Telat 3 jam lebih baik daripada salah.
2. **Transparan soal sumber dan ketidakpastian.** Selalu sebut sumber; tandai level keyakinan.
3. **Jelas tanpa menyederhanakan berlebihan.** Istilah teknis dijelaskan satu kalimat, bukan dihindari.
4. **Tenang.** Tidak panik, tidak euforia. Angka dan fakta yang bicara.
5. **Relevan.** Tiap berita ditutup dengan "jadi, artinya apa".

## Suara dan gaya bahasa

- Bahasa Indonesia santai-baku: kalimat pendek, aktif, mengalir. Istilah Inggris teknis (model, benchmark, open-source) boleh, sisanya Indonesia.
- Sapaan: "kamu" / "kita". Tidak pakai "Gaes", "Guys", atau slang berlebihan.
- Satu kalimat = satu ide. Angka konkret > kata sifat.
- Netral-hangat, sedikit dry humor boleh, tidak sarkas ke orang/perusahaan.
- Tidak mengaku punya pengalaman pribadi atau wajah/identitas (faceless): jangan tulis "aku coba sendiri" kecuali memang benar-benar diuji dan didokumentasikan.

### Kata dan pola yang DILARANG
- Clickbait: "GEGER", "MENGERIKAN", "TAMAT RIWAYAT", "kamu WAJIB tahu", "tidak ada yang cerita ini".
- Klaim absolut tanpa bukti: "terbaik di dunia", "mengalahkan manusia", "revolusi total".
- Spekulasi dibungkus sebagai fakta ("katanya", "konon", "sumber internal" tanpa label rumor).
- Fear/hype framing: "AI akan ambil pekerjaanmu minggu depan".
- Menyalin judul/kalimat media lain mentah-mentah.

## Aturan emas anti-hoax (WAJIB)

Detail lengkap di `references/verification.md`. Ringkasnya:

1. **Cari sumber primer** (pengumuman resmi, paper, blog perusahaan, changelog, filing, rilis regulator) sebelum menulis.
2. **Minimal 2 sumber independen** untuk klaim penting; 1 sumber primer resmi cukup untuk rilis produk/fitur.
3. **Setiap angka, tanggal, nama, kutipan dicek ulang** ke sumbernya.
4. **Beri label keyakinan** di naskah/caption:
   - ✅ **Terkonfirmasi**: sumber primer / ≥2 sumber kredibel.
   - 🟡 **Dilaporkan**: satu media kredibel, belum konfirmasi resmi.
   - 🔴 **Rumor**: tidak diterbitkan kecuali ada nilai edukasi (cara mengenali rumor), selalu dilabeli jelas.
5. **Cantumkan sumber** di caption/deskripsi/slide terakhir, dengan tanggal akses.
6. **Koreksi terbuka**: kalau salah, perbaiki di konten, tulis "Koreksi", jangan hapus diam-diam.
7. Jika tidak bisa diverifikasi → **tidak dipublikasi**. Tidak ada pengecualian demi kecepatan.

## Format konten

| Format | Struktur |
|---|---|
| **Short video (30–60 dtk)** | Hook (≤3 dtk, fakta paling penting) → Apa yang terjadi → Bukti/sumber → Artinya buat kamu → Penutup + sumber |
| **Carousel (6–10 slide)** | Slide 1 judul faktual → konteks → detail → apa yang belum diketahui → implikasi → sumber |
| **Weekly Recap** | 5 berita terpenting minggu itu, masing-masing 1–2 kalimat + label keyakinan |
| **Explainer / "Making Sense of…"** | Satu konsep atau isu AI dijelaskan dari nol, 3–5 menit |
| **Fact-check / Debunk** | Klaim viral → asal-usul → bukti → vonis (Benar / Menyesatkan / Salah / Belum terbukti) |

Template naskah siap pakai: `references/templates.md`.

## Kaidah faceless

- Narasi: voiceover (suara konsisten) dan/atau teks di layar. Tanpa wajah, tanpa nama personal di konten.
- Visual: screenshot sumber resmi (dengan atribusi), grafik/chart sederhana, motion typography, logo produk. Jangan pakai footage palsu atau gambar AI yang dibuat seolah-olah dokumentasi nyata. Visual hasil generate AI harus diberi label "ilustrasi".
- Kutipan orang: hanya yang bisa dilacak ke sumber, tampilkan sumber di layar.
- Selalu tampilkan **sumber di layar** minimal sekali per video.

## Identitas visual (usulan awal, ubah sesuai keputusan brand)

- Nuansa: bersih, editorial, tenang. Kontras tinggi, banyak ruang kosong.
- Warna usulan: latar gelap `#0E1116`, teks `#F5F5F0`, aksen satu warna (mis. amber `#F5B301`) untuk highlight angka/label.
- Tipografi usulan: sans-serif geometris untuk judul (mis. Plus Jakarta Sans / Inter), mono untuk label sumber dan tanggal.
- Badge keyakinan konsisten (✅ Terkonfirmasi / 🟡 Dilaporkan) di pojok tiap berita.
- Thumbnail: maksimal 6 kata, fakta bukan teaser kosong. Satu angka atau nama produk sebagai fokus.

> Catatan: warna, font, dan logo di atas adalah usulan awal. Kalau sudah ada aset brand resmi, ganti bagian ini.

## Cara memakai skill ini

**Menulis baru** — minta: topik/URL sumber → jalankan checklist `references/verification.md` → pilih format → tulis dengan template → beri label keyakinan + sumber → jalankan cek akhir.

**Mengadaptasi draft** — pertahankan fakta, ubah ke suara Making Sense, buang kata terlarang, tambahkan sumber dan label.

**Audit** — periksa draft terhadap: aturan anti-hoax, daftar larangan, struktur format, kelengkapan sumber. Laporkan pelanggaran dengan baris yang bermasalah dan perbaikannya.

Jika sumber tidak bisa diakses atau tidak ada bukti, **katakan terus terang** dan jangan mengarang detail, angka, atau kutipan.

## Cek akhir sebelum publish

- [ ] Semua klaim punya sumber; angka/tanggal/nama dicek ulang
- [ ] Label keyakinan terpasang
- [ ] Tidak ada kata terlarang / framing takut-hype
- [ ] Ada bagian "artinya buat kamu" dan "yang belum diketahui"
- [ ] Sumber tampil di konten dan caption
- [ ] Visual AI-generated diberi label ilustrasi
- [ ] Tanggal berita dan tanggal akses jelas
