# Sapper Issue

 - Node `12.16.0`
 - Yarn `1.17.13`
 - Clone repo
 - `cd dependencies/foo && yarn && yarn prepublish && cd ../../`
 - `yarn`
 - `yarn dev`

# Problem

`index.svelte` - client and server is compiling successfully, but `foo` is not resolved on client resulting in 500 internal server error.

Error image: [at imgur](https://imgur.com/a/edMl6WX)
