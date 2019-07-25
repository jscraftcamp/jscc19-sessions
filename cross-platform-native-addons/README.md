# Dealing with cross-platform native addons

_session by Simon Hofmann_

Showed [sakuli.io](https://sakuli.io/) where they use
[nut.js](https://github.com/nut-tree/nut.js) which is basically the code that
prompted Simon to work with native addons.

Simon shared his
[slides in s1hofmann/jscc19-sessions](https://github.com/s1hofmann/jscc19-sessions).

- node-gyp or cmake-js are options for creating native addons
- NAN -> this requires special V8 APIs, so needs to compile for each NodeJS
  version
- N-API -> is not dependent on specific JS engine and does not need to be
  compiled for each version

[justadudewhohacks/opencv4nodejs](https://github.com/justadudewhohacks/opencv4nodejs)
"best supported / maintained project for using opencv with nodejs"
