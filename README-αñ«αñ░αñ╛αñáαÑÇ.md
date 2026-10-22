# Dreams Enterprises — Install app (laptop आणि phone)

हा folder GitHub वर ठेवायचा, HTS च्या `hts-app` सारखाच. त्यामुळे laptop च्या Chrome / Edge मध्ये
**Install** चे बटण येते, आणि phone वर home screen icon बनतो.

## एकदाच करायची setup (साधारण 10 मिनिटे)

1. **नवीन repository** — github.com → **New repository** → नाव: `dreams-app` → **Public** → **Create repository**.
2. **Files upload** — **Add file → Upload files** → या ZIP मधल्या सगळ्या files आणि **icons** folder
   drag करा → **Commit changes**.
3. **GitHub Pages चालू करा** — **Settings → Pages** → Source: **Deploy from a branch** →
   Branch: **main**, folder **/ (root)** → **Save**. 1–2 मिनिटांत link मिळेल:
   `https://तुमचे-USERNAME.github.io/dreams-app/`
4. **App link तपासा** — GitHub वर **config.js** उघडा → ✏️ Edit. तिथली link तुमच्या Dreams च्या
   **/exec** link सारखीच आहे का ते पाहा (Apps Script → Deploy → Manage deployments). वेगळी असेल
   तर तुमची link paste करा → **Commit changes**.

## Laptop वर install

- Chrome किंवा Edge मध्ये GitHub ची link उघडा.
- Address bar च्या उजवीकडे **Install (⊕ / 🖥️↓)** चे चिन्ह येईल → **Install** दाबा.
  (किंवा ⋮ menu → **Cast, save and share → Install page as app**.)
- Desktop आणि Start menu मध्ये **Dreams** चा icon येतो. App स्वतःच्या window मध्ये उघडते.

## Phone वर

- Chrome मध्ये तीच link → **Install** / ⋮ → **Add to Home screen**.
  (Android APK वापरत असाल तर याची गरज नाही.)

## पुढे

- App मधले **ZIP update** (More → App update) तसेच चालतात. GitHub ला हात लावायची गरज नाही.
- Apps Script मध्ये **नवीन deployment** केल्यास /exec link बदलते. तेव्हा फक्त **config.js** बदला.
- Install केलेल्या app मध्ये पहिल्यांदा एकदा mobile नंबर + PIN ने login करावे लागेल.
