## SpaceDataLab

Open, verified space-data computation.

**[spacelab](https://github.com/SpaceDataLab/spacelab)** is astrodynamics in Rust, organised
around independent verification: fundamental astronomy and reference frames, SGP4, numerical and
semi-analytical propagation with the IERS 2010 force model, orbit determination, GNSS, satellite
laser ranging, coverage and constellation design, and Earth-observation geometry. Every number it
produces is checked against a lineage that did not come from the project, and each check is
written down with its oracle and residual.

- **Rust**: [`cargo add spacelab`](https://crates.io/crates/spacelab) · [API docs](https://docs.rs/spacelab)
- **Python**: [`pip install spacedatalab`](https://pypi.org/project/spacedatalab/), imported as `import spacelab`
- **C / C++**: a C ABI and a C++20 header, built with CMake from `crates/spacelab-capi`

`MIT OR Apache-2.0` · [spacedatalab.org](https://spacedatalab.org)
