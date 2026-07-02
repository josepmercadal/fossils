Materials for the paper *Lateral inhibition governs ancestral cellular patterning in fossil and extant liverworts* (https://doi.org/10.64898/2025.12.27.696693)

- In the folders, you can find the necessary code to analyze the experimental statistics of dark/oil body cells in fossils (M. sharonae) and extant species (T. lacunosa, A. nana, M. polymorpha). Raw and segmented data are available in the Zenodo repository (https://doi.org/10.5281/zenodo.19886342). These analyses are related to Figures 1, 2, 3, and 4.

- The file **linear_stability_analysis** contains the Python code for obtaining the parameter space region where homogeneous states are unstable due to diffusion, forming patterns. This is used to compute region 6 in Figure 3C and the pink regions in Figure S4)
- The file **stability_diagram** contains the Julia code for the bifurcation analysis. This is used in Figure 3C and Figure S4 to compute saddle-node curves (in cod-2 parameter space) associated with homogeneous states (enclosing the grey regions), and the saddle-node bifurcation curves associated with the state in which a single dark/oil body cell is located in the middle of the tissue. This curve encloses all other patterning states. 
- The file **model_statistics** contains the Python code to simulate the mathematical model in a cellular tissue and perform the spatial statistics. Associated with Figures 3 and 4.
-  The file **random_statistics** contains the Python code to simulate a random model in a cellular tissue and perform the corresponding statistics. Associated with Figures 2, 3, and 4.
