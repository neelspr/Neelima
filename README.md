# Neelima P R | Technical Writing Portfolio

A single-page portfolio with no build step. Everything is in `index.html`.

## Publish on GitHub Pages

1. On GitHub, create a new public repository. For a personal URL, name it `<your-username>.github.io`.
2. Upload `index.html` and this `README.md` to the repository root (Add file > Upload files), then commit.
3. Open **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/` (or `/<repo-name>/` for other repository names).

### Other free hosts

- **Netlify:** drag the folder onto app.netlify.com/drop.
- **Cloudflare Pages or Vercel:** connect the repository and leave the build command empty.

## Customize

- **Add a photo:** add `photo.jpg` to the repository, then place `<img src="photo.jpg" alt="Neelima P R" width="96" height="96" style="border-radius:50%">` above the name in the sidebar.
- **Add writing samples:** link public samples (PDFs, a sample help site, a GitHub docs repo) in the Projects section, for example `<li><a href="samples/release-notes.pdf">Sample release notes</a></li>`. Only share material your employers allow.
- **Add metrics:** if you have numbers (articles published, help consumption growth, turnaround time saved), add them to the project bullets or the facts row near the top.
- **Add links:** LinkedIn or GitHub links can go in the sidebar `contact` block and the Contact section.
- **Colors:** change the variables at the top of the `<style>` block. Dark mode follows the visitor's system setting.
