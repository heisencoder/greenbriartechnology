# Team photos

This folder holds the portrait images shown on the **/team** page.

The `*.svg` files here are **on-brand placeholders** (initials on a dark
terminal background). To use a real photo:

1. Drop a square image into this folder, e.g. `josef-schroeter.jpg`
   (recommended: at least 600×600px, square, JPG or WebP).
2. Update that person's `photo` field in `src/pages/team.astro` to point at the
   new file, e.g. `photo: '/team/josef-schroeter.jpg'`.

That's it — the page picks it up on the next build.

> Note: don't hotlink LinkedIn profile images. Those URLs are signed and expire,
> and embedding them breaks LinkedIn's terms. Download/export the photo (with the
> person's permission) and commit it here instead.
