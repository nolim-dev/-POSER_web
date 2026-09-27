# POSER Web

Website statis untuk produk POSER, Self Print, Snapflow, dan Photobooth.

## Isi repository
- `generate.py`, `localize.py`: generator halaman dan lokalisasi.
- `dist/`: hasil build website yang siap di-host sebagai situs statis.
- `pricing.json`, `translations.tsv`: data harga dan terjemahan.
- `supabase/functions/`: fungsi CMS admin.

## Menjalankan build
Memerlukan Python 3. Jalankan:

```bash
npm run build
npm run check
``

Server lokal opsional: `python3 preview.py`.
