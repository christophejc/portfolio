# Christophe Charles — static technical portfolio

A self-contained HTML/CSS copy of the public portfolio at https://christophejcharles.wordpress.com/, captured October 12, 2026. No WordPress installation, database, plugins, build step, ads, analytics scripts, or paid hosting required.

## Publish on GitHub Pages

1. Create a public GitHub repository. Use `christophejc.github.io` if you want the site at `https://christophejc.github.io/`, or choose another repository name for a project site.
2. Clone that repository using GitHub Desktop (or Git).
3. Copy the **contents** of this folder into the repository. `index.html` must be directly in the repository root, alongside `assets/` and the project folders. Include the hidden `.nojekyll` file.
4. Commit the files and push/publish the repository to GitHub.
5. On GitHub, open the repository's **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then **Save**.
6. After deployment completes, open the website link shown in Pages settings.

Use GitHub Desktop or Git for the initial upload: two original GIF animations exceed GitHub's 25 MiB browser-upload limit. All individual files are below its 100 MiB Git limit. Do not upload the ZIP itself as the website.

GitHub instructions:
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-large-files-on-github

## Included pages

- `index.html` — home, biography, and project links
- `edgereps/index.html` — EdgeReps
- `64-tap-fir-filter-core/index.html` — 64-Tap FIR Filter Core
- `hydrai/index.html` — HydrAI
- `autonomous-ir-line-tracking-vehicle-ti-rslk/index.html` — Autonomous IR Line-Tracking Vehicle (TI-RSLK)
- `formal-verification-of-risc-v-cpu-simulator-using-generative-ai-fuzzer/index.html` — Formal Verification of RISC-V CPU Simulator using Generative AI Fuzzer

The sitemap and public WordPress page inventory list these six pages. The original homepage also contains a hidden Golf Wizards card linking to `?page_id=81`; that address returns HTTP 404 and no public page content is available. The hidden, broken card is omitted. Supply its WordPress export or content to add it later.

## What was preserved and changed

Original project text, code examples, images, GIFs, PDF diagrams, dates, repository links, biography, contact details, and black theme are preserved. All required images, fonts, PDFs, and styles are local in `assets/`. Navigation uses relative links so it works on a GitHub user site or a repository site. The menu now uses ordinary visible links without JavaScript. PDF previews and downloads work without WordPress. WordPress ads, tracking, promotional bars, cookie overlays, subscription controls, and the promotional footer are removed.

External links to GitHub, LinkedIn, YouTube, and Edge Impulse still open those services. The YouTube demo remains an external link, as on the original site; it is not embedded or copied.

## Preview and edit

Open `index.html` in a browser. For a local server, run `python3 -m http.server 8000` inside this folder and open `http://localhost:8000`.

Edit page text in each HTML file. Site-wide static adaptations are in `assets/static.css`. Most original theme styling is preserved in page style blocks and other asset CSS files. There is no WordPress editor or live sync; future edits are made in these files and pushed to GitHub.

## Latest refresh

All six pages were fetched again after the latest wording corrections. The vehicle project contained new wording; the other five pages matched the prior public version. Each project’s text was compared with its latest public source and matched exactly. Homepage text and project navigation were also checked.

## Validation

- Compared each project's text with the source: exact match.
- Checked every local HTML link, fragment, image, PDF, stylesheet, and CSS asset reference: no missing files or anchors.
- Downloaded all required assets with no failures.
- Checked homepage desktop layout and project-page phone layout in a browser.
- Removed all executable scripts and WordPress page links.

See `migration-report.json` for the page inventory and missing-page note. This package has not been published to GitHub; your original WordPress site is unchanged.
