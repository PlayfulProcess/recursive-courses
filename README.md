# recursive-courses

Public-domain courses by [PlayfulProcess](https://recursive.eco). MDX files, no build step, served via raw GitHub and GitHub Pages.

## Work in progress

This is a work in progress. I published it mainly so the pages could be served, and it isn't
finished. Contributors are welcome: open an issue or send a pull request, however small.

The idea behind [recursive.eco](https://recursive.eco) is a hypothesis, not a claim: that we may
need to learn together how to create the conditions for recursive eco-improvement, rather than
race toward recursive self-improvement.

If your work appears here and you'd like it featured differently, removed, or given a shelf of
your own, please write to pp@playfulprocess.com.

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
