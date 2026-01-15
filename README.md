Materials for the paper: Lateral inhibition governs ancestral cellular patterning in fossil and extant liverworts (https://doi.org/10.64898/2025.12.27.696693)

- In the folders, you can find the necessary code to analyze the experimental statistics of dark/oil body cells in fossils (M. sharonae) and extant species (T. lacunosa, A. nana, M. polymorpha). Raw and segmented data will soon be available in the Zenodo repository.

- The file **linear_stability_analysis** contains the Python code for obtaining the parameter space region wherehomogeneous states are unstable due to diffusion, forming patterns.
- The file **stability_diagram** contains the Julia code for the bifurcation analysis. Specifically, it computes the saddle-node bifurcation curve (in cod-2 parameter space) associated with the state with a single dark/oil body cell in the middle of the tissue. All other patterning states are enclosed by this curve.
- The file **model_statistics** contains the code to simulate the mathematical model in a cellular tissue and perform the spatial statistics.
-  The file **random_statistics** contains the code to simulate a random model in a cellular tissue and perform the corresponding statistics.
