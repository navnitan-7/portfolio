# Portfolio

Personal portfolio site for **Navnitan SV**, served with [GitHub Pages](https://pages.github.com/).

## Publish as `username.github.io/portfolio`

1. Create a new repository on GitHub named **`portfolio`** (user or organization account).
2. Push this folder to the `main` branch:

   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Add portfolio site for GitHub Pages"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```

3. In the repo on GitHub: **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose branch **`main`** and folder **`/` (root)**, then save.

The site will be available at `https://YOUR_USERNAME.github.io/portfolio/` (may take a minute to go live).

## Local preview

From this directory, run any static file server, for example:

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).
