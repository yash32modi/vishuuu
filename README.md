# ek chhoti si baat 💌

A cute pink cat-meme love confession site for your girl.

## What's in the img/ folder

- `1.png` through `6.png` — the 6 cat memes (already added)
- You need to add ONE more photo: **a photo of you two together**
  - Name it `us.jpg` (or `.png`)
  - Put it in the `img/` folder

## How to add your real photo (the final slide)

Open `index.html` and find this line (around line 270):

```html
<div class="final-photo-placeholder">📸</div>
```

Replace it with:

```html
<img src="img/us.jpg" class="final-photo" alt="us">
```

(if your photo is `.png` instead of `.jpg`, change accordingly)

## How to edit the final letter

Find the `<p class="letter">` section in `index.html` and replace with your own words. Keep it real, not poetic. The cat memes already did the cute part — the last slide should sound like YOU.

## How to test

Just double-click `index.html` — opens in browser.

## Background music idea

If you want music when she opens it, add this just before `</body>`:

```html
<audio autoplay loop>
  <source src="song.mp3" type="audio/mpeg">
</audio>
```

(put any soft romantic song as `song.mp3` in the same folder)
