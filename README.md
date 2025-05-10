# LaTeX CV

This repository contains a customized LaTeX CV template based on the original work by [Sourabh Bajaj](https://github.com/sb2nov/resume). It includes personal modifications tailored for a Computer Science student with a focus on systems programming, embedded development, and community involvement.

## Formats Included

- **Format 1**: Enhanced version with a profile picture and a "Profile" section.
- **Format 2**: Lightweight, clean version without image support but with more community involvement details.

## Key Features

- Clean, ATS-friendly layout
- Embedded profile picture (Format 1)
- Dedicated sections for:
  - Experience (e.g., kernel modules, Hugo, Raspberry Pi 5)
  - Projects (e.g., POSIX shell, ray tracing, Nand2Tetris)
  - Community Work (e.g., IEEE, MLSA, Book Club)
  - Skills & Participations

## How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/hissamshar/cv.git
   cd cv
   ```

2. Build the CV using `pdflatex`:
   ```bash
   pdflatex CV.tex
   ```

> Make sure the `PROFILE.jpeg` is in the same directory when compiling **Format 1**.

## License

This project is licensed under the [MIT License](LICENSE), following the original repository guidelines.

## Acknowledgments

- Based on [sb2nov/resume](https://github.com/sb2nov/resume)
- Modified by [Hisam Mehboob](https://hissamshar.github.io)

