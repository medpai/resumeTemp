# Resume & Cover Letter Templates (LaTeX)

This repository contains LaTeX templates for ATS‑friendly resumes and cover letters. It includes English and French variants and tailored versions for specific roles.

## Repository

Clone your fork:

```bash
git clone https://github.com/medpai/resumeTemp.git
cd resumeTemp
```

## Files

- `main.tex` — English resume (customer service / counter support focused)
- `main_fr.tex` — French resume (technicien informatique / centre de services)
- `resume_aircraft_plater.tex` — Targeted resume for Aircraft Plater role
- `cover_letter_wheatland.tex` — Cover letter for Wheatland Regional Library (Computer Technician)
- PDFs are generated alongside `.tex` files upon compilation

## Build

Prerequisite: LaTeX distribution (MiKTeX/TeX Live) or Overleaf.

Compile locally (example):

```bash
pdflatex main.tex
pdflatex main_fr.tex
pdflatex resume_aircraft_plater.tex
pdflatex cover_letter_wheatland.tex
```

## ATS notes

- Use standard sections (Experience, Education, Skills)
- Keep formatting simple (standard bullets, fonts)
- Include role‑specific keywords from job descriptions
- Avoid heavy tables/graphics and headers/footers

## License

Personal use permitted.
