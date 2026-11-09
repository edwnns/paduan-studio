# Paduan Studio

Editor partitur paduan suara (SATB) berbasis not angka. Satu file `index.html`, berjalan langsung di browser tanpa server.

## Fitur
- Tulis not angka per suara (Sopran, Alto, Tenor, Bass, plus Solo/Mezzo opsional), akor, dan lirik bertingkat (beberapa bait).
- Bar dipotong otomatis sesuai birama, semua suara sejajar per ketukan.
- Tanda ulang, volta, segno/coda, D.S./D.C., modulasi, slur, triol, fermata, staccato, dinamik, crescendo/diminuendo.
- Tampilan not angka, not balok, atau keduanya.
- Harmonisasi otomatis A/T/B dari Sopran + akor (6 gaya), dan tebak akor dari melodi.
- Putar dengan piano/organ/vokal, sorot not yang sedang berbunyi, metronom, hitungan masuk, swing, ulang birama, pilih suara yang didengar.
- Ekspor PDF (lewat dialog cetak), MIDI, WAV, dan file lagu (.json).
- Lagu tersimpan otomatis di browser (localStorage).

## Menaruh di GitHub Pages
1. Buat repository baru di GitHub (misal `paduan-studio`).
2. Unggah `index.html` (Add file → Upload files) ke repository itu.
3. Buka Settings → Pages → Source: "Deploy from a branch", pilih branch `main` dan folder `/ (root)`, lalu Save.
4. Setelah 1–2 menit, aplikasi bisa dibuka di `https://<username>.github.io/paduan-studio/`.

Catatan: not balok memakai pustaka abcjs dari CDN jsDelivr, jadi butuh internet saat pertama dibuka. Lagu yang disimpan di satu browser tidak otomatis muncul di browser/perangkat lain; pakai Berkas → Simpan file lagu untuk memindahkannya.
