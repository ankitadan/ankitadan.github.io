# Ankita Dan — GitHub Pages Portfolio

A responsive, dark-themed personal portfolio built with plain HTML, CSS, and JavaScript.

## Preview locally

Open `index.html` in your browser. No build tools or package installation are required.

## Add your profile photo

1. Choose a professional headshot.
2. Rename it to **`profile-photo.jpg`**.
3. Place it in the `assets/` folder, next to `profile-placeholder.svg`.
4. The page will automatically show your photo instead of the placeholder.

Use a portrait-oriented image; the page crops it to fit the photo frame.

## Add your resume

If you want a resume link on the site, put your current PDF in `assets/` as `resume.pdf` and add a link in the hero or contact section. I have not included a resume download link because no current resume PDF was supplied with this build.

## Publish with GitHub Pages

1. Create a public repository named **`ankitadan.github.io`**.
2. Upload the contents of this folder to the repository root (not the enclosing ZIP folder).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **`main`** and folder **`/(root)`**, then save.
6. After GitHub finishes deploying, visit **https://ankitadan.github.io/**.

A first deployment can take several minutes.

## Before publishing

- Add your own profile photo.
- Check the LinkedIn URL and email address.
- Review every project and experience detail for accuracy.
- Only include public, non-confidential descriptions of work completed for employers.
- GitHub Pages is a static hosting service. It can host this portfolio, but it does not run the Rails or Flask backend applications.

## Files

- `index.html` — portfolio content and structure
- `style.css` — responsive dark visual design
- `script.js` — mobile navigation and current footer year
- `assets/profile-placeholder.svg` — temporary image shown until you add `profile-photo.jpg`
