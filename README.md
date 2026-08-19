# t4pan.github.io

Source for <https://t4pan.github.io/>. Plain static HTML — `.nojekyll` is
present, so GitHub Pages serves these files as-is with no Jekyll build.

```
index.html          landing page
ava/index.html      AVA — about, download, support
ava/privacy.html    AVA privacy policy (Greek + English)
assets/style.css    shared stylesheet
```

## Why this exists

The Google Play Console requires a **publicly reachable privacy policy URL** for
every app listing. AVA's is:

> <https://t4pan.github.io/ava/privacy.html>

The store listing's optional website field points at
<https://t4pan.github.io/ava/>.

Keep the privacy policy accurate: if AVA's data handling changes, update that
page *and* the date at the top of it before shipping the release.
