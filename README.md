# commuter-site

The public support page and privacy policy for Commuter, Jordan's train
planner. The app's own repo (`jcamina/commuter`) is private, so App Store
Connect's URLs point here. Served by GitHub Pages from `main`, root folder.

| URL | File | App Store Connect field |
|---|---|---|
| https://jcamina.github.io/commuter-site/ | `index.html` | Support URL (and Marketing URL, if wanted) |
| https://jcamina.github.io/commuter-site/privacy.html | `privacy.html` | Privacy Policy URL |

- **`privacy.html` is a copy.** Its source is `Commuter/docs/privacy.html`,
  which must match `Commuter/docs/PRIVACY.md` and the app's Privacy Policy
  screen (`PrivacyPolicyView`). Change it there, then copy it here (keep the
  icon link and the "‹ Commuter" back link).
- `icon.png` is exported from `Commuter/App/AppIcon.icon` with Xcode's
  `ictool` (Icon Composer), 256 px. Re-export it if the icon changes.
- Help requests arrive as GitHub issues on this repo, so no email address
  is published.
- `.nojekyll`: plain files, no Jekyll build.
