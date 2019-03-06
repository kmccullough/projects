# Sass Projects

## Setup

```
# Setup package.json dependency manifest file
npm init
# Install sass compiler
npm i -D sass
```

## Example package.json and scripts
```
{
  "main": "public/index.html",
  "devDependencies": {
    "sass": "^1.17.2"
  },
  "scripts": {
    "build": "npm run clean ; npm run sass",
    "clean": "rm -rf ./public/build/style/",
    "sass": "sass ./src/style/style.scss ./public/build/style/style.css"
  },
}
```

###Usage

```
npm run build
```

## See Also

* [Sass Starter Project](https://github.com/kmccullough/sass-starter)
