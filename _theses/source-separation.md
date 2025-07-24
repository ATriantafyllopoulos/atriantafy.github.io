---
title: "Source separation"
collection: theses
permalink: /theses/source-separation
excerpt: 'Decomposing an audio stream to its individual salient components.'
---

Broader context
---
Contrary to computer vision, where different objects are separated in space and potentially occlude one another, audio sources are superimposed in time. This makes it harder to identify the individual sources -- a problem that is known a source separation. Source separation can be seen as a means to an end (==to improve the recognition of sources) or as an end in itself (==to recover the individual sources for further processing).

Current status
---
Our work has mainly focused on speech *denoising* (==we treat speech as the only desirable signal and everything else as interference). We aim to generalize this by considering universal sound source separation, which aims to decompose a soundscape to all of its individual sources. Moreover, separation (& denoising) performance still leaves much to be desired, especially using low-compute models that can be run on-device, so we are focused on improving separation (& denoising) performance through architectural innovation.

Open research questions
---
I am generally interested in the following research questions:
* How can we make a universal source separation model?
* How are architectural biases connected to model performance, especially on specific source combinations?
* How can we make smaller models perform better?
* How can we make source separation *adaptive* to context

References
---

Tsangko, I., Triantafyllopoulos, A., Müller, M., Schröter, H., & Schuller, B. W. (2025, April). DFingerNet: Noise-Adaptive Speech Enhancement for Hearing Aids. In ICASSP 2025-2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 1-5). IEEE.

Triantafyllopoulos, A., Tsangko, I., Müller, M., Schröter, H., & Schuller, B. W. (2025, September). Speaker vs Noise Conditioning for Adaptive Speech Enhancement. In ITG Conference on Speech Communication (forthcoming). IEEE.