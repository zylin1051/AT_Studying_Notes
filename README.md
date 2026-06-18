![AT_logo](advance_tech_logo.png)

**Last Updated: June 2, 2026**

## IMPORTANT 

This platform should be used as a refenrence only. **ALWAYS** refer the original sources or documents, where applicable, for details and clarity.

---

# Specification/Standard Systems

## Pipeline Transportation Systems

### International Organization for Standardization (ISO)

- [ISO 13623-2017 (The Design of Pipeline System for the Transportation of Fluids)](ISO_13623-2017.md)

  - [ISO 15589-1-2015 (On-land Pipelines)](ISO_15589-1-2015.md)
  - [ISO 15589-2-2024 (Offshore Pipelines)](ISO_15589-2-2024.md)
  - [ISO 21809-3-2016 (Field Joint Coatings)](ISO_21809-3-2016.md)

---

# General Notes

## Common CP Anode Category [Table](anode_comparison.md)

## Fourier-Transform Infrared Spectroscopy (FTIR)
Used for identifying the **chemical backbone (main composition)**
- Molecules absorb infrared light at specific frequencies when that light matches the vibration of their chemical bonds。
- In an FTIR test, the instrument sends infrared light through or onto the sample. The sample absorbs certain infrared frequencies. The instrument then converts the signal into a spectrum using a mathematical process called a Fourier transform.
- TIR tells us what chemical bonds are present by looking at *where the material absorbs infrared light* （i.e. the peaks on the graph).

## Differential Scanning Calorimetry (DSC)
Used for identifying the **thermal properties (the behaviour when heated)**
- DSC graphs describe the thermal behavior or thermal properties of the adhesive materials (how the material behaves when heated).
- Area (under the curve above the baseline) tells you how much heat is needed to melt that part of the material.
- A larger area generally means:
  - more crystalline material, or
  - more heat required to melt that melting phase.
- A smaller area generally means:
  - less crystalline material, or
  - a smaller melting contribution.
- The DSC “area” is the integrated peak area relative to the baseline, and it represents the melting enthalpy in J/g.

## Melt Flow Rate (MFR)
Measures how easily a **molten polymer** flows under *a specified temperature and load*.
- Unit: g/10 min
- A polymer sample is heated until molten. Then a standard weight pushes the molten polymer through a small opening. The lab measures how much material flows out in 10 minutes.

## Ring-and-Ball Softening Point (R&B Softening Point)
A small adhesive sample is placed in a metal ring with a steel ball above it and heated at a controlled rate. The reported temperature is reached **when the adhesive softens enough for the ball to move downward by a defined distance**.
- Higher value: remains firm to a higher temperature.
- Lower value: begins to soften sooner and may flow more easily at lower temperature.
- **Indicates the adhesive’s resistance to heat-induced softening**

## Successive Self-Nucleation and Annealing (SSA)
Measures the distribution of different crystalline structures inside a semicrystalline adhesive.
An adhesive does not normally contain one uniform type of crystal. It contains many crystal populations:
- thin, less stable crystals that melt at lower temperatures;
- thicker, more ordered crystals that melt at higher temperatures;
- intermediate crystals between them.
SSA uses repeated heating, partial melting, cooling, and annealing steps to separate the different crystal populations into clearer fractions.
- sorting the crystals according to how much heat is needed to melt them.
  
### How to read one line of SSA (there are usually more than one line, each corresponding to one specific crystal population)

| Measure | Unit | How to read it |
| --- | --- | --- |
| **Melting-peak temperature** | °C | The temperature around which that particular crystalline population melts. It represents a peak covering a temperature range, not melting at one exact temperature only. |
| **Relative melting-area fraction** | % | The area of that melting peak divided by the total area of all SSA melting peaks. It shows how much that crystal population contributes to the total crystalline melting signal. It is **not weight percentage**. |
| **Estimated lamellar thickness** | nm | The estimated average thickness of the crystal lamellae associated with that melting peak. It is calculated from the melting temperature rather than measured directly. Higher-temperature peaks generally correspond to thicker, more thermally stable lamellae. |

### Example

**111.4°C, 31.56%, 6.2 nm** means:

> A crystalline population with an estimated lamellar thickness of **6.2 nm** melts mainly around **111.4°C** and contributes **31.56% of the total SSA crystalline melting area**.

For example:

- 111.4°C, 31.56%, 6.2 nm

This means:

- 111.4°C: melting temperature of that crystalline fraction;
- 31.56%: that fraction contributes about 31.56% of the total measured melting-area distribution;
- 6.2 nm: estimated thickness of the crystal lamellae.

Note: the lamellar thickness is normally calculated from melting temperature using a thermal model. It is not measured directly with a microscope.
