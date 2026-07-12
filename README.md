# GitHub Pages Policy Site

This folder contains a static privacy policy site for:

- Korean app name: 하루질문: 소복일기
- English app name: Dear Me: Little Questions

## Files

- `index.html`: simple policy home page
- `privacy.html`: Korean privacy policy with English summary

The pages use only plain HTML and inline CSS. They do not use external CDN, JavaScript, external fonts, images, forms, login, comments, cookies, or tracking scripts.

## Recommended Repository

Create a separate GitHub repository, for example:

```text
haru-question-policy
```

## Deployment Steps

1. Create the GitHub repository.
2. Copy `index.html`, `privacy.html`, and this `README.md` into the repository root, or into a `docs/` folder.
3. Commit and push to the `main` branch.
4. In GitHub, open `Settings` → `Pages`.
5. Set the source to either:
   - `Deploy from a branch` → `main` branch → `/root`, if files are in the repository root.
   - `Deploy from a branch` → `main` branch → `/docs`, if files are inside a `docs/` folder.
6. Save and wait for GitHub Pages to publish.

## Final URL Example

```text
https://<github-username>.github.io/haru-question-policy/privacy.html
```

Use the final `privacy.html` URL in Google Play Console and in the app’s `AppConstants.privacyPolicyUrl` before release.

## Before Release

- Replace the contact placeholder with a real support email or support URL.
- Confirm the effective date.
- Confirm the policy matches the final Android permissions and app behavior.
- Update the policy if ads, analytics, payments, cloud backup, account login, or server sync are added.
