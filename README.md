# Computational Theory

Assessment repository for the Computational Theory module (Winter 26/27), completed as part of the BSc in Computing at Atlantic Technological University (ATU).

The assessment focuses on the [Secure Hash Standard (FIPS 180-4)](https://doi.org/10.6028/NIST.FIPS.180-4), building up a from-scratch implementation of SHA-256 in Python and NumPy, one problem at a time.

## Contents

- [`problems.ipynb`](problems.ipynb): the main notebook containing all problems, explanations, and code.
- [`requirements.txt`](requirements.txt): Python packages needed to run the notebook.
- [`AGENTS.md`](AGENTS.md): guidelines for AI-assisted work on this repository.

## Requirements

- Python 3.10+
- The packages listed in [`requirements.txt`](requirements.txt).

## Setup

Clone the repository and navigate into the directory:

```bash
git clone https://github.com/jhanney/computational-theory.git
cd computational-theory
```
Optionally, create a virtual environment to keep dependencies isolated from your system:
```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate
```
Then install the dependencies:
```bash
pip install -r requirements.txt
```
Then launch Jupyter and open the notebook:
```bash
jupyter notebook problems.ipynb
```

Run the notebook from top to bottom (`Kernel -> Restart & Run All`) to reproduce all results. The notebook is designed to run on a standard machine in three minutes or less, with no manual setup steps beyond the above.


## Structure of the notebook

The notebook is organised into the following problems, each under its own level-2 heading:

0. GitHub issue tracking
1. Representing SHA-256 data in Python
2. SHA-256 bitwise operations
3. Generating the SHA-256 constants
4. Padding and parsing messages
5. The SHA-256 compression function
6. Complete SHA-256

## Issues
[GitHub Issues](https://github.com/jhanney/computational-theory/issues) is used to track progress of each problem addressed throughout the notebook, with each main problem having its own parent issue and sub-issues each being closed on completion.

## References

References used throughout the notebook are cited inline, with full links provided in context.
