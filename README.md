# CineVocab

This is a single-page vocabulary learning site hosted on GitHub Pages.

## Add real film/TV images (recommended)

1. Put your images in:

`images/`

2. Use these filenames (already referenced in `index.html`):

- `images/zhenhuan.jpg`
- `images/langyabang.jpg`
- `images/chenqingling.jpg`
- `images/liulangdiqiu.jpg`
- `images/wujiandao.jpg`
- `images/yewen.jpg`
- `images/zhanlang2.jpg`

3. Image size (important)

- The site will display posters at a **fixed size** (cards: **84×112**, flashcards: **96×128**).
- Any image will be auto-cropped with `object-fit: cover`, but for best results, use a vertical poster-like image (e.g. 3:4).

## Update the website

```bash
cd "/Users/ajz/Library/CloudStorage/OneDrive-Personal/Coding/vocab-cinema"
git add -A
git commit -m "Update CineVocab"
git push
```