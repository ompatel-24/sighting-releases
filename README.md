# sighting-releases

Public update feed for Sighting. CI in the private source repo publishes each build here:

- `appcast.xml` — Sparkle feed, served by GitHub Pages at https://updates.sighting.dev/appcast.xml
- Releases — the signed app zips the feed points to

Don't edit `appcast.xml` by hand; every item carries an EdDSA signature.
