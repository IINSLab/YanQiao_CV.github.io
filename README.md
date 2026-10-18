# Yan Qiao - Academic CV Website

This is a lightweight academic website for **Yan Qiao (乔焰)**, Associate Professor and Ph.D. Supervisor at Hefei University of Technology. Its design follows the simple academic/Jemdoc style used by the [Meng Li CV site](https://github.com/IINSLab/MengLi_CV.github.io).

## Files

- `index.html` - the complete academic homepage (including 20 journal papers and 18 conference papers from the supplied CV).
- `jemdoc.css` - local stylesheet; no external font or JavaScript dependencies.
- `_config.yml` - GitHub Pages metadata.
- `README.md` - this guide.
- `Yan_Qiao_CV.pdf` - **NOT included in this package.** Rename the approved source PDF to this exact filename and upload it to the repository root.

## How to publish on GitHub Pages

1. In the `IINSLab` organization, create a **public** repository named `YanQiao_CV.github.io` (or use your existing repository for this homepage).
2. Upload `index.html`, `jemdoc.css`, `_config.yml`, and `README.md` to the **root** of the repository. Do **not** upload the ZIP as one file: extract it and upload the files inside.
3. Rename the approved CV PDF to `Yan_Qiao_CV.pdf` and upload it to the same root. If the PDF isn't uploaded, the `CV (PDF)` link won't work.
4. Go to **Settings > Pages > Build and deployment**. Choose **Deploy from a branch**, **main**, **/(root)**, then **Save**.
5. Once deployed, open `https://iinslab.github.io/YanQiao_CV.github.io/` (assuming that repository name) and test the PDF, Google Scholar and faculty links.

## Local preview

Open `index.html` in Chrome/Edge. Internet is required only to follow external links; the homepage layout itself is completely local.

## Notes

- The public webpage intentionally excludes date of birth, mobile phone and WeChat contact details from the supplied PDF. Review the PDF separately before publishing it publicly.
- A personal photo is not included, because no photograph was provided. The webpage works without one.
- All scholarly records are based on the supplied CV. Some punctuation and line-wrapped hyphenation have been normalized for web display; please review manuscript titles and author markers before publication.
- To update the homepage later, edit `index.html` and commit the changes. No build tools are required.
