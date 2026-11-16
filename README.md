# Joseph King Photography

Live at https://stillsfromjk.github.io

## Folder layout

```
index.html
.nojekyll
images/
  hero.jpg
  WEDDINGS/   weddings-01.jpg ... weddings-06.jpg
  PORTRAITS/  portraits-01.jpg ... portraits-06.jpg
  EVENTS/     events-01.jpg ... events-06.jpg
  FASHION/    _MG_2720.jpg, _MG_2723.jpg, _MG_2743.jpg, _MG_2848.jpg, __8274.jpg.jpg, __8351.jpg.jpg
  PRODUCTS/   products-01.jpg ... products-06.jpg
```

The `images` folder is the Drive "WEBSITE" folder with its original names.

Keep the `.nojekyll` file. Without it, GitHub Pages hides every file that starts with an underscore, and the fashion photos disappear.

## Changing photos

Swap a photo by uploading a new file with the same name into the same folder.
To add or rename photos, edit the `FILES` list near the top of the script in `index.html`.

## Moving to a custom domain later

Repo Settings, then Pages, then Custom domain. Enter the domain and add the DNS records GitHub shows.
Then update the two `stillsfromjk.github.io` links in the `<head>` of `index.html`.
