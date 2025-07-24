---
title: "Ecoacoustics"
collection: theses
permalink: /theses/ecoacoustics
excerpt: 'Using audio to monitor the environment.'
---

Broader context
---
Audio contains plenty of information about the status of our environment. Mammals, birds, and insects are often hard to see but make sounds that help us identify them even from a great distance. This is why bioacoustics (==the use of audio to detect the presence of life in a particular area) offers great promise in monitoring biodiversity. Thus, several works focus on *species detection*.

Ecoacoustics goes way beyond that though. It aims to extract robust indicators of species abundance and species diversity and link them to underlying parameters of the environment. For instance, we aim to answer questions such as "what is the impact of forest structure on the abundance of insects?" This helps us answer questions regarding the *interventions* we should or should not be doing to improve the biodiversity of our forests.

We aim to answer some of these questions in our DFG-funded [HearTheSpecies](https://www.biodiversity-exploratories.de/en/projects/using-computer-audition-to-understand-the-drivers-of-soundscape-composition-and-to-predict-parasitation-rates-based-on-vocalisations-of-bird-species/) project.

Current status
---
We are currently developing models for:
* Coarse soundscape classification, where we aim to recognize the high-level categories of Anthropophony (==sounds made by human activity), Biophony (==sounds made by animal activity), and Geophony (==weather-related phenomena such as wind or noise)
* Species-level classification of birds and insects
* Indicators of species abundance

We primarily work with our [autrainer](https://github.com/autrainer/autrainer/) toolkit. You can find some of our trained models in our [huggingface](https://huggingface.co/HearTheSpecies) space.

Open research questions
---

Ecoacoustic models are facing severe generalization issues. Even though ecoacoustic data is relatively easy to collect, it is very time-consuming to annotate it. Therefore, a lot of the datasets we have are coming from different geographic locations, are collected with different microphones, and contain a lot of label noise. These are all issues we aim to improve.


References
---

Xie, J., Zhong, Y., Zhang, J., Liu, S., Ding, C., & Triantafyllopoulos, A. (2023). A review of automatic recognition technology for bird vocalizations in the deep learning era. Ecological Informatics, 73, 101927.

Triantafyllopoulos, A., Gebhard, A., Milling, M., Rampp, S., & Schuller, B. (2024). An automatic analysis of ultrasound vocalisations for the prediction of interaction context in captive Egyptian fruit bats. arXiv e-prints, arXiv-2406.

Gebhard, A., Triantafyllopoulos, A., Bez, T., Christ, L., Kathan, A., & Schuller, B. W. (2024, April). Exploring meta information for audio-based zero-shot bird classification. In ICASSP 2024-2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 1211-1215). IEEE.

Stowell, D. (2022). Computational bioacoustics with deep learning: a review and roadmap. PeerJ, 10, e13152.

Schuller, B. W., Akman, A., Chang, Y., Coppock, H., Gebhard, A., Kathan, A., ... & Pokorny, F. B. (2024). Ecology & computer audition: Applications of audio technology to monitor organisms and environment. Heliyon, 10(1).