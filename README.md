# MeshTeacher Route B — pre-evaluation freeze commitments

This repository time-stamps cryptographic commitments made before evaluating sealed test sets of
the MeshTeacher Route B study (learned anisotropic metrics for closed-loop finite-element mesh
adaptation, manufactured T2-M benchmark). Each release is archived on Zenodo.

| Gate | File | SHA-256 of the manifest | What it freezes |
|---|---|---|---|
| G2 (release v1.0-g2) | `G2_COMMITMENT.txt` | `77fc5f52f95a94c41f27efbb5b55eb78f654ddf384b18143cc9cbaa74f6dea1b` | frozen student network, code, protocol and addenda G1/P2, sealed test (24) and OOD (12) designs |
| G3 (release v1.1-g3) | `G3_COMMITMENT.txt` | `92951e830361bb40ad9733eedbe5b6c11d803a0e174b8c070f061f8c0cf17bf7` | hybrid policy (Addendum H, k = 2), its code and analysis, new sealed test2 (24) and ood2 (12) designs |
| G4 (release v1.2-g4) | `G4_COMMITMENT.txt` | `762c00033a8acc0b7e90b1a955b598e2cc019e1e7cd829e7714eba8e5126582e` | source/residual ablation (Addendum G4): S-f student, masking and analysis code, new sealed test3 (24) and ood3 (12) designs |

None of the corresponding instances had been solved when each commitment was made. The manifests
and every listed file will be released with the article; anyone can verify them with

    sha256sum G2_FREEZE_MANIFEST.json G3_FREEZE_MANIFEST.json G4_FREEZE_MANIFEST.json
