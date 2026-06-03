Randomness or Interaction? Testing EMH, Ising, and Lux-Marchesi Models Against Financial Market Stylized Facts

Replication archive contents
----------------------------
paper.tex            LaTeX manuscript
references.bib       Bibliography used by the manuscript
figures/             All manuscript figures, renamed with simple file names
data/                Generated simulation datasets and summary statistics
code/                Python script used to reproduce simulations, figures, and data
README.txt           This file

Reproducibility notes
---------------------
Random seed: 42
Sample length: 6,288 observations

EMH model:
- Gaussian random walk calibrated to empirical S&P 500 mean and standard deviation.

Ising model:
- Lattice size: 40x40
- Coupling: J = 1.0
- Price sensitivity: lambda = 0.10
- Noise standard deviation: 0.002
- Regimes: beta = 0.20, beta = 0.44, beta = 0.70

Simplified Lux-Marchesi model:
- Fundamentalists: 500
- Chartists: 500
- Total agents: 1000
- Initial price: 100
- Fundamental price: 100
- Strategy-switching parameter: 0.10

Data availability statement
---------------------------
The empirical S&P 500 data used in this study are publicly available through Yahoo Finance.
The simulation code and generated data are included in this replication archive.

Corresponding author
--------------------
Lehlohonolo Moloi
Institute for Collider Particle Physics (ICPP)
University of the Witwatersrand
Email: 1874376@students.wits.ac.za
