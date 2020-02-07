<p align="center">
  <a href="https://parceljs.org/" target="_blank">
    <img alt="Parcel" src="https://user-images.githubusercontent.com/19409/31321658-f6aed0f2-ac3d-11e7-8100-1587e676e0ec.png" width="749">
  </a>
</p>

# **australia-post**

a super minimal [Parcel](https://parceljs.org/) starter for quick JS prototyping feat. [TailwindCSS](https://tailwindcss.com/) for quick styling.

## Getting Started

Install them packages

```sh
yarn
```

Run the project

```sh
yarn dev
```

Any extra files to be watched should be appended to the `package.json` script.

From there you just need to point Parcel at some of your entry files. Like if
you're building a website, an `index.html` file:

```json
...
  "scripts": {
    ...
    "dev": "parcel index.html index.js MORE.html FILES.js GO.json HERE.css",
    ...
  },
...
```

> Not intended for production use
