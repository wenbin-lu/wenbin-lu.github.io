---
title: "Solving Partial Differential Equations via Radon Neural Operator"
collection: publications
category: conferences
permalink: /publication/radon-neural-operator
excerpt: "A discretization-invariant, angle-aware Radon Neural Operator for PDE solving that achieves state-of-the-art performance."
date: 2025-09-18
venue: "NeurIPS 2025"
# slidesurl: ""
# paperurl: ""
# bibtexurl: ""
# citation: "Wenbin Lu et al. (2025). Solving Partial Differential Equations via Radon Neural Operator. In NeurIPS 2025."
---
In this work, we introduce the Radon Neural Operator (RNO), a novel data-driven framework for solving partial differential equations by leveraging the Radon transform to project input data into the sinogram domain, effectively reducing dimensionality while preserving the intrinsic structure of the PDE solution space. Unlike previous neural operators that rely on Fourier, Laplace, or wavelet transforms, RNO operates in a domain more naturally aligned with PDE geometry, enabling more accurate and holistic feature learning. We further propose an angle-reweighting technique and sinogram-domain convolution to adaptively emphasize important angular components, and rigorously prove that RNO satisfies a bilipschitz strong-monotonicity property, ensuring discretization invariance under diffeomorphism. Extensive experiments demonstrate that RNO achieves state-of-the-art performance across multiple PDE benchmarks and exhibits superior generalization capability, especially in zero-shot high-resolution inference scenarios.
