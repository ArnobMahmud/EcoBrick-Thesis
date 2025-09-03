# EcoBrick Thesis
![developed-by-arnob](https://img.shields.io/badge/Developed%20by-Arnob%20Mahmud-1f425f.svg?style=plastic&logo=visual-studio-code&logoColor=007ACC&labelColor=beb4ab)

Eco bricks are building materials made from sustainable, recycled resources such as plastic, textiles, and other waste materials. They serve as an alternative to traditional clay bricks, which have a significant environmental impact due to the high energy consumption in their production process.

![Image](https://github.com/user-attachments/assets/31eae92b-faef-4994-b977-f2c957b69d10)

<table>
   <tr>
      <td><img src="https://github.com/user-attachments/assets/25e48e4b-7274-4ec7-9791-97387ffe8c84"></td>
      <td><img src="https://github.com/user-attachments/assets/b4e3e146-97c5-4a66-90e0-b9aeab596142"></td>
      <td><img src="https://github.com/user-attachments/assets/24b2e0c5-75dd-4764-addd-6f5894e404b0"></td>
   </tr>
   <tr class="text-center">
      <td><b>CRB-01 (Epoxy Brick)</b></td>
      <td><b>CRB-02 (PET Brick)</b></td>
      <td><b>CRB-03 (POP Brick)</b></td>
   </tr>
</table>


## Structure
- `main.tex`: Main LaTeX file for compiling the thesis.
- `Abstract.tex`, `Acknowledgement.tex`, `Cover.tex`: Front matter sections.
- `Chapters/`: Contains chapter-wise LaTeX files.
- `Sections/`: Contains section-wise LaTeX files for detailed content.
- `Assets/`: Images and figures used in the thesis.

## How to Compile
1. Ensure you have a LaTeX distribution installed (e.g., TeX Live, MiKTeX).
2. Compile `main.tex` using your preferred LaTeX editor or command line:
   ```
   pdflatex main.tex
   ```
   Repeat as needed to resolve references.


## Project Tree
```
EcoBrick-Thesis/
│
├── .github/
│   └── workflows/               # GitHub Actions for CI/CD (LaTeX build automation)
│
├── Assets/                      # All figures, tables, and media files
│   ├── Images/                  # Research images, graphs, charts
│   ├── Diagrams/                # Flowcharts, process diagrams
│   └── Tables/                  # Preformatted table data if stored separately
│
├── Chapters/                    # Main thesis chapters (each as separate .tex file)
│   ├── Chapter01_Introduction.tex
│   ├── Chapter02_Literature.tex
│   ├── Chapter03_Methodology.tex
│   ├── Chapter04_Results_Discussion.tex
│   ├── Chapter05__Conclusion.tex
│
├── Sections/                    # Subsections (optional modular organization)
│   ├── Experimental_Setup.tex
│   ├── Testing_Procedures.tex
│   ├── Data_Analysis.tex
│   └── Supplementary.tex
│
├── Abstract.tex                 # Abstract of the thesis
├── Acknowledgement.tex           # Acknowledgements section
├── Cover.tex                     # Title/cover page formatting
│
├── main.tex                     # Master LaTeX file (imports all sections)
├── main.pdf                     # Compiled thesis (final output)
│
├── main.aux                     # Auxiliary LaTeX files (auto-generated)
├── main.fdb_latexmk             # Latexmk build data
├── main.fls                     # Latexmk dependency file
├── main.lof                     # List of figures
├── main.log                     # Compilation log
├── main.lot                     # List of tables
├── main.synctex.gz              # SyncTeX for editor ↔ PDF sync
├── main.toc                     # Table of contents data
│
├── indent.log                   # Indentation/formatting log
├── README.md                    # Repository documentation (you are editing this)
└── .gitignore                   # Ignore LaTeX build artifacts & system files

```

## Read The Thesis
[Thesis-EcoBrick-Revised.pdf](https://github.com/user-attachments/files/22121414/Thesis.pdf)

## Highlights
- Utilizes recycled textile waste for sustainable brick production.
- Experimental results show bricks with 18% waste fabric by weight and polymer-based binders achieve compressive strengths of 3-7 MPa (435-1015 psi).
- Eco-bricks are lightweight, thermally efficient, and cost-effective.

## License
This project is for academic and research purposes.

## Author
Arnob Mahmud

## Contact
For questions or collaboration, please contact the repository owner via GitHub.
mail: arnob.tech.me@gmail.com
