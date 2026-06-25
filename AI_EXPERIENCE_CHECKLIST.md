# AI Experience Improvement Checklist

## Required now
- Upload `index.html` to replace the current homepage.
- Upload `sitemap.xml` to the repository root.
- Upload `robots.txt` to the repository root.
- Upload `llms.txt` to the repository root.
- Upload `ai-index.md` to the repository root.
- Upload `404.html` to the repository root.

## Verify after deployment
- https://mellowwei.github.io/BCI-HRP-Lab/sitemap.xml
- https://mellowwei.github.io/BCI-HRP-Lab/robots.txt
- https://mellowwei.github.io/BCI-HRP-Lab/llms.txt
- https://mellowwei.github.io/BCI-HRP-Lab/ai-index.md
- https://mellowwei.github.io/BCI-HRP-Lab/404.html

## GitHub Pages status behavior
- Existing static files should return 200.
- Missing static files should return 404 and use `404.html` when GitHub Pages serves it.
- 429 / rate-limit behavior is not configurable on plain GitHub Pages without a separate backend, CDN, or proxy.

## Future MCP / Skill candidates
Do not claim current implementation. Future candidates only:
- protocol session export validator
- stimulus metadata validator
- agency-event log validator
- dataset schema checker
