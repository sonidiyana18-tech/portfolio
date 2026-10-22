# Diyana — Portfolio and Diary

A retro desktop-inspired personal portfolio for Diyana, built with plain HTML, CSS and JavaScript. The site uses a red-and-pink palette, a pixelated lilies background, a pixel-art press-pass portrait, interactive story files, company/regulator tracking notes, and a diary section for poetry.

## Book: *I am Loved*

Diyana is also a poet and the author of *I am Loved*. The book is linked from the website and is available here:

- BookLeaf: https://ebooks.bookleafpub.com/product-page/i-am-loved
- Barnes & Noble: https://www.barnesandnoble.com/w/i-am-loved-diyana/1148549190?ean=9798900813745

## Publish on GitHub Pages

1. Create a repository. For a personal site at `https://YOUR-USERNAME.github.io/`, name the repository `YOUR-USERNAME.github.io`. You can also use an existing repository if you want the site under that project's URL.
2. Upload `index.html`, `README.md`, and the entire `assets` folder to the repository root. Keep `index.html` at the root, not inside a nested folder.
3. Commit the upload to your default branch (usually `main`).
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
6. Wait a few minutes for the first deployment and open the URL GitHub shows on the Pages settings screen.

GitHub's guide: https://docs.github.com/en/pages/quickstart

## Editing the site

- Update the introduction and biography by editing the text in `index.html`.
- The story cards are in the `.work-grid` section. The modal story copies and reporting trails are in the `projectNotes` object near the bottom of `index.html`.
- To add another story, add a `.work-card` and a matching entry in `projectNotes`, using a unique `data-project` key.
- Filters use each card's `data-tags` attribute (`regulation`, `data`, `business`, `society`, `poetry`).
- The lilies background is `assets/lilies-background.png`. The pixel-art portrait on the press pass is `assets/diya-pixel.png`.
- Contact links are already set to the addresses provided by Diyana.

## Before sharing

- Confirm each story's publication status and add external clip links where they exist. The supplied reporting copy is labelled as a draft, story, or project where appropriate; don't present a draft as published work.
- Verify all figures, dates, quotations and attributions against the original sources before external publication. The “how I reported it” notes describe the supplied reporting process and identify checks that still need to be completed.
- Because the diary is public on GitHub Pages, publish only poems and personal details you are comfortable making public.
- Don't include confidential source details, private interview notes or material you don't have permission to share.

## Built with

HTML, CSS and JavaScript. No build step or external dependency is required.
