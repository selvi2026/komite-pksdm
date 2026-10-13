# Panduan Portofolio Komite PKSDM

Situs ada di folder `docs/`:

- `index.html` : tampilan portofolio (tidak perlu diubah)
- `data/data.json` : seluruh data kelompok dan program
- `bukti/` : dokumen dan screenshot bukti kegiatan

## 1. Mengaktifkan situs (sekali saja)
1. Repo di GitHub, lalu **Settings > Pages**.
2. Source: **Deploy from a branch**, pilih branch utama (`main`) dan folder **/docs**, lalu Save.
3. Link situs muncul di halaman itu, biasanya `https://selvi2026.github.io/komite-pksdm/`. Kirim link ini ke atasan.

## 2. Membuat token edit (sekali saja, hanya untuk Anda)
1. GitHub: foto profil > **Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate new token**.
2. Repository access: **Only select repositories**, pilih repo ini.
3. Permissions > Repository permissions: **Contents = Read and write**.
4. Generate, lalu salin token. Jangan dibagikan ke siapa pun.

## 3. Mengedit portofolio
1. Buka `https://<link-situs>/#edit`, lalu tempel token dan isi nama branch (`main`).
2. Tombol **+ Program**, **+ Kelompok**, dan **Ubah** muncul. Setiap simpan langsung masuk ke GitHub, dan situs terbarui dalam sekitar 1 menit.
3. Dokumen bukti diunggah langsung dari form program (maks. 20 MB per file).
4. Orang lain yang membuka link biasa hanya bisa melihat. Tanpa token, tidak ada yang bisa mengubah isi.

## Catatan
- Token disimpan di browser Anda. Pakai browser pribadi, dan klik **Keluar mode edit** di komputer bersama.
- GitHub Pages pada paket gratis bersifat publik. Jangan unggah dokumen yang rahasia.
- Data contoh bisa dihapus lewat tombol **Hapus semua data contoh** di mode edit.
