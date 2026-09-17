# MTF-Jupyter-widget

A slanted-edge MTF measurement (the [ImageJ MTF plugin](https://imagej.net/ij/plugins/mtf.html) idea) as an interactive jupyter widget, in the style of CIL's `islicer`.
Open `mtf_interactive.ipynb`, put a ROI over a straight, high-contrast, slightly slanted edge, and read the ESF / LSF / MTF live; capture ROIs and metrics to a table and export them to CSV.
Everything is in the one notebook — it needs numpy, scipy, pandas, matplotlib and ipywidgets, plus CIL only for the cameraman example.
Validated against the analytic MTF of a Gaussian-blurred synthetic edge.
