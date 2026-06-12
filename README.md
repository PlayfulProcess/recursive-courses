# recursive-courses

Public-domain courses by [PlayfulProcess](https://recursive.eco). MDX files, no build step, served via raw GitHub and GitHub Pages.

## Structure

```
_collection.json                          ← index of all courses
courses/<slug>/course.mdx                 ← the course content
```

## How it's used

- **tarot.recursive.eco** fetches course MDX directly from `raw.githubusercontent.com`
- **recursive.eco Library Assistant** reads `_collection.json` + individual MDX to answer course questions
- Any site can render MDX from the raw URL — no API, no auth

## License

CC-BY-SA-4.0 · curated by PlayfulProcess
