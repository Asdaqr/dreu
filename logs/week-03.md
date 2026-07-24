# Week 3

**Dates:** 06-29 to 07-03

## Goals

- Work on gaining familiarity with Azure
- Understand Azure's model
- Implement part of a pipeline from Hamlib -> Azure QRE
- Look at pyLIQTR

pyLIQTR was added for direct encoding of hamiltonian circuits,
rather than evolution via Trotter-Suzuki synthesis.

## Approach and Implementation

I worked on working thourgh and reading Azure's codebase and understanding how it
implements its qdk\[qre\] package. I also tried to understand how it gets its results.

I tried implementing qiskit -> azure qre.

I've been updating pyLIQTR to be more modern.

## Results

I've been understanding Azure pretty well, and have been trying to get across some of the
important features to the team.

Unsuccesful at pipeline, while qiskit to qre is not hard, I do not understand the
structure of hamlib and hdf5 files deeeply.

pyLIQTR has been a work in progress, as updating qualtran versions and swapping over from
pip to uv has been difficult. I will mention, swapping over pip to uv has been, very, very
nice in avoiding python version mismatching and think this detour has been productive.

## Notes


