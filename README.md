# Family Meal Mixer — public legal pages

Static pages required by the app stores and by privacy law: Privacy Policy, Terms of Service, and an account-deletion request page (Google Play requires a web route reachable without installing the app).

This repo is **generated output only** — there's no source here to edit directly. The actual content lives in the main (private) app repo at `apps/mobile/src/features/legal/policy-content.ts`, and is built into the HTML in this repo via that repo's `web/scripts/generate.ts` (`pnpm run web:build`). When the policy content changes, regenerate and re-push the files here.

Served via GitHub Pages from this repo's `main` branch. Live at:

- https://etodd513.github.io/family-meal-mixer-legal/privacy.html
- https://etodd513.github.io/family-meal-mixer-legal/terms.html
- https://etodd513.github.io/family-meal-mixer-legal/delete-account.html
