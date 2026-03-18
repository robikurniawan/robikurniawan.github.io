---
title: Dunia World
date: 2025-03-18
---

# Halo Dunia

Ini adalah post pertama di blog. Selamat datang!

## Cara Menulis Blog

1. Buat file `.md` di folder `blog/` (contoh: `judul-post.md`)
2. Tambahkan front matter di awal file:

```yaml
---
title: Judul Post
date: 2025-03-18
---
```

3. Tulis konten dengan Markdown
4. Daftarkan di `blog/posts.json`:

```json
{
  "slug": "judul-post",
  "title": "Judul Post",
  "date": "2025-03-18",
  "excerpt": "Ringkasan singkat..."
}
```

5. Slug harus sama dengan nama file (tanpa .md)
