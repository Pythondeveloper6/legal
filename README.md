# Legal & Support

Public privacy policies, terms of use and support pages for every app published
by Mahmoud Ahmed, served from GitHub Pages at:

<https://pythondeveloper6.github.io/legal/>

Each app gets its own directory:

```
/<app>/index.html     hub for that app
/<app>/privacy.html   Privacy Policy   -> filed in App Store Connect
/<app>/terms.html     Terms of Use     -> the EULA supplement / custom EULA
/<app>/support.html   Support          -> filed in App Store Connect
```

## Why this repo is public

App Store Connect requires a Privacy Policy URL and a Support URL that return
200 to anyone, with no login. A reviewer opens both. GitHub Pages on a public
repo is the simplest way to guarantee that; the app source stays private in its
own repository.

## Source of truth

Most pages are generated from the Markdown kept beside each app in the apps
working tree (`<App>/legal/*.md`). Incline's four pages are hand-written HTML and
are edited here and in `Incline/docs/legal/` together.

**A page here is a customer-facing document, and Apple treats it as app metadata
under guideline 2.3.** If an app's behaviour changes, its page changes in the
same release — a policy that describes a product that no longer exists is a
rejection, not a typo.

## Contact

apps.mahmoudahmed@gmail.com
