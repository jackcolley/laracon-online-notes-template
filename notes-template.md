# Laracon Online Notes

## 13:45 - Opening Remarks
:tee
--
## 14:00 - Jeffrey Way

### Webpack
- gulp is task runner, webpack isn't
- webpack 2 is used throughout the slides
- webpack: single entry point
- jeff uses npm for everything
- webpack will assume everything comes across is javascript unless we tell otherwise, and we do so by using loader.
- "loader can transform any file that matches a certain criteria" – Jeff
- you can pull loader from npm. for example, to pull `css-loader`, do this:
  `npm install css-loader --save-dev`
- "plugins are the backbone of webpack. webpack itself is built on this same plugin system"

webpack:

- tree shaking: remove unused code
- example:

```
npm install webpack --save-dev
webpack src/main.js dist/bundle.js
```

put the webpack in `package.json` to make your life easier. exec `npm run dev` to run it.

```
"scripts": {
    "dev": "webpack src/main.js dist/bundle.js"
}
```

### Laravel Mix
- laravel mix helps you configuring webpack
- mix covers 80% use case, and very likely you'

--
## 15:00 - Evan You

--
## 16:15 - Rachel Andrew

--
## 17:15 - Adam Wathan

--
## 18:30 - Taylor Otwell

--
## 19:30 - Nick Canzoneri

--
## 20:45 - Jason McCreary

--
## 21:45 - Matt Stauffer

