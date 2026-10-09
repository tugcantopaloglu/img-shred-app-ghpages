# img.shred website

Static landing page, privacy policy, and terms of service for the img.shred gallery cleaner. This repository contains the website, not the mobile application's source code.

- [Website](https://tugcantopaloglu.github.io/img-shred-app-ghpages/)
- [App Store listing](https://apps.apple.com/app/img-shred/id6757125666)
- [Privacy policy](https://tugcantopaloglu.github.io/img-shred-app-ghpages/privacy/)
- [Terms of service](https://tugcantopaloglu.github.io/img-shred-app-ghpages/terms/)

## Local preview

The pages use inline CSS and require no package installation or build step. From the repository root, run:

```sh
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/`. Check the download link, the privacy and terms links, and the return navigation on both policy pages. Stop the server with Ctrl+C.

## Hosting

GitHub Pages serves the root of the `main` branch at `/img-shred-app-ghpages/`. The `.nojekyll` file keeps the site as plain static files. Changes pushed to that branch trigger the existing Pages build and deployment.

Keep internal links relative so they resolve both under the GitHub Pages project path and at the local preview URL. The `og:url` metadata identifies the public project URL.

Policy wording and update dates describe the mobile app's practices. Confirm substantive changes against the app before editing those documents.
