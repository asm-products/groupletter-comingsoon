# Groupletters.io - Coming Soon page

The temporary page for letting the world now that Groupletters.io is coming.

## Development instructions

### Needed on your computer:
- Node
- Ruby
- Sass

### Run when starting:
- `npm install`

### Run when developing:
- `gulp`
- Local test server is now available at [localhost:8080](http://localhost:8080)

### Run to deploy to gh-pages:
- `gulp build` (there is a bug in here, see below)
- Now visible at [asm-products.github.io/groupletter-comingsoon](http://asm-products.github.io/groupletter-comingsoon/)

## Bugs
- When running `gulp build` the changed css is not always committed and pushed to the server. A work around is to first do `gulp deploy` and then run `gulp build`. If you know a fix, you're welcome to fix it!
