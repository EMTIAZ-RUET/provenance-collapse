# Provenance Collapse — research showcase page

A single-file, self-contained site presenting the *Inference as Fact / Provenance Collapse*
findings for academic review. No build step, no dependencies to install (Chart.js + Google
Fonts load from CDN).

## View it locally

Just open the file, or serve it:

```bash
cd docs
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publish on GitHub Pages (shareable link for your professor)

1. Push this repo to GitHub.
2. Repo **Settings → Pages**.
3. **Source:** *Deploy from a branch* → Branch **main**, folder **/docs** → Save.
4. Wait ~1 minute. Your link will be:
   `https://<your-username>.github.io/<repo-name>/`

That URL is the one to send your professor. It is a static page — nothing runs server-side,
nothing can break, and it works on phones.

## What's on the page

A scrollable dossier: the motivation, the journey from the failed "Soul Drift" idea, an
animated live demo of a memory collapsing, the method pipeline, and four interactive charts —
the 10-model capability law, the ambiguity gradient, the mitigation before/after, and the
recall-confound check — plus the judge-validation, the UNIQUE novelty verdict, and an honest
limitations section.

Every number is real and traces to a run listed in the page footer (see `../PAPER_DRAFT.md`
and `../results/` for the source data).
