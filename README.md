# cube-styles

## Demo site
[https://gracious-austin-2edcf5.netlify.app/](https://gracious-austin-2edcf5.netlify.app/)

## Proposal:
### Use [CubeCSS](https://cube.fyi/) methodology
- Design Tokens
- **C**ompositional utility classes
- **U**tility classes - propose we use [Tailwind CSS](https://tailwindcss.com/)
- **B**lock level styles (Bespoke styles that utility classes can't cover)
- **E**xeption styling (using `data` attributes)

### Use Tailwind CSS
This will give us all the utility classes we might need out of the box, and is configurable to add custom colours, classes, etc, and can be optimised for production.

### Use SCSS for writing block and exception level classes
This will allow us to nest classes for a more readable dev experience
[https://sass-lang.com/](https://sass-lang.com/)

## To run
- `yarn install` or `npm install`
- `yarn start` to spin up the live-server