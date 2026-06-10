---
name: MetaCAD
logo_url: https://raw.githubusercontent.com/metacadio/.github/main/profile/logo.png
website: https://metacad.io/
description: MetaCAD is a browser-based maritime engineering CAD — ship stability, loading computer and hydrostatics powered by a Rust → WebAssembly core.
keywords: maritime cad engineering naval architecture ship stability rust simulation production application
---

MetaCAD is a browser-based maritime engineering workspace: ship stability, loading computer, draft survey, hydrostatics and emissions calculators that run fully client-side.

![MetaCAD Loadicator ScreenShot](https://raw.githubusercontent.com/metacadio/.github/main/profile/screenshots/05-loadicator-sim.png)

The numerical core is written in Rust and compiled to WebAssembly. Heavy workloads — Monte-Carlo capsize simulation, GZ cross-curves of stability, fleet-wide CII emissions rating — run in the browser at near-native speed (a 44× speedup over the original JavaScript baseline on the ONR Tumblehome capsize benchmark). Vessel data never leaves the device, so the suite also works fully offline.

## Additional Resources

- [Reproducible validation benchmarks](https://github.com/metacadio/benchmarks)
