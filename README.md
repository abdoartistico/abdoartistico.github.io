# abdoartistico.github.io

Home of **Contrail**, a free flight tracker for Android.

- `contrail/config.json` — remote config the app reads at launch. Empty values = use the public ADS-B endpoints.
- `.well-known/assetlinks.json` — lets `https://abdoartistico.github.io/f/…` share links open directly in the app (Android App Links).
  Add your Google Play app-signing SHA-256 fingerprint here once the app is on Play (Play Console → Setup → App signing).
- `404.html` — shared flight links (`/f/<code>`) land here when the app isn't installed; it shows the flight and a button to open it in Contrail.
