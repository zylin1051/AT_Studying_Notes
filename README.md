![AT_logo](advance_tech_logo.png)



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

# Adhesive Tests

## How the Adhesive Tests Fit Together

| Main question | Relevant test(s) | What the test measures | Typical outputs | Practical interpretation | Important limitation |
| --- | --- | --- | --- | --- | --- |
| **What is the adhesive made of, and has its broad chemistry changed?** | **FTIR** | Infrared absorption by different chemical bonds, producing a chemical fingerprint of the adhesive. | Spectrum of absorbance or transmittance versus wavenumber in **cm⁻¹**; characteristic peak positions and shapes. | Similar peak positions and overall spectral shapes normally indicate the same broad polymer or chemical family. New, missing, or strongly changed peaks may indicate contamination, oxidation, degradation, or a formulation change. | FTIR normally does not give the exact percentage of each ingredient and does not directly measure strength, flow, or molecular weight. |
| **What is the polymer molecular-weight distribution?** | **GPC** | Distribution of molecular sizes in the soluble polymer portion of the adhesive. | **Mn**, **Mw**, **Mz**, dispersity **Đ = Mw/Mn**, and a molecular-weight distribution curve. | Lower molecular weight is often associated with easier flow but may reduce cohesive strength. A larger high-molecular-weight fraction can increase melt strength but reduce flow. | The material must be soluble in the selected solvent. Crosslinked or insoluble material may not be represented, and results can depend on calibration. |
| **At what temperatures does the adhesive melt, crystallize, or undergo other thermal transitions?** | **DSC at 5 K/min or 20 K/min** | Heat absorbed or released while the sample is heated or cooled at a controlled rate. | Melting temperature **Tm**, crystallization temperature **Tc**, glass-transition temperature **Tg**, peak area or enthalpy in **J/g**, and peak shape. | A slower rate such as **5 K/min** usually gives better separation and more time for structural reorganization. A faster rate such as **20 K/min** gives a quicker test and often a stronger signal, but may cause greater thermal lag. | DSC results should be compared using the same scan rate, thermal history, atmosphere, and sample preparation. Peak temperature is not automatically the maximum service temperature. |
| **How are the different crystalline populations distributed?** | **SSA** | Distribution of crystalline fractions according to their melting temperature and thermal stability. | For each fraction: melting-peak temperature in **°C**, relative melting-area fraction in **%**, and estimated lamellar thickness in **nm**. | A higher-temperature fraction generally represents thicker or more thermally stable lamellae. The percentage shows that peak's share of the total SSA crystalline melting area. | The percentage is not weight percentage and not necessarily total crystallinity. Lamellar thickness is estimated from a thermal model rather than measured directly. |
| **How easily does the molten adhesive flow at different processing temperatures?** | **MFR versus temperature** | Mass of molten material flowing through a standard die in ten minutes under a specified temperature and piston load. | **g/10 min**, reported together with the test temperature and load, for example: `2.3 g/10 min at 150°C and 2.16 kg`. | Higher MFR means easier flow and lower apparent melt viscosity under the same conditions. The MFR-temperature curve shows how sensitive processing flow is to temperature. | Values measured at different temperatures or loads are not directly equivalent. MFR is not a complete rheological or viscosity measurement. |
| **At what temperature does the adhesive begin to soften substantially?** | **Ring-and-Ball softening point** | Temperature at which the heated adhesive softens enough for a steel ball to move through a specified distance. | Softening temperature in **°C**. | A higher value indicates greater resistance to bulk softening and deformation during heating. | It is not a true melting point, bond-failure temperature, or maximum service temperature. |
| **How resistant is the thermoplastic to localized penetration during heating?** | **Vicat softening temperature** | Temperature at which a standard needle penetrates the specimen to a specified depth under a defined load and heating rate. | Vicat temperature in **°C**, together with the specified load and heating rate. | A higher Vicat temperature means the material resists localized penetration and softening to a higher temperature. | Vicat and Ring-and-Ball values are not interchangeable because their specimen geometry, loading, and deformation criteria differ. |
| **How stiff, elastic, viscous, or damping is the adhesive at different temperatures?** | **DMA** | Mechanical response to a small repeating deformation while temperature, frequency, or time is varied. | Storage modulus **E′**, loss modulus **E″**, damping factor **tan δ**, and transition temperatures. | **E′** describes elastic stiffness, **E″** describes energy dissipation, and **tan δ** shows the balance between viscous and elastic behavior. DMA can reveal the glass-transition or softening region and stiffness retention at service temperature. | Results depend strongly on deformation mode, frequency, strain level, heating rate, and specimen geometry. A DMA transition temperature may differ from a DSC transition temperature. |
| **How resistant is the adhesive to thermal oxidation?** | **Oxidative Induction Time at 200°C** | Time before detectable oxidation begins after the sample is exposed to oxygen at 200°C. | Oxidative induction time, normally in **minutes**. | A longer OIT generally indicates greater oxidative stability or more effective remaining antioxidant protection. | OIT is an accelerated comparative test. It does not directly equal the service lifetime of the adhesive. Results depend on test temperature, gas flow, sample mass, pan type, and onset calculation. |
| **How much water does the material absorb?** | **Water absorption** | Increase in specimen mass after immersion or conditioning in water for a specified time and temperature. | Water absorption in **% mass gain**, sometimes with dimensional or property changes. | Lower absorption generally means less risk of swelling, plasticization, dimensional change, or moisture-related property loss. | Water absorption is not the same as water permeability or wet adhesion. A material may absorb little water but still lose adhesion at an interface. |
| **How well does the adhesive resist long-term deformation under pressure?** | **Indentation at 1 MPa for at least 72 h** | Creep or permanent deformation while the material is held under a compressive pressure of 1 MPa for at least 72 hours. | Indentation depth in **mm**, remaining thickness, percentage deformation, or residual indentation after recovery. | Smaller indentation or greater retained thickness indicates better resistance to sustained compression, squeezing, or displacement. | Test temperature, indenter geometry, specimen thickness, recovery period, and reporting method are critical. Results from different conditions should not be compared directly. |
| **How strong, stiff, and stretchable is the material itself?** | **Tensile properties** | Stress-strain response while the specimen is pulled at a controlled rate. | Tensile strength in **MPa**, elongation at break in **%**, modulus in **MPa**, yield stress, and sometimes toughness. | Tensile strength indicates resistance to breaking, elongation indicates flexibility, and modulus indicates stiffness. The desired adhesive normally requires a balance of strength and flexibility. | Tensile testing measures the cohesive properties of the material, not adhesion to primer, steel, or backing. Results depend on specimen shape, thickness, temperature, and pulling speed. |

### Important comparison rules

- Compare **DSC** results only when scan rate and thermal history are the same.
- Compare **MFR** results only when both temperature and applied load are the same.
- Report **Vicat** results together with the load and heating-rate condition.
- Report **indentation** results together with the pressure, temperature, duration, and recovery condition.
- A higher numerical result is not always better; the preferred value depends on processing requirements and service conditions.

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

### Scan Rate
- The polymer can be heated at different rate, measured in Kelvin per minute (i.e. 20K / min).
- Typical heating-rate effects are:
  - Faster heating may shift a melting or reaction peak to a somewhat higher apparent temperature.
  - Faster cooling may shift crystallization to a lower temperature because more supercooling is required.
  - Slower heating may allow crystals to reorganize before melting, which can change the peak shape or area.

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
