# Install to Revenue

Static single-page demo built for an Upwork application. No build step.

## Deploy

```bash
cd vercel-demo
vercel --prod
```

Then paste the deployed URL into `proposal.txt` and `proposal_upwork.txt`
in place of `[DEMO_LINK]`.

## Notes

- Single `index.html`, no dependencies, no bundler.
- Fonts come from Google Fonts. Everything else is inline.
- Three-state theming: system default, plus an explicit toggle in the footer.
- Tabs switch with the `hidden` attribute, so the `[hidden]` rule in the
  inline reset is load-bearing. Do not remove it.
