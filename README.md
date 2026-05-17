# DMP Portal v1

Password-gated landing page for **The Disciple-Making Parent** content tool. Routes Chap and his team to the n8n Upload + Create forms.

## Live URL

`https://j4m3sdev.github.io/dmp-portal-v1/`

## Team password

**`passingthebaton`**

To change the password:

```bash
echo -n "yournewpassword" | shasum -a 256
```

Then replace the `HASH` constant inside the `<script>` tag near the bottom of `index.html`.

## Brand

- Primary navy: `#1E3A5F`
- Deep navy: `#0F1E2E`
- Vellum/gold accent: `#C8A75B`
- Typography: Inter (sans), Playfair Display (serif), DM Mono (mono labels)

## Backend (n8n)

- Workflow: `DMP Content Repurposer` (`3P0kF3dWk3p8YPfp`)
- Upload form: `https://modulusai.app.n8n.cloud/form/3f3adc2d-8037-482e-bfc3-7d65c61ca950`
- Create form: `https://modulusai.app.n8n.cloud/form/1d0a8d19-ae42-40f2-a3e4-3f2ff235bbd8`

## Editing

1. Edit `index.html` locally
2. Preview: `python -m http.server 5173` and open `http://localhost:5173`
3. Commit + push — Pages auto-rebuilds in ~30 seconds

## Cloned from

[`cbm-portal-v1`](https://github.com/J4m3sdev/cbm-portal-v1) — same Modulus portal pattern, retrofitted for DMP branding, password, and content.
