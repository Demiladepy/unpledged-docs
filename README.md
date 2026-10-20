# Unpledged docs

Source for the [Unpledged documentation](https://unpledged.thally.app), built
and published with [Thally](https://thally.io).

Unpledged is a confidential receivables-financing app built with Daml on
Canton. The app itself lives at
[Demiladepy/Unpledged](https://github.com/Demiladepy/Unpledged).

## What's here

| Path | What it is |
| --- | --- |
| `src/content/introduction.mdx` | What Unpledged does and who it's for |
| `src/content/quickstart.mdx` | Run it locally in mock mode in about five minutes |
| `src/content/guides/run-on-devnet.mdx` | Connect to Canton DevNet, with troubleshooting |
| `src/content/guides/how-this-site-was-built.mdx` | How this site was built with Thally |
| `docs.json` | Navigation, logo, and agent-readiness test questions |
| `src/data/site.ts` | Site name, links, and brand colours |
| `AGENTS.md` | Instructions and product terms for AI coding agents |

## Work on it locally

```bash
npm install
npm run dev
```

Before pushing, run:

```bash
npx --yes @thallylabs/cli@latest check   # on Windows: npx create-thally-docs check
npm run build                            # on Windows: run inside WSL
```

Pushing to `main` publishes the site automatically.
