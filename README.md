# Seina

This project was created using [Vite](https://vite.dev/guide/) and uses
[TailwindCSS](https://tailwindcss.com/docs/installation/using-vite) for
styling.

## Getting running

Install the dependencies:

``` shell
npm install
```

Run the development server:

``` shell
npm run dev
```

# Managing content

### Adding soundcloud embeds

1. Click "share" on the track in soundcloud, then click the Embed tab.
2. Copy the iframe HTML code.
3. Paste it next to the existing soundcloud iframes.
4. Remove the additional text after the `<iframe>`

### Adding Bandcamp embed

1. Click share/embed on the Bandcamp album, then "embed this album"
2. Click the medium sized option
3. Check the box for "Show tracklist"
4. Choose colors (e.g. black)
5. Copy the iframe embed code
6. Change "width: 400px" in the style attribute to "width: 100%"

### Colors, fonts

The custom colors and fonts are defined in `src/style.css`
