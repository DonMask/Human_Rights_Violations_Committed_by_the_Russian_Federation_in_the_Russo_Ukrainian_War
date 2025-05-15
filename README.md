# StrategicCowardice

**Russia’s War on Ukraine: Human Rights and EU-NATO Silence**  
*Blood in the Balance*  

An open-source project documenting human rights violations committed by the Russian Federation in the Russo-Ukrainian War, alongside the strategic silence of international actors (EU, NATO, and others). This work serves as a moral, legal, and factual reference to expose the human cost of inaction and propose actionable solutions for global responsibility.

## Project Scope
- Document verified human rights abuses using credible sources (UN, Amnesty International, Human Rights Watch).
- Analyze violated international agreements (e.g., UN Charter, Geneva Conventions, Budapest Memorandum).
- Highlight human and global consequences, including civilian casualties, displacement, and ecological devastation.
- Propose a manifesto for justice, accountability, and sustainable reconstruction.
- Dedicate the work to the victims and global supporters of Ukraine.

## Repository Structure
```
/Human_Rights_Violations_Committed_by_the_Russian_Federation_in_the_Russo_Ukrainian_War/
├── docs/
│   ├── graphs.tex           - TikZ graphs for civilian casualties and refugees
│   ├── logo.tex             - TikZ logo (justice scale)
│   ├── references.bib       - Bibliography in BibLaTeX format
│   ├── summary.tex          - Executive summary LaTeX source
├── CONTRIBUTING.md          - Guidelines for contributions
├── LICENSE                  - Creative Commons Attribution 4.0 International (CC BY 4.0)
├── MAKEFILE                 - Makefile for local compilation
├── README.md                - Project overview and instructions
├── main.tex                 - Main report LaTeX source
├── output.pdf               - Compiled full report
├── summary.pdf              - Compiled executive summary
```

## Formats
- **PDF**: Academic-style report (`output.pdf`) and executive summary (`summary.pdf`) in English.

## Building the Report

### In Overleaf
1. Create a new project in Overleaf.
2. Upload all files, maintaining the structure above (place `graphs.tex`, `logo.tex`, `references.bib`, `summary.tex` in `docs/`).
3. Set `main.tex` as the main file to compile `output.pdf`, or `summary.tex` for `summary.pdf`.
4. Ensure the compiler is set to `pdflatex` and bibliography processor to `biber` (Overleaf defaults are usually fine).
5. Compile to generate PDFs.

### Locally
To compile locally, ensure you have LaTeX (e.g., TeX Live) and Biber installed, then run:
```bash
make
```
This compiles `main.tex` to `output.pdf` and `summary.tex` to `summary.pdf`. To clean auxiliary files:
```bash
make clean
```

## Accessing the Report
- **GitHub**: [DonMask/Human_Rights_Violations_Committed_by_the_Russian_Federation_in_the_Russo_Ukrainian_War](https://github.com/DonMask/Human_Rights_Violations_Committed_by_the_Russian_Federation_in_the_Russo_Ukrainian_War)
- **Downloads**:
  - Full report: `output.pdf`
  - Executive summary: `summary.pdf`
- **Zenodo**: DOI • https://doi.org/10.5281/zenodo.15427314

## Distribution
- Share `output.pdf` or `summary.pdf` via social media, email, or academic platforms to amplify impact.
- Use hashtags: `#UkraineJustice`, `#HumanRights`, `#RussoUkrainianWar`.
- The executive summary (`summary.pdf`) is designed for quick distribution to media, NGOs, or policymakers.

## How to Contribute
See `CONTRIBUTING.md` for guidelines on:
- Sourcing verified data or updating graphs.
- Translating the report or summary into other languages.
- Improving LaTeX code or repository automation.
- Suggesting new distribution channels (e.g., media, organizations).

Submit contributions via GitHub pull requests or email: **bergerteodor@googlemail.com**

## License
This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**. See `LICENSE` for details.

## Publication
- **GitHub**: Published as of May 15, 2025, at [DonMask/Human_Rights_Violations_Committed_by_the_Russian_Federation_in_the_Russo_Ukrainian_War](https://github.com/DonMask/Human_Rights_Violations_Committed_by_the_Russian_Federation_in_the_Russo_Ukrainian_War).
- **Zenodo**: A DOI will be generated for long-term archiving (pending upload).
- The report is ready for academic, activist, and public distribution.

## Contact
For inquiries, open a GitHub Issue or email: **bergerteodor@googlemail.com**

## Acknowledgments
This project is dedicated to the victims of the Russo-Ukrainian War and the global community standing in solidarity with Ukraine.  
