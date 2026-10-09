# SideBot Dashboard | The 509

Public frontend for the SideBot Discord bot, using the green, black, white, and brown SideBot branding.

## Website

Enable **Settings → Pages → Build and deployment → GitHub Actions**. Once the workflow succeeds, the expected project site is:

https://venloud.github.io/sidebot-dashboard/

The workflow is in `.github/workflows/pages.yml` and deploys root `index.html`.

## Security and hosting

- Python source, secrets, saved state, and bot runtime remain private in `Venloud/sidebot`.
- The dashboard is public. Do not commit Discord tokens, GitHub credentials, private member data, or secret settings here.
- The restart link currently opens GitHub Actions for authenticated manual controls. The static website cannot directly restart the bot.
- Live status, editable configurations and one-click restart require an authenticated backend, potentially Replit later.

## Status

Frontend code is committed. Live site deployment must be verified separately. This alone does not replace all features of Dyno, Tatsu, or FreeStuff.
