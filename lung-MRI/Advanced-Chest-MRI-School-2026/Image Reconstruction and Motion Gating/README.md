# Image Reconstruction and Motion Gating

Created by Dr Nicholas Senn, AMT Center, University of Aberdeen

Originally created for the Advanced Chest MRI School, Aberdeen, Septemeber 2026

Email: nicholas.senn2@abdn.ac.uk

Github page: https://github.com/nicholas-senn/teaching-resources/tree/main/lung-MRI/Advanced-Chest-MRI-School-2026/Image%20Reconstruction%20and%20Motion%20Gating

Developed as part of the V|LF-Spiro3D project: https://v-lf-spiro3d.eu/

-----------------------------------------------------------

This material is provided for educational and research purposes only.
It is not intended for clinical use.

© Nicholas Senn, 2026.
Released under the MIT Licence.

The software is provided "as is", without warranty of any kind.

-----------------------------------------------------------

## About This Tutorial

This tutorial is designed to demonstrate the principles of non-Cartesian MRI reconstruction, self-navigation, amplitude gating and phase-portrait gating.

The notebook contains Python code that performs the image reconstruction and motion-sorting steps. **It is not necessary to understand any of the code in order to achieve the learning objectives of this tutorial.**

The primary learning objectives are to understand:

- How a kooshball acquisition samples k-space.
- Why non-Cartesian image reconstruction requires gridding.
- How self-navigation signals can be extracted from radial MRI data.
- How amplitude gating can be used to reduce motion blurring.
- Why amplitude gating has limitations.
- How phase-portrait analysis can separate different stages of a motion cycle.

Participants who are interested in the implementation details are encouraged to explore the code cells and function definitions. However, the tutorial can be completed successfully by focusing on the figures, results and discussion questions provided throughout the notebook.
