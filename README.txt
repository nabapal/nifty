To use this TWA wrapper:

1. Host your PWA at https://yourdomain.com/
2. Upload `assetlinks.json` to https://yourdomain.com/.well-known/
3. Install Bubblewrap CLI and run:

   bubblewrap init --manifest twa-manifest.json
   bubblewrap build
   bubblewrap install

More info: https://github.com/GoogleChromeLabs/bubblewrap
