# PROJECT KNOWLEDGE BASE

**Generated:** 2026-05-03
**Commit:** 1cd8cfa
**Branch:** main

## OVERVIEW
Browser-based academic meta-search tool. Single HTML file generates direct search links to 15+ research databases (Google Scholar, PubMed, arXiv, etc.). No backend, no dependencies, runs entirely client-side.

## STRUCTURE
```
./
├── index.html    # Main app (369 lines, embedded CSS+JS)
├── README.md    # Documentation
└── .github/workflows/static.yml  # GitHub Pages deploy
```

## WHERE TO LOOK
| Task | Location | Notes |
|------|----------|-------|
| Modify search platforms | index.html lines 280-310 | sites array configuration |
| Add new platform | index.html line 280 | Add to sites array |
| Style changes | index.html lines 5-230 | Embedded CSS |
| UI logic | index.html lines 250-365 | searchLinks() function |

## ANTI-PATTERNS (THIS PROJECT)
- No inline JavaScript preferred—keep logic in script tag only
- No external dependencies—self-contained
- No API calls—generates URLs only, no fetching

## UNIQUE STYLES
- CSS uses linear-gradient dark theme (#0f172a → #020617)
- Two-column responsive grid for results
- Notification popup on search

## COMMANDS
```bash
# No build required - plain HTML
# To test: open index.html in browser
```

## NOTES
- Query encoding handles special characters differently per platform
- DOAJ requires complex JSON query structure
- Responsive: grids collapse to single column <768px