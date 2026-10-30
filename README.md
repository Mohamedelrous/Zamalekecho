# Zamalek Echo 1911

Fan site for the Instagram page [@zamalekecho1911](https://www.instagram.com/zamalekecho1911/): news, videos and a store.

## Publish on GitHub Pages (account: mohamedelrous)

1. Create a new public repository named `zamalekecho1911` on github.com/mohamedelrous.
2. Upload `index.html` and `README.md` (Add file > Upload files > Commit).
3. Go to Settings > Pages. Under Source choose "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
4. After a minute the site is live at https://mohamedelrous.github.io/zamalekecho1911/

Or with git:

```bash
git init
git add .
git commit -m "Zamalek Echo site"
git branch -M main
git remote add origin https://github.com/mohamedelrous/zamalekecho1911.git
git push -u origin main
```

## Soma API

Edit the `CONFIG` block at the top of the script in `index.html`: set `baseUrl`, `apiKey` and the three endpoints. If the response field names differ, adjust the `adapt` functions. Anything in a public GitHub Pages site is visible to visitors, so only use a key that is safe to expose.
