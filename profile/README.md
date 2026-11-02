## SpaceDataLab

Open, verified space-data computation.

**[spacelab](https://github.com/SpaceDataLab/spacelab)** is astrodynamics in Rust, with the
verification as the deliverable. It covers fundamental astronomy and reference frames, SGP4,
numerical and semi-analytical propagation with the IERS 2010 force model, orbit determination,
GNSS, satellite laser ranging, coverage and constellation design, and Earth-observation geometry.
Mathematics decides what is correct, every check is written down with its residual, and other
codes are comparisons, never the proof.

- **Rust**: [`cargo add spacedatalab`](https://crates.io/crates/spacedatalab), with every spacelab crate
  behind a feature, or [`cargo add spacelab`](https://crates.io/crates/spacelab) for the core ·
  [API docs](https://docs.rs/spacelab)
- **Python**: [`pip install spacedatalab`](https://pypi.org/project/spacedatalab/), then `import spacedatalab`
- **C / C++**: a C ABI and a C++20 header, built with CMake from `crates/spacelab-capi`

The Rust and Python entry points are built in
[spacedatalab](https://github.com/SpaceDataLab/spacedatalab), which puts each product behind one
dependency per language.

`MIT OR Apache-2.0` · [spacedatalab.org](https://spacedatalab.org)
