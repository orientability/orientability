# The Non-Orientable Surface Project

Open-source reference implementations of classical non-orientable surfaces —
immersions of the Klein bottle and the projective plane — rendered
interactively in Python.

These surfaces are closed and one-sided: they cannot exist in ordinary
three-dimensional space without passing through themselves. The code here
renders them on the GPU so their form, and the curves where they cross
themselves, can be seen and explored.

## Repositories

- **[boy-surface](https://github.com/orientability/boy-surface)** — Boy's
  surface, an immersion of the real projective plane with no pinch points and
  three-fold symmetry, visualized with an interactive Python/ModernGL renderer.
- **[ida-surface](https://github.com/orientability/ida-surface)** — the Ida
  surface, a non-orientable topological surface that is a three-dimensional
  shadow of a four-dimensional Klein bottle, visualized with an interactive
  Python/ModernGL renderer.
- **[klein-bottle](https://github.com/orientability/klein-bottle)** — the Klein
  bottle in its classic immersed "bottle" shape, a closed one-sided surface
  that cannot exist in three dimensions without passing through itself,
  visualized with an interactive Python/ModernGL renderer.

## About

Each implementation is an independent, modern rendering of mathematics
developed by others; the original work is credited in each repository.
Released under permissive open-source licenses.
