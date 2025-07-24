---
title: "Speech emotion recognition"
collection: theses
permalink: /theses/ser
excerpt: 'Using speech to recognize emotions.'
---

Broader context
---
A speaker's emotional status influences both *what* they are saying (==linguistics) and *how* they are saying it (==paralinguistics). The linguistic/textual part of speech conveys primarily *valence*, i.e. the polarity of a speaker's emotion (how positive or negative it is), while the paralinguistic/auditory part of it denotes their *arousal*, i.e. the intensity of a their emotion *independent* of valence. Our aim is to use both informations treams (text&audio) to predict emotions.

Current status
---
I have 7+ years of experience working on emotion recognition. Some exemplary works can be found below. In general, we've hit a wall after the publication of Wagner et al. (2023) where we used pretrained transformers. We are currently working on several avenues to improve performance beyond that plateau by considering personalization, better pretraining, and better integration of acoustics with linguistics.

A dimensional model that predictis arousal and valence (and dominance) can be found [here](https://huggingface.co/audeering/wav2vec2-large-robust-12-ft-emotion-msp-dim). We have further finetuned it for categorical dimensions ([here](https://huggingface.co/autrainer/msp-podcast-emo-class-big4-w2v2-l-emo)).

Open research questions
---
There are several open topics:

* Why does emotion recognition work better for some speakers than others?
* How can we integrate linguistics and acoustics more tightly?
* How can we take advantage of context?
* How can we adapt to individual speakers?
* How can we generalize across languages and recording environments?
* How can we adapt to individual listeners?

References
---

Triantafyllopoulos, A., & Schuller, B. (2024). Enrolment-based personalisation for improving individual-level fairness in speech emotion recognition. arXiv preprint arXiv:2406.06665.

Triantafyllopoulos, A., Batliner, A., Rampp, S., Milling, M., & Schuller, B. (2024). INTERSPEECH 2009 Emotion Challenge Revisited: Benchmarking 15 Years of Progress in Speech Emotion Recognition. arXiv preprint arXiv:2406.06401.

Wagner, J., Triantafyllopoulos, A., Wierstorf, H., Schmitt, M., Burkhardt, F., Eyben, F., & Schuller, B. W. (2023). Dawn of the transformer era in speech emotion recognition: closing the valence gap. IEEE Transactions on Pattern Analysis and Machine Intelligence, 45(9), 10745-10759.

Triantafyllopoulos, A., Reichel, U., Liu, S., Huber, S., Eyben, F., & Schuller, B. W. (2023). Multistage linguistic conditioning of convolutional layers for speech emotion recognition. Frontiers in Computer Science, 5, 1072479.

Triantafyllopoulos, A., Wagner, J., Wierstorf, H., Schmitt, M., Reichel, U., Eyben, F., ... & Schuller, B. W. (2022). Probing speech emotion recognition transformers for linguistic knowledge. arXiv preprint arXiv:2204.00400.

Triantafyllopoulos, A., Liu, S., & Schuller, B. W. (2021, July). Deep speaker conditioning for speech emotion recognition. In 2021 IEEE International Conference on Multimedia and Expo (ICME) (pp. 1-6). IEEE Computer Society.