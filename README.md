# Svelte Issue

 - Node `12.16.0`
 - Yarn `1.17.13`
 - `git clone` this repo
 - `cd dependencies/foo && yarn && yarn prepublish && cd ../../`
 - `yarn`
 - `yarn build`
 - `cd dist && python3 -m http.server && cd ../`

# Problem

`App.svelte` - compilation is successful, but `foo` is not resolving at runtime due to `exports` not being defined, resulting in a 500 internal server error.

At runtime, open dev tools and look at console to see error.

Error image: [at imgur](https://imgur.com/a/XaZnWCx)
