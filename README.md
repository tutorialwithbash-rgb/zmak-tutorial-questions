# SS2 & SS3 Tutorial Questions

A lightweight static site for viewing and downloading the SS2 and SS3 past-question PDFs.

## Pages

- Home: <https://tutorialwithbash-rgb.github.io/zmak-tutorial-questions/>
- SS2: <https://tutorialwithbash-rgb.github.io/zmak-tutorial-questions/ss2/>
- SS3: <https://tutorialwithbash-rgb.github.io/zmak-tutorial-questions/ss3/>

The site uses GitHub Pages project-site paths and does not require a build step.

## Publish with GitHub Pages

1. In the repository on GitHub, open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push a change to `main`, or run **Deploy static site to GitHub Pages** from the **Actions** tab.
4. Open the live site at <https://tutorialwithbash-rgb.github.io/zmak-tutorial-questions/>.

The workflow deploys the site automatically whenever `main` is updated. The first deployment may take a few minutes.

The PDFs are stored in `pdf/`. To replace a paper, keep its existing filename (`ss2.pdf` or `ss3.pdf`) so the viewer and download links continue to work.
