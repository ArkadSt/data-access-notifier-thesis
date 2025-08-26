# Defense Presentation

This folder contains the LaTeX Beamer presentation for the thesis defense.

## Files

- `defense-presentation.tex` - Main LaTeX Beamer presentation file
- `build-presentation.sh` - Build script to compile the presentation
- `README.md` - This file

## Building the Presentation

### Prerequisites
Make sure you have LaTeX installed with the Beamer package. On Ubuntu/Debian:
```bash
sudo apt install texlive-latex-base texlive-latex-extra texlive-fonts-recommended
```

### Compilation
Run the build script:
```bash
./build-presentation.sh
```

Or compile manually:
```bash
pdflatex defense-presentation.tex
pdflatex defense-presentation.tex  # Second run for proper references
```

## Presentation Structure

The presentation includes:

1. **Introduction** - Problem statement and motivation
2. **Background** - Current Andmejälgija system and its limitations
3. **Implementation Approach** - Analysis of different technical approaches
4. **Technical Solution** - Architecture and key challenges
5. **Results** - Implementation outcomes and testing observations
6. **Limitations** - Current constraints and known issues
7. **Impact & Significance** - Contributions and policy implications
8. **Conclusions** - Summary and future work

## Timing Guidance

The presentation is designed for approximately 15-20 minutes:
- Introduction: 2-3 minutes
- Background: 3-4 minutes  
- Technical sections: 6-8 minutes
- Results & Impact: 3-4 minutes
- Conclusions: 1-2 minutes

## Notes

- Images are referenced from the main thesis `english/figures/` directory
- The presentation uses the Madrid Beamer theme with University of Tartu colors
- All technical details are simplified for presentation format while maintaining accuracy
- Key findings and limitations are clearly highlighted
