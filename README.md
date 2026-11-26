# renovate

Runs [Renovate](https://docs.renovatebot.com) for the `varify-io` repositories as the `varify-renovate` GitHub App, every two hours and on demand (Actions → Renovate → Run workflow).

A repository takes part when the app is installed on it and it has a `renovate.json`. Its dependency dashboard is an issue in that repository.

The app's id is the `RENOVATE_APP_ID` variable, its private key the `RENOVATE_APP_PRIVATE_KEY` secret.
