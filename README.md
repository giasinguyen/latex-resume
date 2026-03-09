# LaTeX CV — Nguyen Tran Gia Si

A professional, Harvard-style resume built with LaTeX. Clean, ATS-friendly, and modular.

---

## Preview

> 2-page PDF compiled with `pdflatex` from a modular LaTeX source.

---

## Project Structure

```
latex-cv/
├── README.md
├── docs/
│   └── PROMPT.md              # Design specification & requirements
└── resume/
    ├── NguyenTranGiaSi_Intern_Backend_Developer.pdf   # Original CV (PDF)
    └── cv-harvard/
        ├── main.tex           # Entry point — layout, header, imports
        ├── main.pdf           # Compiled output
        └── sections/
            ├── summary.tex        # Professional summary
            ├── education.tex      # Education history
            ├── experience.tex     # Work experience (template)
            ├── projects.tex       # Personal & academic projects
            ├── skills.tex         # Technical & soft skills
            └── certifications.tex # Awards & scholarships
```

---

## Getting Started

### Prerequisites

Install one of the following LaTeX distributions:

| Distribution | Platform | Download |
|---|---|---|
| **MiKTeX** | Windows (recommended) | https://miktex.org/download |
| **TeX Live** | Windows / Linux / macOS | https://tug.org/texlive/ |
| **MacTeX** | macOS | https://tug.org/mactex/ |

### Compile

```bash
cd resume/cv-harvard
pdflatex main.tex
pdflatex main.tex   # Run twice to resolve cross-references
```

The output PDF will be generated as `main.pdf`.

---

## CV Content

| Section | Description |
|---|---|
| **Header** | Name, phone, email, GitHub, location |
| **Professional Summary** | Background in Java / Spring Boot / Fullstack development |
| **Education** | IUH – Software Engineering, GPA 3.44/4.0 |
| **Technical Skills** | Languages, Frameworks, Databases, Tools |
| **Projects** | Portfolio, CodeHub, NatureGrain, SoleStore, HuongBien |
| **Awards** | 3× Academic Excellence Scholarships (2022–2024) |

---

## Design

- **Style:** Harvard-style academic resume layout
- **Font:** Latin Modern (`lmodern`)
- **Colors:** Harvard Crimson (`#A51C30`) for section headings
- **Compiler:** `pdflatex` compatible
- **Layout:** 2 pages, ATS-friendly

---

## Author

**Nguyen Tran Gia Si**
- Email: [giasinguyentran@gmail.com](mailto:giasinguyentran@gmail.com)
- GitHub: [github.com/giasinguyen](https://github.com/giasinguyen)
- Portfolio: [nguyentrangiasi.id.vn](https://nguyentrangiasi.id.vn)
