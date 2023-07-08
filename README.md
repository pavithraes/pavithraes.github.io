## Hi! 👋

This is my **personal website and blog**, built with the [Doks theme](https://getdoks.org/) for Hugo.

Live at: https://pavithraes.me

## Initial setup 💻

```bash
git clone git@github.com:pavithraes/pavithraes.github.io.git
```

```bash
cd pavithraes.github.io
```

```bash
conda create -n website-dev nodejs
```

```bash
conda activate website-dev
```

```bash
npm install
```

## Reference commands 👩🏻‍💻

Build development site:

```bash
npm run start
```

Create new blog:

```bash
npm run create blog/<slug>/index.md
```

Create new talk-year:

```bash
npm run create docs/talks/<YYYY>/index.md
```
