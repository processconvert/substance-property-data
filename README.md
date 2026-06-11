# Aqueous Substance Property Data

Computed density, dynamic viscosity and specific heat capacity grids for common industrial process chemicals and heat-transfer fluids in aqueous solution, as concentration × temperature tables in machine-readable JSON — with freezing-point tables for the freeze-protection fluids.

Published and maintained by [ProcessConvert](https://www.processconvert.com), where each substance has an interactive property explorer:
https://www.processconvert.com/substances

## Substances

| Substance | Formula | CAS | Concentration | Temperature | Properties | Model |
|---|---|---|---|---|---|---|
| Sulfuric acid | H₂SO₄ | 7664-93-9 | 5–75 wt% | 0–75 °C | ρ, μ, cp | Laliberté (2009) |
| Sodium hydroxide | NaOH | 1310-73-2 | 5–50 wt% | 20–100 °C | ρ, μ, cp | Laliberté (2009) |
| Hydrochloric acid | HCl | 7647-01-0 | 5–35 wt% | 0–60 °C | ρ, μ, cp | Laliberté (2009) |
| Nitric acid | HNO₃ | 7697-37-2 | 5–65 wt% | 0–45 °C | ρ, μ, cp | Laliberté (2009) |
| Phosphoric acid | H₃PO₄ | 7664-38-2 | 5–60 wt% | 0–60 °C | ρ, μ, cp | Laliberté (2009) |
| Ammonia | NH₃ | 7664-41-7 | 5–30 wt% | 0–50 °C | ρ, μ, cp | Laliberté (2009) |
| Ethylene glycol | C₂H₆O₂ | 107-21-1 | 10–60 wt% | 0–100 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Propylene glycol | C₃H₈O₂ | 57-55-6 | 10–60 wt% | 0–100 °C | ρ, μ, cp | Melinder (2010) via CoolProp |
| Copper(II) sulfate | CuSO₄ | 7758-98-7 | 2–12 wt% | 15–60 °C | ρ, μ, cp | Laliberté (2009) |
| Zinc sulfate | ZnSO₄ | 7733-02-0 | 2–30 wt% | 15–55 °C | ρ, μ | Laliberté (2009) |
| Nickel sulfate | NiSO₄ | 7786-81-4 | 2–22 wt% | 15–60 °C | ρ, μ, cp | Laliberté (2009) |
| Iron(II) sulfate | FeSO₄ | 7720-78-7 | 2–16 wt% | 15–25 °C | ρ, μ, cp | Laliberté (2009) |
| Iron(III) chloride | FeCl₃ | 7705-08-0 | 2–40 wt% | 0–35 °C | ρ, μ | Laliberté (2009) |
| Sodium chloride | NaCl | 7647-14-5 | 2–24 wt% | 0–80 °C | ρ, μ, cp | Laliberté (2009) |
| Calcium chloride | CaCl₂ | 10043-52-4 | 2–34 wt% | 0–80 °C | ρ, μ, cp | Laliberté (2009) |
| Magnesium sulfate | MgSO₄ | 7487-88-9 | 2–20 wt% | 15–60 °C | ρ, μ, cp | Laliberté (2009) |
| Sodium carbonate | Na₂CO₃ | 497-19-8 | 2–14 wt% | 20–40 °C | ρ, μ, cp | Laliberté (2009) |
| Ammonium sulfate | (NH₄)₂SO₄ | 7783-20-2 | 2–40 wt% | 15–55 °C | ρ, μ | Laliberté (2009) |
| Methanol | CH₃OH | 67-56-1 | 10–50 wt% | −45–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Ethanol | C₂H₅OH | 64-17-5 | 10–50 wt% | −35–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Glycerol | C₃H₈O₃ | 56-81-5 | 10–60 wt% | −30–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Potassium carbonate | K₂CO₃ | 584-08-7 | 5–35 wt% | −25–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Lithium chloride | LiCl | 7447-41-8 | 5–20 wt% | −40–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Magnesium chloride | MgCl₂ | 7786-30-3 | 5–20 wt% | −25–40 °C | ρ, cp, T_f | Melinder (2010) via CoolProp |
| Sodium acetate | CH₃COONa | 127-09-3 | 5–30 wt% | 0–60 °C | ρ, μ, cp | Laliberté (2009) |

T_f = freezing-point table (concentration → freezing temperature) included in the file.

Each file declares its own valid concentration and temperature ranges; values are tabulated only inside the published validity region of the underlying model, bounded below saturation for the salts. No extrapolation. Two honest-omission conventions apply: where a property column is absent (ZnSO₄, FeCl₃ and (NH₄)₂SO₄ ship without cp; MgCl₂ ships without μ), the model provides no usable coefficients for that property — the value is omitted rather than approximated. And for the sub-zero heat-transfer fluids, grid cells below the solution's freezing line at that concentration are `null` — the solution would be frozen, so no liquid property exists to report.

## Properties

Per substance, on a regular concentration (wt%) × temperature (°C) grid:

- Density (kg/m³)
- Dynamic viscosity (mPa·s) where the model supports it
- Specific heat capacity (J/(kg·K)) where the model supports it
- Freezing point (°C) per concentration, for the Melinder-path fluids where independently validated
- Derived where applicable: specific gravity, °Baumé

## How the values are produced

No value in this repository is hand-authored. Grids are computed by a deterministic offline pipeline from established published models:

- **Laliberté, M. (2009).** "A Model for Calculating the Heat Capacity of Aqueous Solutions, with Updated Density and Viscosity Data." *Journal of Chemical & Engineering Data*, 54(6), 1725–1760 — via the `thermo`/`chemicals` Python libraries.
- **Melinder, Å. (2010).** *Properties of Secondary Working Fluids for Indirect Systems*, IIR — via CoolProp incompressible solutions.

Every file carries `validation` entries: independently cited reference points (property, concentration, temperature, expected value, tolerance, source citation — CRC Handbook 97th ed. concentrative-properties tables, Perry's, ICT) that the generated grid is checked against before publication. A grid that fails its validation points is not published. Full methodology: https://www.processconvert.com/methodology

## File format

One JSON file per substance. Key fields:

```text
name, formula, cas, aliases      identification
axes                             grid axes: concentrations (wt%), temperatures (°C)
grid                             rho / mu / cp arrays, rows = concentration, cols = temperature
                                 (mu/cp absent where the model has no coefficients;
                                  cells are null below the freezing line)
freeze_points                    concentration -> freezing point (°C), where present,
                                 with its own cited validation
concentration_range,
temperature_range                declared validity window
model, model_family, sources     provenance
validation                       cited check points the grid was verified against
validity_note                    plain-language scope and limitations
generated                        generation date
```

### Example (Python)

```python
import json

with open("data/methanol.json") as f:
    s = json.load(f)

conc = s["axes"]["concentrations"]   # wt%
temp = s["axes"]["temperatures"]     # °C
rho  = s["grid"]["rho"]              # kg/m3, [i_conc][j_temp]; None below freeze line

# density of 30 wt% methanol at -10 °C
i, j = conc.index(30), temp.index(-10)
print(rho[i][j])

# freezing point of 40 wt% methanol
fp = {p["conc"]: p["freeze_C"] for p in s["freeze_points"]["points"]}
print(fp[40])
```

Bilinear interpolation between grid points is appropriate inside the declared ranges; do not interpolate across `null` cells and do not extrapolate beyond the declared ranges.

## Intended use and limitations

This data is published as an engineering reference for preliminary calculations, teaching and software development. It is not a substitute for project-specific data, vendor data sheets, or the judgement of a qualified engineer, and it carries no warranty. Always confirm safety-critical values against primary sources.

## License and attribution

Data is licensed **CC BY 4.0**. You may use, redistribute and adapt it, including commercially, provided you attribute:

> Substance property data from ProcessConvert (https://www.processconvert.com), computed from Laliberté (2009) and Melinder (2010), CC BY 4.0.

When citing the underlying science, cite the original papers above.

## Errors

If a value looks wrong, please open an issue or email hello@processconvert.com — concrete reports ("file X, 30 wt% at 25 °C shows Y, expected Z because…") are especially helpful.
