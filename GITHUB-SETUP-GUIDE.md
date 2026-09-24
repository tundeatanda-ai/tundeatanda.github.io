# GitHub Pages — Step-by-step

1. Go to https://github.com and sign in.
2. Click **+ → New repository**.
3. Name it `YOUR-GITHUB-USERNAME.github.io` (replace with your actual username).
4. Choose **Public** and create the repository.
5. Download and extract this ZIP on your computer.
6. Open the extracted folder. `index.html` must be directly inside it.
7. In GitHub, click **Add file → Upload files**.
8. Select ALL contents of the extracted folder and upload them.
9. Commit with the message `Initial portfolio website`.
10. Go to **Settings → Pages**.
11. Under **Build and deployment**, choose **Deploy from a branch**.
12. Select branch **main** and folder **/ (root)**.
13. Click **Save**.
14. Wait a few minutes, then return to **Settings → Pages** and click **Visit site**.

Your address will normally be:
`https://YOUR-GITHUB-USERNAME.github.io`

IMPORTANT: Do not upload the ZIP itself. Upload its extracted contents, with `index.html` at the repository root.

The package already contains:
- Your supplied professional headshot at `assets/images/profile.jpg`
- Your CV at `assets/documents/Babatunde-Raaji-CV.pdf`
- All portfolio pages
- Responsive CSS and mobile navigation
- A 404 page
- This setup guide

For future updates, replace/edit the relevant files in GitHub and commit the changes. GitHub Pages will redeploy automatically.

After launch, we can add certificate galleries, approved project evidence, SEO improvements, animations, a contact form and a custom domain.


## Adding future certifications yourself
1. Put the certificate image in `assets/images/certificates/`.
2. Open `certifications.html`.
3. Copy an existing certification card and replace the title, issuer, date, description, image path and credential information.
4. Add the exact verification URL supplied by the issuer when one exists.
5. If no public verification URL exists, use a View certificate button instead.
6. Upload the changed HTML and image to GitHub and commit.

A complete example is available in `CERTIFICATION-MANUAL-UPDATE-GUIDE.md`.
