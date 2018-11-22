# Create React App And Workbox

Apperently workbox is automatically run when you have a workbox-config.js
and run the build command and then use serve, as recommended by the cra build
command line output. Here are some commands.

```
npm install -g serve
npm run build
serve -s build
```

## TODO

- Host this small app on digital ocean and verify is caching works.
- add images to the app and verify caching works
- modify manifest to locally install the pwa app and test on Android and then iOS

## Done

| Date       | Done                                                              |
| ---------- | ----------------------------------------------------------------- |
| 2018-11-21 | Locally served and verified assest are cached and can run offline |

## History

The code in this repository is based on the
[PWA series](https://www.youtube.com/watch?v=Nduh3IUtyrE&list=PLIiQ4B5FSuphk6P-zg_E3W9zL3J22U4dT&index=2)
and
[Build a Simple PWA based on Basic JavaScript using Google's Workbox](https://www.youtube.com/watch?v=PL2DG9LJoVQ)
video tutorials.
