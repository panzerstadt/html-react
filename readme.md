# adding html to react

is as easy as the tutorial says it is!

## drawbacks

- no jsx
  - unless you also download babel, which is not recommended for production because it performs all the below in sequence on the client (the browser) EVERY TIME the page is loaded:
    1. downloads
    2. reads your jsx code
    3. compiles
    4. renders
- no autocomplete
  - relies on your memory of react's API
