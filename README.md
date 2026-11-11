# Game Developer & 3D Artist Portfolio

A responsive dark futuristic portfolio website with green/black accents, built using plain HTML, CSS, and JavaScript.

## Quick customisation

Before publishing, open `index.html` and replace:
- `YOUR NAME` with your name.
- `your.email@example.com` with your email address.
- `YOUR_USERNAME` in the GitHub, ArtStation, and LinkedIn links.
- The sample project names and descriptions with your real projects.

### Add your own project images
1. Create an `images` folder in this repository.
2. Upload your renders/screenshots.
3. In `index.html`, replace each abstract project `<a class="project-image ...">...</a>` block with an image, for example:
   `<a class="project-image" href="images/my-project-full.jpg"><img src="images/my-project.jpg" alt="My 3D project"></a>`
4. Add this CSS to `style.css`:
   `.project-image img { width:100%; height:100%; object-fit:cover; display:block; }`

## Publish free with GitHub Pages

1. Create a **public** repository named exactly `YOUR_USERNAME.github.io`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Visit `https://YOUR_USERNAME.github.io` after the deployment finishes.

No paid domain or hosting is required.
