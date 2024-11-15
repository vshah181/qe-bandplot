# QE BandPlot
This is a simple utility script to plot QuantumESPRESSO band strcutures.
The programme assumes that pw.x and bands.x have both successfully been run, and that the gnuplot file as been generated by bands.x.

The input file should be called INPUT.qebp and an example is provided here:
#### INPUT.qebp
    seedname CoSi
    e_fermi  17.3456
    figsize  6.0 4.0
    klabels  Γ X M Γ R X
    yrange   11 23
    colour   tab:purple
    filband  CoSi_band.dat.gnu
    ppfile   pp.band.CoSi.out

# Dependency list
- Python $\qeg$ 3.7.2
- Numpy
- Matplotlib
- Arial font
