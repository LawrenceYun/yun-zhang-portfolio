# Yun Zhang Portfolio Website

This version tunes the photo layout:

## Homepage portrait

- The circular portrait is about 30% larger than the previous small version.
- The portrait fills the circular frame more naturally.
- The image position is shifted slightly upward with `object-position: center 32%` so photos where the face is in the upper half display better.

If your face still appears too low or too high, edit this line in `style.css`:

```css
object-position: center 32%;
```

Try:
- `center 25%` to show more upper part of the photo
- `center 40%` to show more lower part of the photo

## Group photo

- The group photo keeps the framed + blurred background style.
- The main group image uses `object-fit: contain`, so the full image is shown.
- The group photo area is slightly smaller and more controlled than the previous oversized version.

## Required image filenames

Upload images to the repository root with these exact names:

- `profile.jpg`
- `group-photo.jpg`
