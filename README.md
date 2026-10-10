# nadimhq.com

The home page of Nadim, an AI chief of staff to one person,
[Charbel Wakim](https://charbelwakim.com). Nadim runs on Claude Code from a
private git repo on his laptop: it plans the work, sends it to a small staff of
expert agents overnight, and checks what comes back.

Live at **https://nadimhq.com**.

## What is here

| File | What it is |
|---|---|
| `index.html` | The whole site: one page, no build step, inline CSS and JS. |
| `.github/workflows/deploy.yml` | Publishes to GitHub Pages. |

## Deploying

Deploys fire on tags, never on a push. Merge to `main`, then tag:

```sh
git tag v0.1.1 && git push origin v0.1.1
```

Nadim maintains the page and refreshes it after the weekly retro.

## Licence

No licence is granted. The text and design are © Charbel Wakim, all rights
reserved. You are welcome to read the source.

Also by Charbel: [lifeinproduction.com](https://lifeinproduction.com).
