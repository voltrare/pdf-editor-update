# PDF Editor

No install. No server. ¯\\\_(ツ)\_/¯ https://pdf-editor.now.sh

![It just works!](https://i.imgur.com/m3weLXQ.gif)

## How to use pdf-editor?

1. Click `Choose PDF` to upload a `.pdf` file.
2. Add images, signatures, text, freehand drawing to your PDF.
3. Click `Save`.
4. That's it! All is done **in your browser**.

## How to build this Project?
```
npm i 
npm run dev
```

## Features

- Resize and move everything.
- Add signatures.
- Draw on page.
- Adjust line height, font size, font family.
- Mobile friendly.
- Drag and drop to upload your PDF.
- 支援中文（標楷體）。

## Run locally

```sh
# install dependencies
yarn install
# build assets
yarn build
# run on localhost:5000
yarn start
```

## Docker setup

Run `make build` to create the docker image. Run `make run` to start the container. For reference see [Makefile](./Makefile)


## What's New?

Update and added and features from these PR's [25](https://github.com/ShizukuIchi/pdf-editor/pull/25) [31](https://github.com/ShizukuIchi/pdf-editor/pull/31) [37](https://github.com/ShizukuIchi/pdf-editor/pull/37)


---

LICENSE MIT © 2020 ShizukuIchi
