# Felsökning – GitHub Actions, Astro, pnpm & GitHub Pages

Den här filen är avsedd att användas som **Markdown (.md)**, t.ex. som `FELSOKNING.md`
eller som en sektion i `README.md`.

Den hjälper dig att snabbt identifiera och lösa vanliga problem i CI/CD‑kedjan för
Astro‑projekt som byggs med **pnpm** och deployas till **GitHub Pages**.

## Snabb felsökningschecklista

✅ Rätt Node‑version i loggen (>=22.13)
✅ pnpm installerad via npm (inte Corepack)
✅ Ingen trasig pnpm-workspace.yaml (ta bort)
✅ dist/ laddas upp som artifact
✅ Deploy‑jobbet hittar artifact
