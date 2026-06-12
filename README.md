# Substance Property Data

Computed property data for industrial process chemicals, as machine-readable JSON: concentration × temperature grids (density, dynamic viscosity, specific heat capacity) for aqueous solutions — with freezing-point tables for the freeze-protection fluids and °Brix for sucrose; saturation tables (pressure, liquid and vapour density) for refrigerants and pure fluids, including bubble/dew-point data for zeotropic blends; single-phase pressure × temperature grids (density, isobaric heat capacity, dynamic viscosity) for compressed industrial and utility gases, up to 700 bar for hydrogen; water/steam tables from the IAPWS-95 formulation — a full saturation table (0–370 °C, with enthalpy and latent heat) and a superheated-steam grid to 200 bar and 600 °C; and a humid-air psychrometric grid (humidity ratio, wet bulb, dew point, enthalpy) from the ASHRAE RP-1485 formulation.

Published and maintained by [ProcessConvert](https://www.processconvert.com), where each substance has an interactive property explorer:
https://www.processconvert.com/substances

## Aqueous solutions

| Substance | Formula | CAS | Concentration | Temperature | Properties | Model |
|---|---|---|---|---|---|---|
| Sulfuric acid | H₂SO₄ | 7664-93-9 | 5–75 wt% | 0–75 °C | ρ, μ, cp | Laliberté (2009) |
| Sodium hydroxide | NaOH | 1310-73-2 | 5–50 wt% | 20–100 °C | ρ, μ, cp | Laliberté (2009) |
| Hydrochloric acid | HCl | 7647-01-0 | 5–35 wt% | 0–60 °C | ρ, μ, cp | Laliberté (2009) |
| Nitric acid | HNO₃ | 7697-37-2 | 5–65 wt% | 0–45 °C | ρ, μ, cp | Laliberté (2009) |
| Phosphoric acid | H₃PO₄ | 7664-38-2 | 5–60 wt% | 0–60 °C | ρ, μ, cp | Laliberté (2009) |
| Ammonia | NH₃ | 7664-41-7 | 5–30 wt% | 0–50 °C | ρ, μ, cp | Laliberté (2009) |
| Potassium hydroxide | KOH | 1310-58-3 | 5–50 wt% | 15–40 °C | ρ, μ | Laliberté (2009) |
| Acetic acid | CH₃COOH | 64-19-7 | 5–80 wt% | 15–55 °C | ρ, μ | Laliberté (2009) |
| Formic acid | HCOOH | 64-18-6 | 5–60 wt% | 15–55 °C | ρ, μ | Laliberté (2009) |
| Ethylene glycol | C₂H₆O₂ | 107-21-1 | 10–60 wt% | 0–100 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Propylene glycol | C₃H₈O₂ | 57-55-6 | 10–60 wt% | 0–100 °C | ρ, μ, cp | Melinder (2010) via CoolProp |
| Methanol | CH₃OH | 67-56-1 | 10–50 wt% | −45–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Ethanol | C₂H₅OH | 64-17-5 | 10–50 wt% | −35–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Glycerol | C₃H₈O₃ | 56-81-5 | 10–60 wt% | −30–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Potassium carbonate | K₂CO₃ | 584-08-7 | 5–35 wt% | −25–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Lithium chloride | LiCl | 7447-41-8 | 5–20 wt% | −40–40 °C | ρ, μ, cp, T_f | Melinder (2010) via CoolProp |
| Magnesium chloride | MgCl₂ | 7786-30-3 | 5–20 wt% | −25–40 °C | ρ, cp, T_f | Melinder (2010) via CoolProp |
| Sodium acetate | CH₃COONa | 127-09-3 | 5–30 wt% | 0–60 °C | ρ, μ, cp | Laliberté (2009) |
| Sucrose | C₁₂H₂₂O₁₁ | 57-50-1 | 5–50 wt% | 15–55 °C | ρ, μ, °Bx | Laliberté (2009) |
| Hydrogen peroxide | H₂O₂ | 7722-84-1 | 5–50 wt% | 0–40 °C | ρ | Laliberté (2009) |
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
| Potassium chloride | KCl | 7447-40-7 | 2–20 wt% | 5–80 °C | ρ, μ, cp | Laliberté (2009) |
| Sodium sulfate | Na₂SO₄ | 7757-82-6 | 2–14 wt% | 20–60 °C | ρ, μ | Laliberté (2009) |
| Aluminium sulfate | Al₂(SO₄)₃ | 10043-01-3 | 2–24 wt% | 15–60 °C | ρ | Laliberté (2009) |
| Ammonium chloride | NH₄Cl | 12125-02-9 | 2–24 wt% | 15–60 °C | ρ, μ | Laliberté (2009) |
| Zinc chloride | ZnCl₂ | 7646-85-7 | 5–50 wt% | 15–70 °C | ρ | Laliberté (2009) |
| Sodium nitrate | NaNO₃ | 7631-99-4 | 2–40 wt% | 10–60 °C | ρ, μ, cp | Laliberté (2009) |
| Potassium nitrate | KNO₃ | 7757-79-1 | 2–18 wt% | 15–60 °C | ρ, μ, cp | Laliberté (2009) |
| Ammonium nitrate | NH₄NO₃ | 6484-52-2 | see file | see file | ρ, μ | Laliberté (2009) |
| Calcium nitrate | Ca(NO₃)₂ | 10124-37-5 | see file | see file | ρ, μ | Laliberté (2009) |
| Sodium bicarbonate | NaHCO₃ | 144-55-8 | 1–8 wt% | 10–50 °C | ρ | Laliberté (2009) |
| Manganese sulfate | MnSO₄ | 7785-87-7 | see file | 20–25 °C | ρ, μ | Laliberté (2009) |
| Barium chloride | BaCl₂ | 10361-37-2 | see file | see file | ρ, μ | Laliberté (2009) |

T_f = freezing-point table (concentration → freezing temperature) included in the file. °Bx = degrees Brix derived display (sucrose). "See file" = the JSON file's declared ranges are the authority.

## Refrigerants & pure fluids

Saturation tables on a single temperature axis. Single-component fluids carry one saturation pressure column; **zeotropic blends carry separate bubble-point and dew-point pressure columns** with the computed temperature glide stated — a distinction most published PT charts silently omit. Each file states the fluid's critical point; tables stop short of it. Designation facts (GWP with stated basis per the U.S. EPA Technology Transitions reference table, ANSI/ASHRAE Standard 34 safety classification) are included as cited values.

| Fluid | Composition / name | CAS | Temperature | Pressure columns | Glide (1 atm) |
|---|---|---|---|---|---|
| R-134a | 1,1,1,2-tetrafluoroethane | 811-97-2 | −40–60 °C | P_sat | — |
| R-290 | Propane | 74-98-6 | −40–60 °C | P_sat | — |
| R-32 | Difluoromethane | 75-10-5 | −40–60 °C | P_sat | — |
| R-744 | Carbon dioxide | 124-38-9 | −40–25 °C (critical 30.98 °C — see file note) | P_sat | — |
| R-717 | Ammonia (anhydrous) | 7664-41-7 | −40–60 °C | P_sat | — |
| R-600a | Isobutane | 75-28-5 | −40–60 °C | P_sat | — |
| R-410A | R-32/125 (50/50) blend | blend | −40–60 °C | P_bubble, P_dew | 0.08 K |
| R-404A | R-125/143a/134a blend | blend | −40–60 °C | P_bubble, P_dew | 0.75 K |
| R-407C | R-32/125/134a blend | blend | −40–60 °C | P_bubble, P_dew | 7.0 K |

All files also carry saturated liquid and vapour density columns (bubble-point liquid / dew-point vapour for blends).

## Compressed & utility gases

Single-phase properties on a pressure (bar absolute) × temperature (°C) grid: density (kg/m³), isobaric heat capacity (J/kg·K) and dynamic viscosity (µPa·s), computed from each fluid's reference Helmholtz-energy equation of state. Every tabulated state is single-phase; any grid cell that would fall at or inside the two-phase region is `null` (for the fluids below, the whole window is supercritical, so no cell is null). Each file carries a cited identity block (molar mass, critical point, normal boiling point).

| Gas | Formula | CAS | Pressure | Temperature | Properties | Reference EoS |
|---|---|---|---|---|---|---|
| Nitrogen | N₂ | 7727-37-9 | 1–500 bar | −20–100 °C | ρ, cp, μ | Span et al. (2000) |
| Oxygen | O₂ | 7782-44-7 | 1–200 bar | −20–100 °C | ρ, cp, μ | Schmidt & Wagner (1985) |
| Hydrogen | H₂ | 1333-74-0 | 1–700 bar (incl. 350/700 bar storage pressures) | −20–100 °C | ρ, cp, μ | Leachman et al. (2009) |
| Methane | CH₄ | 74-82-8 | 1–200 bar | −20–100 °C | ρ, cp, μ | Setzmann & Wagner (1991) |
| Argon | Ar | 7440-37-1 | 1–300 bar | −20–100 °C | ρ, cp, μ | Tegeler, Span & Wagner (1999) |
| Helium | He | 7440-59-7 | 1–300 bar | −20–100 °C | ρ, cp, μ | Ortiz-Vega et al. (2019) |

Air (as a pseudo-pure mixture) is planned; it is held pending an approved citable validation source and will be added under the same format.

## Water & steam

One file (`data/water-steam.json`) from the **IAPWS-95** reference formulation (Wagner & Pruß 2002, via CoolProp), checked against IAPWS-IF97 published verification values and NIST WebBook:

- **Saturation table** — 0–370 °C (5° steps to 100 °C, 10° steps above; the critical point, 373.946 °C / 22,064 kPa, is stated and the table stops short of it). Columns: saturation pressure (kPa), saturated liquid and vapour density (kg/m³), liquid and vapour enthalpy and the latent heat of vaporisation h_fg (kJ/kg), liquid and vapour entropy (kJ/kg·K).
- **Superheated grid** — 1–200 bar (absolute) × 100–600 °C: density, enthalpy and entropy. Any grid cell at or below the saturation temperature for that pressure is `null` (the state there is saturated or liquid water, not superheated steam).
- **Reference-state note:** enthalpy and entropy follow the IAPWS convention — internal energy and entropy are zero for saturated liquid at the triple point (0.01 °C). Values from tables built on a different datum are not directly comparable.

## Humid air (psychrometrics)

One file (`data/humid-air.json`) from the **ASHRAE RP-1485** real-moist-air formulation (Herrmann, Kretzschmar & Gatley 2009, via CoolProp `HAPropsSI`):

- **Grid:** dry-bulb 0–50 °C (5° steps) × relative humidity 10–100 % (10 % steps), at sea-level pressure (101.325 kPa). Columns: humidity ratio W (g water vapour / kg dry air), thermodynamic wet-bulb temperature (°C), dew-point temperature (°C), and moist-air specific enthalpy (kJ / kg dry air).
- **Reference-state note:** enthalpy is per kilogram of dry air on the ASHRAE convention — the enthalpy of dry air and of liquid water are both zero at 0 °C.
- Sub-zero dew points at the cold–dry corner are over-water values (indicative); the ice line is not included in this version.

Each file declares its own valid ranges; values are tabulated only inside the published validity region of the underlying model, bounded below saturation for the aqueous salts, below the critical point for the saturation tables, and single-phase for the gas grids. No extrapolation. Honest-omission conventions: where a property column is absent from a table above, the model provides no usable coefficients for that property over the tabulated range — the value is omitted rather than approximated; for the sub-zero heat-transfer fluids, grid cells below the solution's freezing line at that concentration are `null`.

## How the values are produced

No value in this repository is hand-authored. Grids are computed by a deterministic offline pipeline from established published models:

- **Laliberté, M. (2009).** "A Model for Calculating the Heat Capacity of Aqueous Solutions, with Updated Density and Viscosity Data." *Journal of Chemical & Engineering Data*, 54(6), 1725–1760 — via the `thermo`/`chemicals` Python libraries.
- **Melinder, Å. (2010).** *Properties of Secondary Working Fluids for Indirect Systems*, IIR — via CoolProp incompressible solutions.
- **CoolProp reference Helmholtz-energy equations of state, mixture models and transport-property correlations** (Bell et al., 2014, *Ind. Eng. Chem. Res.* 53(6)) for the pure fluids, refrigerant blends and compressed gases — saturation and compressed-state points checked against NIST WebBook (SRD 69) published values for single-component fluids, and named manufacturer engineering tables (REFPROP-derived) for blends.

Every file carries `validation` entries: independently cited reference points (property, state point, expected value, tolerance, source citation — CRC Handbook 97th ed., Perry's, ICT, NBS Circular 440, NIST WebBook, named manufacturer saturation tables) that the generated data is checked against before publication. A value that fails that check is not published. Full methodology: https://www.processconvert.com/methodology

## File formats

**Aqueous solutions** — one JSON per substance:

```text
name, formula, cas, aliases      identification
axes                             concentrations (wt%), temperatures (°C)
grid                             rho / mu / cp arrays, rows = concentration, cols = temperature
                                 (mu/cp absent where the model has no coefficients;
                                  cells are null below the freezing line)
freeze_points                    concentration -> freezing point (°C), where present
concentration_range,
temperature_range                declared validity window
model, sources, validation,
validity_note, generated         provenance and checks
```

**Pure fluids (saturation)** — one JSON per fluid:

```text
name, formula, cas, designation  identification (refrigerant designation)
axes.temp_C                      single temperature axis (°C)
sat                              single-component: p_sat_kPa / rho_liq / rho_vap
                                 blends: p_bubble_kPa / p_dew_kPa / rho_liq / rho_vap
blend                            blends only: components, composition, computed glide (K)
critical                         critical temperature (°C) and pressure (kPa)
gwp, ashrae34                    cited designation facts (value, basis, citation)
model, sources, validation,
validity_note, generated         provenance and checks
```

**Compressed gases** — one JSON per gas:

```text
name, formula, cas               identification
axes                             pressure_bar (absolute), temp_C
grid                             rho / cp / mu arrays, rows = pressure, cols = temperature
                                 (mu in µPa·s; any two-phase/liquid state is null)
identity                         molar mass, critical T and P, normal boiling point (cited)
boundary_note                    single-phase rule as applied to this fluid
model, sources, validation,
validity_note, generated         provenance and checks
```

**Water & steam** — one JSON (`water-steam.json`):

```text
name, formula, cas               identification
saturation.temp_C                saturation temperature axis (°C)
saturation                       p_sat_kPa / rho_liq / rho_vap / h_f / h_g / h_fg / s_f / s_g
superheated.axes                 pressure_bar (absolute) × temp_C
superheated.grid                 rho / h / s arrays (cells at or below saturation are null)
datum                            IAPWS reference-state provenance (u = s = 0, sat. liquid, triple point)
critical                         critical temperature (°C) and pressure (kPa)
model, sources, validation,
validity_note, generated         provenance and checks
```

**Humid air** — one JSON (`humid-air.json`):

```text
name                             identification (moist air)
axes                             temp_db_C (dry bulb), rh_percent; pressure fixed at 101.325 kPa
grid                             W (g/kg dry air) / t_wb / t_dp / h (kJ/kg dry air) arrays
datum                            ASHRAE reference state (dry air and liquid water enthalpy zero at 0 °C)
model, sources, validation,
validity_note, generated         provenance and checks
```

### Example (Python)

```python
import json

with open("data/hydrogen.json") as f:
    s = json.load(f)

p = s["axes"]["pressure_bar"].index(700)
t = s["axes"]["temp_C"].index(25)

# Hydrogen density at 700 bar, 25 °C (kg/m³)
print(s["grid"]["rho"][p][t])
```

Interpolation between points is appropriate inside the declared ranges (bilinear for the concentration and pressure grids, linear along the saturation line for pure fluids); do not interpolate across `null` cells and do not extrapolate beyond the declared ranges or toward the critical point.

## Intended use and limitations

This data is published as an engineering reference for preliminary calculations, teaching and software development. It is not a substitute for project-specific data, vendor data sheets, or the judgement of a qualified engineer, and it carries no warranty. Always confirm safety-critical values against primary sources.

## License and attribution

Data is licensed **CC BY 4.0**. You may use, redistribute and adapt it, including commercially, provided you attribute:

> Substance property data from ProcessConvert (https://www.processconvert.com), computed from Laliberté (2009), Melinder (2010) and CoolProp reference equations of state, CC BY 4.0.

When citing the underlying science, cite the original papers above.

## Errors

If a value looks wrong, please open an issue or email hello@processconvert.com — concrete reports ("file X, 30 wt% at 25 °C shows Y, expected Z because…") are especially helpful.
