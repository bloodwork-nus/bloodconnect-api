# The BloodConnect API
This repository contains the (production stage) cloud functions for BloodConnect.

### Developer's guide (to be removed)
For local development, install the Firebase CLI with `npm install firebase-tools --global` or `yarn global add firebase-tools`.
Note that this is as far as you will go using `yarn`. Firebase currently only supports Node 8 or 10. Different engine versions
might conflict with `yarn` and it is recommended to continue with `npm` for greater stability, unless you decide to use
`yarn --ignore-engine`. **BloodConnect API uses `npm`.**

* To test functions locally, invoke the Firebase Local Emulator with `firebase emulators:start`.
* To deploy functions to Firebase, invoke `firebase deploy --only functions`.

<div align='center'>
    <hr>
    <img src="https://firebase.google.com/downloads/brand-guidelines/SVG/logo-built_black.svg" width="200rem" />
</div>
