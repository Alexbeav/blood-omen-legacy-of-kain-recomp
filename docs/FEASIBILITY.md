# Blood Omen: Legacy of Kain release feasibility

Status: `bootstrap_verified`; Windows package pending R2 and R3

The operator confirmed that the promoted private build reaches gameplay. This
source-only pilot does not inherit that claim. It must pass the exact-package
setup, generation, build, and startup gates before it can claim
`bootstrap_verified`.

The owned NTSC-U revision is `SLUS-00027`. The boot executable SHA-256 is
`1f2a6037b8e1b022698a8e71b1ae796045571b99d119ed23114a25eacabe8c47`.
The project uses the corrected `0x801FFF00` stack value from the shared
SYSTEM.CNF ownership finding.

The public package must not contain the disc, a BIOS, generated retail code,
a save, a prebuilt title executable, or a private absolute path.
