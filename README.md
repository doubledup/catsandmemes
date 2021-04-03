# Cats and Memes

Small Elm app for searching Giphy.

## Running

As normal, either compile individual files with `elm make` and open the
generated `index.html` with a browser, or start up `elm reactor` and point your
browser at `localhost:8000`

Use `bin/build` to run the Webpack build. This takes files from `public/` along
with `src/Main.elm`, compiles with the optimize flag and minifies & gzips the
result, storing it in `dist/app.js.gz`.

Alternatively, run `bin/optimize` to compile only `src/Main.elm` with the
optimize flag and minify & gzip the result, storing the it in
`minify/elm.min.js.gz`.
