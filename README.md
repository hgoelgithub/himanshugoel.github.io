# himanshu-goel.github.io

Personal website of Himanshu Goel — Computational Scientist specializing in Drug Design, AI/ML, Cheminformatics, and Bioinformatics.

**Live site:** https://himanshu-goel.github.io

---

## Quick setup (5 steps)

### 1. Create the GitHub repo

Create a **public** repo named exactly `himanshu-goel.github.io` on GitHub.  
(Replace `himanshu-goel` with your actual GitHub username.)

### 2. Clone and copy these files

```bash
git clone https://github.com/himanshu-goel/himanshu-goel.github.io
# Copy all files from this starter kit into the cloned folder
```

### 3. Install Quarto

Download from https://quarto.org/docs/get-started/  
Quarto is free and works with VS Code, RStudio, and Jupyter.

### 4. Preview locally

```bash
quarto preview
```

Your site opens at `http://localhost:4444` — live-reloads as you edit.

### 5. Push to GitHub → auto-deploys

```bash
git add .
git commit -m "Initial site"
git push origin main
```

GitHub Actions (`.github/workflows/deploy.yml`) will build and deploy automatically.  
Go to **Settings → Pages** in your repo and set source to **GitHub Actions**.

Your site will be live at `https://himanshu-goel.github.io` within ~2 minutes.

---

## File structure

```
.
├── _quarto.yml              # Site configuration
├── index.qmd                # Homepage
├── research.qmd             # Publications & conferences
├── code.qmd                 # GitHub repos
├── resources.qmd            # Curated tools & databases
├── cv.qmd                   # Full CV
├── tutorials/
│   ├── drug-design.qmd      # CADD tutorials with Python
│   ├── cheminformatics.qmd  # RDKit tutorials
│   ├── bioinformatics.qmd   # RNA-Seq tutorials
│   ├── agentic-ai.qmd       # LangGraph / RAG tutorials
│   └── ml-multimodal.qmd    # GNN / transformer tutorials
├── assets/
│   ├── custom.scss          # Light mode theme
│   └── custom-dark.scss     # Dark mode theme
└── .github/
    └── workflows/
        └── deploy.yml       # Auto-deploy to GitHub Pages
```

## Adding a new tutorial

1. Create a new `.qmd` file in `tutorials/`
2. Add front-matter: `title`, `description`, `date`
3. Write in Markdown + Python/R code chunks
4. `quarto preview` to check, then `git push` to publish

## Adding a publication

Edit `research.qmd` — copy any `.pub-entry` block and update the text.

## License

Content © Himanshu Goel. Code examples MIT licensed.
