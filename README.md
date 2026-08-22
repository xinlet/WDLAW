# Using Wavelet Domain Fingerprints to Improve Source Camera Identification

## Abstract

Camera fingerprint detection plays a crucial role in source identification and image forensics, with wavelet denoising approaches proving particularly effective for extracting sensor pattern noise (SPN). In this article, we introduce the concept of a wavelet domain (WD) fingerprint, redefining the representation of the extracted fingerprint from the conventional image domain to the native wavelet coefficient domain. Rather than reconstructing the fingerprint as a spatial domain image, fingerprint comparison is performed directly on the wavelet coefficients, eliminating the final inverse transform and subsequent image-domain post-processing. This reformulation streamlines the fingerprint extraction and comparison pipeline while preserving the information required for source camera identification. The proposed framework is applicable to existing wavelet-based SPN extraction methods and is demonstrated using two representative state-of-the-art pipelines. Experimental results on real-world datasets show that the proposed approach significantly reduces computational cost, making it well-suited for large-scale source camera identification applications.

## Authors

[Xinle Tian](https://xinlet.github.io/), [Matthew Nunes](https://people.bath.ac.uk/man54/homepage.html), [Emiko Dupont](https://researchportal.bath.ac.uk/en/persons/emiko-dupont/), 
[Shaunagh Downing](https://www.cameraforensics.com/about/shaunagh-downing/), [Freddie Lichtenstein](https://www.cameraforensics.com/about/fred-lichtenstein/), [Matt Burns](https://www.cameraforensics.com/about/matt-burns/)

## Links
Forensic Science International: Digital Investigation link can be found at [https://doi.org/10.1016/j.fsidi.2026.302196]<br />
Preprint paper link can be found at [https://arxiv.org/abs/2507.01712]<br />

## Dataset
Dresden Image Database can be found at [https://www.kaggle.com/datasets/micscodes/dresden-image-database]<br />

## Industrial collaboration
This work was completed through collaboration with [CameraForensics](https://www.cameraforensics.com/), an IT company based in Bristol, UK.
