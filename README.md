# Riccardo Tinivella

Most engineering tools give you an answer. I build the ones that show you the price of each choice.

A design is a walk through a graph of choices. 10 % or 100 % ripple on a 20 A buck: 13.71 µH or 1.371 µH. You pay in inductance, or you pay ten times the capacitor current. Neither is wrong. Each path ends at a different converter. The repositories below do one of three jobs: put a price on one step, keep the path on record, or teach the walk.

How I think about it: **[Thinking in power electronics](https://tinix84.github.io/blog/thinking-in-power-electronics/)**

[Website](https://tinix84.github.io/) · [Course](https://tinix84.github.io/power-electronics/) · [Newsletter](https://riccardotinivella.substack.com/) · [LinkedIn](https://www.linkedin.com/in/riccardotinivella/) · [ResearchGate](https://www.researchgate.net/profile/Riccardo-Tinivella) · [tinix84@gmail.com](mailto:tinix84@gmail.com)

The tables below show 15 repositories. All 40+ projects, each with its context and outcome: [tinix84.github.io/projects](https://tinix84.github.io/projects/).

## Now

- Technical business development for 400/800 V power conversion: AI data centres, battery storage, industrial power.
- Guest lecturer in power electronics at HTWG Konstanz.
- Quant at MenthorQ. Control-loop stability and options gamma are the same argument. I checked.

I never studied power electronics. I learned it by owning products from schematic to UL certificate.

## Put a price on one step

A choice is cheap when its price costs one script run, not one week at the bench.

| Repository | The price it shows |
|---|---|
| [pyplecs](https://github.com/tinix84/pyplecs) | Turns one-off PLECS runs into reusable sweeps and batch workflows |
| [pycircuitsim](https://github.com/tinix84/pycircuitsim) | PLECS and GeckoCIRCUITS behind one Python interface |
| [py_magnetic_fem](https://github.com/tinix84/py_magnetic_fem) | Parametric magnetic geometry driven into a finite-element solver |
| [inductor_optimizer](https://github.com/tinix84/inductor_optimizer) | Multi-objective inductor design, each candidate evaluated by FEM |
| [doublepulse_tester](https://github.com/tinix84/doublepulse_tester) | Double-pulse simulation that produces switching-loss maps |
| [choke_ac_model_fitting](https://github.com/tinix84/choke_ac_model_fitting) | Measured choke impedance fitted to a SPICE model |
| [mutual_transformer](https://github.com/tinix84/mutual_transformer) | AC winding loss from a mutual-impedance transformer model |
| [thermalkli](https://github.com/tinix84/thermalkli) | Heatsink and semiconductor thermal analysis from the command line |
| [interleaved_boost](https://github.com/tinix84/interleaved_boost) | C2000 firmware for a 3-phase interleaved boost with CLA current control |

## Keep the path on record

A decision nobody can review is a guess with a date on it.

| Repository | What it records |
|---|---|
| [frameshift](https://github.com/tinix84/frameshift) | Frame the problem before optimizing a solution. Specification-first, pre-alpha |
| [plecs-expert-skill](https://github.com/tinix84/plecs-expert-skill) | Agent skills that read, lay out and test PLECS models |
| [glassgraph](https://github.com/tinix84/glassgraph) | A deterministic, byte-reproducible entity linker for research wikis |

## Teach the walk

| Repository | What students get |
|---|---|
| [power-electronics](https://github.com/tinix84/power-electronics) | The HTWG course: every decision with its price, every dead end marked No! |
| [awesome-power-eval-kits](https://github.com/tinix84/awesome-power-eval-kits) | Learn power electronics by reverse engineering evaluation kits |
| [LinkedinPublic](https://github.com/tinix84/LinkedinPublic) | The notebooks behind my posts: EMC, magnetics, impedance fitting |

---

It is not poetic, it is not romantic, but simplicity pays. `#ThinkingInPowerElectronics`
