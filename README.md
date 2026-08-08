# profile-metrics

Generates the analytics SVGs embedded in [@crypticatul](https://github.com/crypticatul)'s profile README.

Runs here (org billing) because the personal profile repo only embeds the rendered SVGs via raw URLs.

- `metrics-overview.svg`, `metrics-languages.svg`, `github-metrics.svg` — committed to `main` daily by the Metrics workflow
- `github-contribution-grid-snake*.svg` — published to the `output` branch daily by the Snake workflow

Requires an Actions secret `METRICS_TOKEN`: classic PAT from **crypticatul** with `repo` + `read:user` scopes (enables private-repo stats).
