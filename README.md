# Focus Studio web hosting

This public repository contains deployment configuration for the owner-approved Focus Studio web build. The complete React/TypeScript source is maintained in the private [focus-studio repository](https://github.com/monobrihi-maker/focus-studio).

Compiled app files are attached to versioned Releases rather than committed to Git. Each release contains focus-studio-web.zip and SHA256SUMS. GitHub Actions checks the checksum and publishes the static app to Pages.

## Privacy

Study projects, lecture progress and session history are saved in the visitor's browser. They are not uploaded to this repository or a server. Use the app's JSON backup before clearing site storage or changing devices.

## Android

Open the published HTTPS app URL in Android Chrome. After the first complete online load, use the browser menu → Add to Home screen / Install app. Actual background sound and notification delivery depends on Android and Chrome.

## Updates

Update the private source through a pull request, wait for Checks, and use its focus-studio-web-release artifact. Attach focus-studio-web.zip and SHA256SUMS to a new approved release here; the release workflow verifies and deploys it. Previous releases remain available for rollback.
