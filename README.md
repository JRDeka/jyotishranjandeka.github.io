# Jyotish Ranjan Deka — Academic Website

A lightweight static academic website designed for GitHub Pages.

## Research focus

The homepage is organized around four clear themes:

1. Tiger Connectivity
2. Human–Wildlife Coexistence
3. Transboundary Conservation
4. Conservation Technology

The site uses plain HTML, CSS, and JavaScript so it is easy to maintain and does not require a build system.

## Files

```text
jyotish-website/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    └── images/
        ├── hero.jpg
        ├── project-connectivity.jpg
        ├── project-acoustics.jpg
        ├── project-coexistence.jpg
        ├── project-transboundary.jpg
        ├── field-camera.jpg
        ├── field-acoustic.jpg
        ├── field-landscape.jpg
        └── field-team.jpg
```

The site will still work before you add the images; it will show neutral background colors.

## 1. Create the GitHub repository

1. Sign in to GitHub.
2. Click **New repository**.
3. Name it something like `jyotishranjandeka.github.io` if you want the cleanest GitHub Pages address, or `academic-website` if you prefer.
4. Make it **Public** if you are using GitHub Free for Pages.
5. Create the repository.

## 2. Upload the website files

On the repository page:

1. Choose **Add file → Upload files**.
2. Upload everything in this folder, including the `assets` folder.
3. Commit the files to the `main` branch.

You can also use Git from your computer if you prefer.

## 3. Turn on GitHub Pages

1. Open the repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose `main` and `/ (root)`.
5. Click **Save**.

GitHub will publish a temporary GitHub Pages URL. Test the site there first.

## 4. Add your photographs

Replace the placeholder image filenames in `assets/images/` with your own files using these exact names:

- `hero.jpg` — strongest wide field image, ideally Assam landscape / you or team in field
- `project-connectivity.jpg` — connectivity/current-flow map or tiger landscape
- `project-acoustics.jpg` — recorder, spectrogram, or tiger acoustic figure
- `project-coexistence.jpg` — WUI/conflict/connectivity figure
- `project-transboundary.jpg` — transboundary landscape or map
- `field-camera.jpg` — camera deployment
- `field-acoustic.jpg` — acoustic deployment
- `field-landscape.jpg` — strong Assam landscape
- `field-team.jpg` — field team photograph

Recommended image size: around 1600–2200 px wide, JPEG/WebP, preferably under 1 MB each after compression.

## 5. Update publications

Open `index.html`, find the `publications-section`, and replace the three placeholder entries with the three papers you most want visitors to see.

## 6. Connect jyotishranjandeka.com — only after testing

Do **not** change the domain DNS while you are still building the site. Your current WordPress site can remain live.

When the GitHub Pages version is ready:

1. In GitHub, open **Settings → Pages** for the repository.
2. Enter `jyotishranjandeka.com` under **Custom domain** and save it.
3. At the company where your domain DNS is managed, point the apex/root domain to GitHub Pages using GitHub's current documented DNS records.
4. Point `www` to your GitHub Pages hostname with a CNAME.
5. When DNS resolves correctly, enable **Enforce HTTPS** in GitHub Pages.

GitHub recommends verifying the custom domain before use.

Always use GitHub's current official documentation when changing DNS because these values can change.

## 7. Editing later

For small changes you can edit `index.html` directly on GitHub and commit the change. GitHub Pages will redeploy the site automatically.

The next logical development step is to add separate pages for:

- Research
- Publications
- Fieldwork
- About
- CV
- Contact

and change the homepage menu from anchor links to those pages.
