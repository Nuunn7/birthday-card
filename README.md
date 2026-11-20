# Happy Birthday card

Пастел пиксел стильтэй, утсанд зориулсан төрсөн өдрийн мэндчилгээ-тоглоом.

## Файлууд

- `index.html` — карт бүхэлдээ
- `manifest.webmanifest`, `icon-192.png`, `icon-512.png` — утасны нүүр дэлгэцэнд нэмэх
- `og.png` — линк хуваалцахад гарах зураг
- `vercel.json` — Vercel тохиргоо

## GitHub

```bash
git remote add origin https://github.com/<username>/birthday-card.git
git push -u origin main
```

## Vercel

vercel.com → Add New → Project → GitHub repo-гоо сонгох → Framework: Other → Deploy

Эсвэл CLI:

```bash
npx vercel --prod
```
