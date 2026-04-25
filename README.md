## Run Locally

```bash
npm start
```

Then open:

```text
http://localhost:3000
```

If Chrome shows `Not found`, stop the running server with `Ctrl+C` in the terminal and run `npm start` again. If an old Node process is still using port 3000, close that terminal or run:

```powershell
Get-Process node | Stop-Process
```

## Customize

Edit these files:

- `index.html` for your name, bio, projects, email, GitHub, and LinkedIn links.
- `styles.css` for colors, spacing, and layout.
- `assets/noise.svg` if you want to change the abstract visual texture.

## Host on GitHub Pages

1. Create a GitHub repository.
2. Push this folder to the repository.
3. In GitHub, go to `Settings` → `Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select your default branch and `/root`.
6. Save. GitHub will publish your site for free.

No build step is required.
