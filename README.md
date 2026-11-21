# TinyTrestle website

GitHub Pages serves the static HTML in `docs/` from `main`. The public pages work without JavaScript, cookies, external assets or a sign-in.

| Google Play or app destination | Public URL |
| --- | --- |
| Developer website | https://tinytrestle.github.io/ |
| MinoTrove Android privacy policy | https://tinytrestle.github.io/minotrove/privacy/ |
| MinoTrove Android data deletion help | https://tinytrestle.github.io/minotrove/data-deletion/ |

Use the privacy URL in the Play Console privacy-policy field and in the Android app. The deletion page supplies a player data request route. MinoTrove currently has no account creation. If an app adds accounts, review Google Play's requirements for initiating account deletion from inside the app and on the web.

To preview locally, run `python3 -m http.server --directory docs 8000` and open `http://localhost:8000/`. Keep established policy paths when revising pages. Add future apps under their own directory and link them from the home page.

Before changing distribution, compare the shipped SDKs, permissions, audience, markets, analytics choices and retention with the public text and the Play Console Data safety and ads declarations. Verify the published contact reaches the person responsible for privacy requests. A web page does not submit a Play Console declaration.

- [Google Play User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?hl=en)
- [Google Play account deletion](https://support.google.com/googleplay/android-developer/answer/13327111?hl=en)
- [Google Mobile Ads SDK disclosures](https://developers.google.com/admob/android/privacy/play-data-disclosure)
