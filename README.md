
# Supporting Data for *Accessible Chemical Space for Metal Nitride Perovskites*

This repository contains the research data generated for *Accessible Chemical Space for Metal Nitride Perovskites* aiming at discovering new stable nitride perovskites.





[![DOI](https://img.shields.io/badge/DOI-link__to__arxiv-blue)](https://arxiv.org/abs/2304.05450)

[![DOI](https://zenodo.org/badge/623976069.svg)](https://zenodo.org/badge/latestdoi/623976069)




## Folder Architecture

The folders contain respectively:

- 25_Candidates_HSE06: The structures of the 25 candidates presented in the manuscript and relaxed with HSE06
- Competing_phases: The structures of the 86 competing phases considered for thermodynamic stability and relaxed with HSE06
- Json_summaries: Json files containing all the relevant information. 
  This includes structures and energies for:
  - the 279 candidates in 15 possible tilts
  - the lowest energy tilted structure for all 279 candidates
  - the intermediate structures found during the phonon mapping process
  - the ten lowest energy structures for each of the 25 candidates obtained with AIRSS
  - the summary of all lowest-energy structures identified in both workflows
  - the materials already reported in literature and recomputed in this work
  - the energy above the hull for all considered structures calculated with HSE06 and PBEsol
- Switching_paths: The structures along the switching path and the Born effective charges of the material calculated in the initial configuration
