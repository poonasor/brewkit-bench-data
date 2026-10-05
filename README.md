# Espresso Machine Bench Data

Original measured maintenance and workflow data for home super-automatic espresso machines, from the [Brewkit](https://brewkit.net/) gear bench. Every number below was logged on our own counter, on our own water and beans — one honest bench data point, not lab data.

- **Website:** https://brewkit.net/
- **Last updated:** 2026-10-05
- **License:** CC BY 4.0 (data); analysis and prose remain © Brewkit

## What is in this repository?

Two CSV datasets from published Brewkit bench studies, plus the method notes needed to read them. The CSVs are machine-readable; each study section below gives the answer-first summary so you can quote it without opening a file.

### Study 1 — Super-automatic maintenance rotation (2 months, 4 machines)

**Data:** [`data/super-automatic-maintenance-rotation-2026.csv`](data/super-automatic-maintenance-rotation-2026.csv) · **Last updated:** 2026-10-05 · **Canonical article:** [Best Super-Automatic Espresso Machine in 2026](https://brewkit.net/best-super-automatic-espresso-machine/)

Four machines — De'Longhi Magnifica Evo, De'Longhi Magnifica S, Philips 3200 LatteGo, Philips 2300 LatteGo — rotated through the Brewkit bench over two months on the same medium-roast blend. We timed first-cup-to-second-cup cycles, counted daily cleanup steps, and logged grinder response to a one-setting change.

**The headline numbers:**

| Observation (2-month rotation) | Magnifica Evo | Philips 3200 | Philips 2300 |
|---|---|---|---|
| Milk-path rinse + reassemble, daily avg | 25 s (carafe auto-clean first) | **14 s** | 14 s |
| Re-dial-ins needed after week one | 0 | **0** | 1 (one drift, fixed once) |
| Grinder noise, same counter | Loudest of the three | **Quietest** | Quietest |
| Finished cappuccino, button to cup | **Fastest** | Middle | Middle |
| Brew group serviceability | Removable, tap rinse | Not user-removable | Not user-removable |

The quotable finding: in 2026 the super-automatic category's real dividing line is not coffee quality — every machine here makes a credible cappuccino — it is which milk system you are still willing to clean in month six.

**Method:** 2-month rotation, one medium-roast blend, same counter/water/beans across all machines. Readings from our counter, our water, our beans; treat as one honest data point, not lab data. Bench observations are our own; manufacturer specs (grind settings, descale intervals, capacities) are cited to official listings and manuals in the canonical article.

### Study 2 — Philips 3200 vs 2300 LatteGo side-by-side (2026)

**Data:** [`data/philips-3200-vs-2300-bench-2026.csv`](data/philips-3200-vs-2300-bench-2026.csv) · **Last updated:** 2026-10-05 · **Canonical article:** [Philips 3200 vs 2300 LatteGo (2026)](https://brewkit.net/philips-3200-vs-2300/)

**Data:** the Philips 3200 and 2300 LatteGo share the same 100% ceramic grinder, the same two-part no-tube LatteGo milk system, and the same AquaClean maintenance — the 3200's higher price buys a fuller one-touch drink menu (5 varieties incl. latte macchiato and americano) and a touch display, nothing in the cup. Both bench-rinsed identically at 14 s daily average.

The shot character on both: a café-style, crema-layered shot that leans smooth and mild rather than punchy — the bean-to-cup character of the whole Philips Series 2x00/3x00 platform. Neither machine exposes extraction control (no PID-style temperature setting, no pressure profiling; fixed pre-brew aroma step only).

**Method:** two months of side-by-side use; every spec row is labeled in the CSV with its evidence type — manufacturer spec, manufacturer claim, or bench observation — so you can separate quoted specs from measured behavior.

## How was this data collected? (Method)

Each study ran on the Brewkit bench (same beans, same counter, one variable at a time where applicable) with numbers logged during the rotation or side-by-side period named in the study header. Readings are from our own machines and kitchen — one honest, reproducible data point per study, not laboratory measurement. Manufacturer specifications are quoted from official product pages and manuals (retrieved September 2026) and labeled as such.

## Can I use this data?

Yes — the CSV data is released under [CC BY 4.0](LICENSE). Attribute "Brewkit (brewkit.net)" and link the canonical article named in each study. The analysis, verdicts, and prose on brewkit.net remain copyright Brewkit; the CSV numbers are free to reuse with attribution.

## Who maintains this repository?

[Brewkit](https://brewkit.net/) — an independent espresso-gear publication that measures the gear it writes about. Bench studies land on the site first; this repository republishes the underlying numbers for anyone who wants machine-readable data. Study requests: hello@brewkit.net.
