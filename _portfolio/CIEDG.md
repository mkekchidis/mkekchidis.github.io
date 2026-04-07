---
title: "CI Electrodogram"
excerpt: "Simulates the firing pattern of a 16-channel cochlear implant with current steering and pulse time-gating.<br/><img src='/images/500x300.png'>"
collection: portfolio
date: 2026-04-06
---

Cochlear implants are auditory prosthetic devices that restore hearing functionality for the deaf and hard-of-hearing (DHH). However, they face many limitations in sound fidelity, most notably in temporal coding [^1][^2][^3][^4][^5][^6]. Pulse rate is known to affect the quality of sounds and hence the user's hearing experience [^1][^3]. Simulating the firing patterns of a cochlear implant is a valuable step toward understanding the bridge between external sounds and the psychoacoustics of a CI user. There currently is no widely-available software for simulating CI stimulation. To address this, I here present a python program that produces a cochlear implant electrodogram inspired by current steering and pulse-gating approaches described in the literature. This implementation is based on publically available descriptions in Nogueira et al. (2009)[^7] and the supplementary information of Stupak et al. (2021)[^1], and hence bears similiarity to the processing strategies in use by Advanced Bionics. I hope that this can serve as an approximation of current-steering and pulse-gating approaches to CI stimulation for educational applications.

[^1]: Stupak N, Todd AE, Landsberger DM. Place-Pitch Interval Perception With a Cochlear Implant. Ear Hear. 2021 Mar/Apr;42(2):301-312. doi: 10.1097/AUD.0000000000000922. PMID: 33606415; PMCID: PMC8915956.
[^2]: Bissmeyer SRS, Goldsworthy RL. Combining Place and Rate of Stimulation Improves Frequency Discrimination in Cochlear Implant Users. Hear Res. 2022 Oct;424:108583. doi: 10.1016/j.heares.2022.108583. Epub 2022 Jul 22. PMID: 35930901; PMCID: PMC10849775.
[^3]: Goldsworthy RL, Bissmeyer SRS. Cochlear Implant Users can Effectively Combine Place and Timing Cues for Pitch Perception. Ear Hear. 2023 Nov-Dec 01;44(6):1410-1422. doi: 10.1097/AUD.0000000000001383. Epub 2023 Oct 20. PMID: 37788011; PMCID: PMC10593103.
[^4]: Carlyon RP, Deeks JM, Delgutte B, Chung Y, Vollmer M, Ohl FW, Kral A, Tillein J, Litovsky RY, Schnupp J, Rosskothen-Kuhl N, Goldsworthy RL. Limitations on Temporal Processing by Cochlear Implant Users: A Compilation of Viewpoints. Trends Hear. 2025 Jan-Dec;29:23312165251317006. doi: 10.1177/23312165251317006. Epub 2025 Mar 17. PMID: 40095543; PMCID: PMC12076235.
[^5]: O'Connell SR, Papadopoulos JM, Inouye D, van der Donk BJ, Gan H, Goldsworthy RL. Musically evoked emotions in cochlear implant users and those with no known hearing loss. Hear Res. 2025 Mar;458:109196. doi: 10.1016/j.heares.2025.109196. Epub 2025 Jan 27. PMID: 39914280; PMCID: PMC12341844.
[^6]: Landsberger DM, Vermeire K, Claes A, Van Rompaey V, Van de Heyning P. Qualities of Single Electrode Stimulation as a Function of Rate and Place of Stimulation with a Cochlear Implant. Ear Hear. 2016 May-Jun;37(3):e149-59. doi: 10.1097/AUD.0000000000000250. PMID: 26583480; PMCID: PMC4844766.
[^7]: Nogueira, Waldo & Litvak, Leonid & Edler, Bernd & Ostermann, Jörn & Büchner, Andreas. (2009). Signal Processing Strategies for Cochlear Implants Using Current Steering. EURASIP J. Adv. Sig. Proc.. 2009. 10.1155/2009/531213. 


See the github repository at: [https://github.com/mkekchidis/CI_electrodogram](https://github.com/mkekchidis/CI_electrodogram)
