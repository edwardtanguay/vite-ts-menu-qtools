# vite-ts-menu-qtools

This is a minimal React site created with Vite with Sass, React Router, CLI command and qtools with Jest testing.

![grafik](https://user-images.githubusercontent.com/446574/200960596-bdc5bd34-ca8c-4c03-9c0f-e67e9bf7d111.png)

## includes

- TypeScript
- Sass
- React Router (v6)
- only one Sass file (`App.scss`) - the file `index.css` was deleted
- CLI with page component creator: `npm run cp`
- page-load flicker bug fixed in index.html:

```html
  <style>
    body {
      background-color: #333;
    }
  </style>
```

## how to install

- download zip
- copy all files to new directory, e.g. `/home/yourname/projects/site001`
- open VSCode in that directory (`code .`)
- `npm i`
- `npm run dev`
