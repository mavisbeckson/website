# Mavis Boatemaa Beckson — Academic Website (Quarto, restyled)

UNL scarlet (#D00000) and cream theme in the same layout as Michael's green-and-beige site: Newsreader + IBM Plex fonts, numbered sections, full-width scarlet band. Pages: About (home), Research, Publications, CV.

## Preview / build
    quarto preview      # live preview
    quarto render       # builds the site into docs/

## Publish to GitHub Pages (mbeckson2.github.io)
Push this folder to the `mbeckson2.github.io` repo, then in GitHub:
Settings → Pages → Source: "Deploy from a branch" → branch `main`, folder `/docs`.

## Still to fill in (search the files for "TO BE SUPPLIED")
- Email address (_quarto.yml, index.qmd)
- Experience entries: 2025 role; institutions for the 2015 research-assistant roles (cv.qmd)
- Current status of the NCTE Press chapter (publications.qmd, cv.qmd)
- Current projects and teaching (research.qmd)
- Presentations, awards & service, CV PDF (cv.qmd)

Colors live in unl.scss; change $unl-scarlet / $unl-cream there.
