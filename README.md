# qa-assets

Screenshots and assets referenced from QA comments on PrestaShop pull requests.

## Rules

- **Append-only.** Comments on merged PRs live forever, so files here are never
  deleted, moved or rewritten. Do not rewrite history.
- **Public by necessity.** `raw.githubusercontent.com` needs a token on private
  repos, so images would not render in a comment. Never commit a screenshot
  containing a credential, token, secret or personal data. Redact before commit.
- **Link by commit SHA, not branch name**, so reorganising later cannot break
  older comments:

  ```
  https://raw.githubusercontent.com/mattgoud/qa-assets/<sha>/PR-<number>/<name>.png
  ```

## Layout

```
PR-<number>/<slug>.png
```
