<!-- This file is automatically compiled into the website. Please copy linked files into .website_src/ paths to enable website rendering -->

# Three-dimensional (3D) flow past airfoils

These benchmark cases use IDDES for turbulence modeling, and they simulate flow past a NACA 0021 airfoil. Input files are provided for 4 angles of attack: 30, 45, 60 and 90 degrees.

The Nalu-Wind hash used was 4faf299. Every case was run on Kestrel for at least 100 iterations to confirm input-file compatibility and provide profiling information in the log file footer. The 30 degree case was run with different numbers of nodes to establish scaling behavior, and the 45 degree case was run for 8000 steps to output force and moment results.

These cases correspond to the following publication:
Bidadi, S.; Vijayakumar, G.; Sharma, A.; Sprague, M.A. Mesh and model requirements for capturing deep-stall aerodynamics in low-Mach-number flows. J. Turbul. 2023, 24, 393–418.
