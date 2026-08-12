# Somach Systems, Inc.

**Silent speech from cheap surface EMG.**

Subvocalization is a muscle phenomenon, not a brain one. When you articulate a word without sound, your motor cortex still drives the tongue, jaw, hyoid and larynx below the threshold of audible speech. That activity is readable from the skin MINUS the implant, helmet, and magnetically shielded room (looking at you, Meta's Text2Qwerty).

We build the cheapest open stack that actually reads it.

---

### Research

**[semg-silent-speech](https://github.com/Somach-Systems-Inc/semg-silent-speech)** : Can a $40 device read silent speech? (arXiv:2601.06516) A cost-feasibility benchmark for consumer-grade sEMG. Full hardware BOM, firmware, ML pipeline, and replication guide. `48.9–51.8% 5-fold CV on a 6-class vocabulary against a 16.7% chance baseline` : and an honest account of exactly where $40 hits its ceiling.

**[ear-emg-forward-model](https://github.com/Somach-Systems-Inc/ear-emg-forward-model)** : Which speech muscles are visible from behind the ear? Mostly none. A volume-conductor model on the MIDA head (116 compartments, reciprocity, orientation and electrode-count controls): five articulators favour the jaw montage by 9.0 to 21.2 dB, and no muscle robustly favours the ear. We killed our own easiest form factor with a laptop before building it. arXiv submission shipped August 2026.

---

### Product

**Health Passport** is the shipped side of the same thesis: an on-device medical-document AI, live on [Google Play](https://play.google.com/store/apps/details?id=com.carlkho.healthpassport). A vision-language model runs entirely on the phone, zero cloud. Qualcomm x Nexa On-Device Bounty Grand Champion, 100+ teams.

### Why open

The well-funded labs optimise word error rate and never report cost. We think the more useful frontier is **accuracy per dollar, reproducible by anyone**. Every result here ships with the BOM, the firmware, the data, and the honest number : including when the honest number is disappointing.

---

*San Francisco. Founded 2026.*
