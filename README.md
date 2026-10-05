# xzhou98.github.io

Source for **[xzhou98.github.io](https://xzhou98.github.io)**, the personal website of Xiangyu Zhou, a Ph.D. candidate in Computer Science at Wayne State University working on trustworthy AI: robustness and alignment of LLMs, reasoning models, and agentic AI.

Built with [Hugo](https://gohugo.io) and the [HugoBlox](https://hugoblox.com) Academic CV template, and deployed to GitHub Pages by GitHub Actions on every push to `main`.

## Where things live

| To change | Edit |
| --- | --- |
| Bio, links, education, experience | `data/authors/me.yaml` |
| Homepage sections, job-market callout, CV button, page title | `content/_index.md` |
| Google Scholar metrics (citations, h-index, i10-index) | `data/scholar.yaml` |
| Publications | `content/publications/<slug>/index.md` (figure: `featured.png`) |
| News posts / talks | `content/blog/`, `content/events/` |
| Skills and academic service | `content/experience.md` |
| CV PDF | `static/uploads/CV_XZhou.pdf` |
| Custom styles | `assets/css/hbx/blocks/shared/site/custom.css` |

`layouts/_partials/hbx/blocks/resume-biography-3/block.html` is a local copy of the theme's bio template, with two added includes for the Scholar metrics and the job-market callout. If you upgrade the theme, re-copy the upstream file and re-add the lines marked `LOCAL CHANGE`.

## Run locally

Requires Hugo extended 0.159.1, Go, and Node.js.

```bash
pnpm install
pnpm dev        # http://localhost:1313
```

## Gotchas

- **Future-dated pages are not published.** Hugo skips content whose `date` is after the build date.
- **Duplicate YAML keys fail the build** (e.g. two `links:` in one front matter).
- **Image extensions must match the file format.** A JPEG saved as `featured.png` can break the build.
- **`assets/scss/custom.scss` is not loaded** by this theme version. Put CSS in the file listed above.

## License

Theme and template code: MIT, © George Cushen (see `LICENSE.md`). Site content (text, publications, photos, CV): © Xiangyu Zhou, all rights reserved.
