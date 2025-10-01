# Lecture 2: Introduction to Biopharmaceutics

## I. Core Definition: Biopharmaceutics

*   **Biopharmaceutics**:  Study of how the **physicochemical properties**(物理化学性质) of a drug substance and its **dosage form** (e.g., tablet, capsule, suspension, injection) influence the **rate** and **extent** of drug absorption into the systemic circulation.
*   **Central Conceptual Pathway**: Drug Product → Administration → Liberation → Absorption → Systemic Circulation → Pharmacologic Effect.
*   **Significance**: Explains why two products containing the same active pharmaceutical ingredient (药物活性成分) can exhibit different clinical performances (e.g., onset of action, peak effect) due to differences in formulation or physical properties. For example, a paracetamol **suspension**(混悬液) acts **faster than a tablet** because the drug is pre-dispersed, leading to quicker dissolution and absorption.
    *  设计合理的给药方案，以更好的方式开发治疗效果；描述在不同的身体部位达到的药物水平和相应的药理作用之间的直接关系；预测药品的体内性能（in vivo performance）

## II. ADME/LADME Framework

*   **ADME**: The four core processes of **Pharmacokinetics (PK)** (药代动力学), which describes "what the body does to the drug."（the change in drug concentration as it passes through the body）
    *   **A - Absorption**: drug is administered and entry into systemic circulation (central compartment: blood/plasma).
        *    Drug's  biopharmaceutics properties (剂型、溶解度、渗透性) decided how fast and how much it enters.
        *    药物可以从Central Compartment移动到Peripheral Compartment (外周隔室: tissue/organs where the drug distributes) 或elimination（metabolism [liver], excretion [kidney]）, 药物在中央隔室和外周隔室之间来回移动。
    *   **D - Distribution**: Movement from blood to tissues.
    *   **M - Metabolism**: Chemical alteration (biotransformation).
    *   **E - Excretion**: Removal from the body.    
    ![Time curve]  https://github.com/HZzzzz411/Pharmacokinetics-and-Pharmacodynamics-Notes/raw/picture/image3.png)
*   **LADME**: An expanded model that includes **Liberation** (release of the drug from its dosage form) as the critical first step for non-intravenous dosage forms, which is the primary focus of biopharmaceutics.

## III. Key Determinants of Oral Absorption: Solubility & Permeability

For a drug to be absorbed from the gastrointestinal (GI) tract, it must successfully overcome two sequential barriers: it must **dissolve** and then **permeate** across the intestinal membrane.

### 1. Solubility (溶解度): The "Dissolution" Challenge
*   **Principle**: "No dissolution = No absorption." A drug must be in solution to be absorbed.
*   **FDA/BCS High Solubility Criterion**: A drug is considered **highly soluble** if its highest therapeutic dose is soluble in **≤ 250 mL** of aqueous media over the pH range of **1.0–6.8** at **37°C**.
    *   **Rationale**: 250 mL approximates the typical volume of fluid in the human stomach.
*   **Solubility Assessment**: Typically performed using the **shake-flask method** (摇瓶法) at pH 1.2, 4.5, and 6.8 to mimic GI conditions.

### 2. Permeability (渗透性): The "Membrane" Challenge
*   **Principle**: "No permeability = No absorption." The dissolved drug must cross the intestinal epithelial barrier.
*   **FDA/BCS High Permeability Criterion**: A drug is considered **highly permeable** if its **absolute bioavailability is ≥ 90%**, or if direct permeability measurements (e.g., Caco-2 cell assay) confirm high permeability.
*   **Governing Principle**: There is a fundamental trade-off between **Lipophilicity** (亲脂性) (favors permeability) and **Hydrophilicity** (亲水性) (favors solubility).

## IV. The Biopharmaceutics Classification System (BCS) (生物药剂学分类系统)

The BCS is a scientific framework that categorizes drugs into four classes based on their solubility and permeability, which is crucial for predicting absorption behavior and guiding regulatory decisions.

| BCS Class | Solubility | Permeability | Absorption Characteristics | Formulation Strategy | Biowaiver Eligibility |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Class I** | High | High | Absorption is rapid and complete. Not limited by dissolution or permeability. | Standard formulations are usually sufficient. | **✅ Yes**. Ideal candidate. |
| **Class II** | **Low** | High | Absorption is limited by **dissolution rate**. Once dissolved, it is well-absorbed. | **Enhance dissolution**: particle size reduction, salt formation, use of surfactants or co-solvents. | **❌ No**. Requires in vivo BE study. |
| **Class III** | High | **Low** | Absorption is limited by **permeability**. Drug dissolves easily but doesn't cross the membrane well. | **Enhance permeability**: permeation enhancers, prodrugs. | **✅ Yes** (under specific conditions). |
| **Class IV** | **Low** | **Low** | Absorption is poor and highly variable due to both low solubility and low permeability. | **Advanced strategies required**: nanoparticles, liposomes, complexation. | **❌ No**. Requires in vivo BE study. |

*   **Biowaiver** (生物豁免): A regulatory mechanism that allows the waiver of in vivo bioequivalence studies for certain drug products, primarily BCS Class I drugs, if their in vitro dissolution profiles are adequate.

## V. Bioavailability (F) (生物利用度) and Bioequivalence (BE) (生物等效性)

These are the key quantitative measures that link biopharmaceutical properties to clinical outcomes.

### Bioavailability (F)
*   **Definition**: The **rate** and **extent** to which the active drug ingredient is absorbed from its dosage form and becomes available at the site of action (systemic circulation).
*   **Absolute Bioavailability (Fabs)**: Compares a non-IV route to an IV dose (which is 100% bioavailable).
    *   **Formula**: `Fabs = (AUC_non-IV × Dose_IV) / (AUC_IV × Dose_non-IV)`
    *   **Example**: If an oral dose of 100 mg yields an AUC of 50, and an IV dose of 50 mg yields an AUC of 100, then `Fabs = (50 * 50) / (100 * 100) = 0.25` or **25%**.
*   **Relative Bioavailability (Frel)**: Compares two different non-IV formulations of the same drug.
    *   **Formula**: `Frel = (AUC_test × Dose_ref) / (AUC_ref × Dose_test)`
*   **Why Oral F is Usually <100%**: Due to incomplete dissolution, poor permeability, degradation in the GI tract, and **first-pass metabolism** (首过效应).

### Bioequivalence (BE)
*   **Definition**: Two pharmaceutical products (e.g., a generic and a brand-name drug) are considered **bioequivalent** if they are **pharmaceutical equivalents** (same API, dose, dosage form, route) and their **rates** and **extents** of absorption are not significantly different.
*   **PK Parameters for BE**: Bioequivalence is primarily assessed by comparing:
    *   **AUC (Area Under the Curve)** (曲线下面积): Measures the **extent** of absorption (total drug exposure).
    *   **Cmax (Maximum Concentration)** (峰浓度): Measures the **rate** of absorption (peak effect).
*   **Regulatory Standard**: The 90% confidence intervals for the test/reference ratio of AUC and Cmax must typically fall within the **80–125%** range.
*   **Significance**: BE is the **scientific and regulatory foundation for generic drug approval**, ensuring that a generic product will have the same safety and efficacy profile as the innovator product.

## VI. Impact of Route of Administration (ROA) (给药途径)

The chosen ROA dramatically alters a drug's journey and its resulting PK profile.

| Route | Key Characteristics | Bioavailability (F) | Advantages | Disadvantages |
| :--- | :--- | :--- | :--- | :--- |
| **Intravenous (IV)** (静脉注射) | Direct injection into a vein. | **100%** | Immediate effect, precise dosing, no absorption barriers. | Invasive, risk of infection, requires trained personnel, not suitable for self-administration. |
| **Intramuscular (IM)** (肌肉注射) | Injection into muscle tissue. | <100% (Variable) | Suitable for depot/long-acting formulations, good for vaccines. | Painful, absorption rate depends on injection site blood flow, risk of tissue damage. |
| **Oral (PO)** (口服) | Administration via the mouth. | <100% (Often low/variable) | Convenient, economical, non-invasive, suitable for self-administration. | Subject to GI barriers (enzymes, pH), variable absorption, **first-pass metabolism**. |
| **Sublingual/Buccal** (舌下/颊部) | Placement under the tongue or in the cheek. | <100% (but > Oral for some drugs) | Rapid absorption, bypasses first-pass metabolism, easy to terminate. | Limited to drugs that are potent and can be absorbed through oral mucosa. |
| **Inhalation** (吸入) | Delivery to the lungs via aerosol. | <100% (Variable) | Rapid systemic absorption (for small molecules) or direct local action (for asthma), minimal systemic side effects for local use. | Requires patient coordination, device-dependent, **particle size** (~1-5 µm) is critical. |
| **Transdermal** (经皮) | Application to the skin (patch). | <100% (Slow & sustained) | Avoids first-pass metabolism, provides steady drug levels, good for chronic conditions. | Drug must be potent and **lipophilic**, slow onset, potential for skin irritation. |

## VII. Plasma Concentration-Time Curve: The PK Roadmap

This curve is the primary tool for visualizing and quantifying a drug's journey through the body after administration.

*   **Absorption Phase (Ascending Limb)**:
    *   Drug enters the bloodstream; concentration rises.
    *   **Key Parameters**: **Cmax** and **Tmax** (达峰时间). These reflect the **rate** of absorption.
*   **Distribution Phase (Initial Rapid Decline)**:
    *   Drug distributes from the central compartment (blood) to peripheral tissues (e.g., fat, muscle).
*   **Elimination Phase (Terminal Decline)**:
    *   Distribution is complete; concentration declines as the drug is metabolized and excreted.
    *   The slope of this phase determines the drug’s **Half-life (t½)** (半衰期).
*   **AUC (Area Under the Curve)**:
    *   The total area under the curve, representing the **total drug exposure** over time. It is directly proportional to the **extent** of absorption.

## VIII. Key Takeaways & Applied Concepts

1.  **Formulation Matters**: The same drug in different formulations (e.g., tablet vs. suspension) can have vastly different PK profiles and clinical effects due to differences in the **liberation** step.
2.  **BCS is a Predictive Tool**: Understanding a drug's BCS class allows scientists to anticipate absorption challenges and design appropriate formulations and regulatory strategies (e.g., biowaiver eligibility).
3.  **BE Ensures Therapeutic Equivalence**: For a generic drug to be approved, it must be proven **bioequivalent** to the brand-name drug, meaning it delivers the same amount of drug to the bloodstream at the same rate (similar AUC and Cmax).
4.  **ROA Defines the Journey**: The choice of administration route is a critical decision that balances convenience, speed of onset, bioavailability, and patient factors. IV offers certainty (100% F), while oral offers convenience at the cost of predictability.
5.  **The Curve Tells the Story**: The plasma concentration-time curve integrates all ADME processes and provides the key parameters (Cmax, Tmax, AUC, t½) needed to understand and compare drug products.
