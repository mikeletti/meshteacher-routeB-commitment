# MeshTeacher Route B — pre-evaluation freeze commitment

This repository time-stamps a cryptographic commitment made before the evaluation of the sealed
test and out-of-distribution sets of the MeshTeacher Route B study (learned anisotropic metrics
for closed-loop finite-element mesh adaptation, manufactured T2-M benchmark).

`G2_COMMITMENT.txt` contains the SHA-256 digest of `G2_FREEZE_MANIFEST.json`. That manifest lists
the SHA-256 digests of the frozen student network, all solver and analysis code, the study
protocol and its addenda, and the parameter files of the sealed test (24 instances) and OOD
(12 instances) designs. None of those instances had been solved when this commitment was made.

The manifest and every listed file will be released with the article; anyone can then verify
them against this digest:

    sha256sum G2_FREEZE_MANIFEST.json
    # expected: 77fc5f52f95a94c41f27efbb5b55eb78f654ddf384b18143cc9cbaa74f6dea1b
