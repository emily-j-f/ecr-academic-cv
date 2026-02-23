# 📄 ecr-academic-cv  
**Academic LaTeX CV template for emerging and early-career researchers**

This repository contains a customizable LaTeX CV template designed for emerging and early-career researchers (ECRs). It includes structured academic sections and optional open science badges (e.g., Open Data, Open Materials, Open Code, Preregistered).

The template is designed to be:
- Clean and professional  
- Easy to customize  
- Open science friendly  
- Suitable for academic job and grant applications  

---

# 🚀 Getting Started

You can use this template in two main ways:

## Option 1 — Use with Overleaf (Recommended)

1. Download the repository as a `.zip` file.
2. Go to https://www.overleaf.com
3. Create a new project → “Upload Project”
4. Upload the entire folder (including the `badges/` folder)
5. Open `main.tex`
6. Click “Recompile”

That’s it.

---

## Option 2 — Compile Locally

You need a LaTeX distribution installed:

- **TeX Live** (Linux)  
- **MiKTeX** (Windows)  
- **MacTeX** (Mac)  

Then run:

```bash
pdflatex main.tex
```
Or compile using your LaTeX editor of choice.

📁 Repository Structure

It is important to keep the folder structure intact:
main.tex
```
badges/
    opendata.png
    openmaterial.png
    opencode.png
    preregistered.png
    preregisteredplus.png
```

⚠️ The badges/ folder must stay in the same directory as main.tex.
If you delete it or move it, the document will not compile if badge images are used.

# 🏅 Open Science Badges

This template allows you to display open science badges next to publications.

Available badges:

- Open Data
- Open Materials
- Open Code
- Preregistered
- Preregistered+

## How Badges Work

Each publication can optionally display badges using a two-column layout:

Left column → badges
Right column → publication text

If you do not want to use badges:

- Remove the badge legend section
- Replace the publication layout with a simple \item[] format

## ✏️ Customizing the Template

You can easily:

- Change fonts (see preamble)

- Add or remove sections

- Reorder publications

- Remove badge functionality

- Adjust spacing (\vspace)

- Modify margins in the geometry package

Your personal information is defined at the top of main.tex:
```
\newcommand{\name}{Your Name}
\newcommand{\position}{Your Position}
\newcommand{\affiliation}{Your Institution}
\newcommand{\address}{City, Country}
\newcommand{\phone}{Your Phone}
\newcommand{\email}{your@email.com}
```

## 🛠 Troubleshooting
❌ “File badges/opendata.png not found”

Make sure:

- The badges/ folder is uploaded

- It is in the same directory as main.tex

- File names have not been changed

❌ Compilation error related to images

Try:

- Re-uploading the full repository

- Checking that image file names are unchanged

- Recompiling twice

## 💡 Suggested Use

This template is especially useful for:

- Academic job applications

- Postdoc applications

- Grant submissions

- Open science oriented contexts (e.g., SIPS, meta-science, reproducibility communities)

# 🤝 Contributing

Contributions are welcome!
