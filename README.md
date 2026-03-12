git add vercel.json
git commit -m "Add vercel routing config"
git push
```

---

## Fix 2 — Rename the homepage file

Vercel automatically serves `index.html` from the root. Just rename `keheilan-homepage.html` to `index.html` in your repo. The other pages will then be accessible at `/keheilan-kaif.html` etc.

---

## Fix 3 — Proper folder structure (cleanest)

Restructure like this:
```
/
├── index.html              ← was keheilan-homepage.html
├── kaif/
│   └── index.html          ← was keheilan-kaif.html
├── sukuk/
│   └── index.html          ← was keheilan-sukuk.html
├── index-portfolios/
│   └── index.html          ← was keheilan-index.html
└── vercel.json
