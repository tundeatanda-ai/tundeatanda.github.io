# Adding future certifications yourself

You can add new certifications without rebuilding the whole website.

## 1. Add the certificate image
Place the image in:
`assets/images/certificates/`

Recommended naming style:
`provider-course-name.jpg` or `.png`

## 2. Add a new card
Open `certifications.html`, then copy an existing `<article class="cert-card">...</article>` block and edit:
- certificate image path
- certificate title
- issuing organization
- date
- description
- credential ID
- verification URL, if the issuer provides one

Example verification button:
```html
<a class="button small" href="YOUR-VERIFICATION-URL" target="_blank" rel="noopener">Verify credential ↗</a>
```

Example certificate image:
```html
<a class="cert-image" href="assets/images/certificates/my-certificate.png" target="_blank" rel="noopener">
  <img src="assets/images/certificates/my-certificate.png" alt="My certificate">
</a>
```

## 3. If there is no public verification URL
Keep the certificate image and use a **View certificate** button. Do not invent a verification URL.

## 4. Upload to GitHub
After adding the image and editing `certifications.html`, upload/replace those files in your GitHub repository and commit the changes. GitHub Pages will redeploy automatically.

## 5. Important
Only publish certificates and verification links that belong to you and that you are permitted to share publicly.
