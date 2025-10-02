# W3 - Introduction to Pharmacokinetics (ADME)

## I. Core Definition and Scope of Pharmacokinetics (PK)

*   **Definition**: Pharmacokinetics is the study of the **movement of drug** (into, within, out) molecules within the body. It describes the quantitative relationship between the administered dose and the resulting drug concentration at the site of action over time.
*   **The ADME Framework**: PK is structured around four sequential and interconnected processes that define a drug's journey:
    1.  **Absorption** (吸收): The process by which a drug moves from its site of administration into the systemic bloodstream. (directly: IV, indirectly: others)
    2.  **Distribution** (分布): The reversible transfer of a drug from the blood to the various tissues and fluids (interstitial 间质 and intracellular fluids 细胞内液) of the body.
    3.  **Metabolism** (Biotransformation, 生物转化): The chemical alteration of the drug, primarily in the liver, to convert it into metabolites that are typically more water-soluble for excretion.
    4.  **Excretion** (排泄): The process by which the drug and its metabolites are eliminated from the body (in urine尿液, bile胆汁, feces粪便).
*   **LADME Extension**: The process often begins with **Liberation **(释放), which is the release of the active drug from its dosage form (e.g., a tablet disintegrating and dissolving).

## II. Absorption: Entry into the Systemic Circulation

Absorption is the critical first step for any non-intravenous drug to exert a systemic effect.

### Processes for Solid Oral Dosage Forms
Before a drug in a solid oral form (e.g., a tablet) can be absorbed, it must undergo a series of physical transformations:
1.  **Disintegration **(崩解): The tablet breaks down into smaller granules.
2.  **Deaggregation **(解聚): The granules break apart into fine particles.
3.  **Dissolution **(溶解): The fine particles dissolve in the gastrointestinal (GI) fluids to form an aqueous solution. Only the dissolved drug can be absorbed.

### Mechanisms of Drug Transport Across Membranes
Drugs cross biological membranes through several mechanisms:
*   **Passive Diffusion **(被动扩散): The most common mechanism. It is a non-saturable, energy-independent process where drugs move **down** their concentration gradient (from high to low concentration). It is highly dependent on the drug's lipid solubility.
*   **Facilitated Diffusion **(易化扩散): A carrier-mediated, energy-independent process that moves drugs **down** their concentration gradient. It is specific and can become saturated (e.g., glucose absorption via GLUT transporters).
*   **Active Transport **(主动转运): A carrier-mediated, energy-dependent (requires ATP) process that moves drugs **against** their concentration gradient. It is highly specific and saturable (e.g., absorption of iron and certain amino acids).
*   **Endocytosis **(胞吞作用): A process used for the absorption of exceptionally large molecules (e.g., proteins, peptides). The cell membrane engulfs the substance, forming a vesicle that transports it into the cell.

### The pH-Partition Hypothesis and the Henderson-Hasselbalch Equation
This is a central principle governing the absorption of weak acids and bases.
*   **Core Principle**: Biological membranes are composed of lipids. Therefore, only the **non-ionized **(unionized, 非离子化) form of a drug, which is **lipid-soluble **(脂溶性), can readily cross these membranes via passive diffusion. The **ionized **(离子化) form is **water-soluble **(水溶性) and is effectively "trapped" on one side of the membrane.
*   **Henderson-Hasselbalch Equation**:
    *   For a **Weak Acid **(弱酸) (`HA ⇌ H⁺ + A⁻`): `pH = pKa + log([A⁻]/[HA])`
        *   **Rule**: When `pH < pKa`, the non-ionized form (`HA`) predominates (good for absorption in acidic environments like the stomach).
        *   When `pH > pKa`, the ionized form (`A⁻`) predominates (poor absorption).
    *   For a **Weak Base **(弱碱) (`B + H⁺ ⇌ BH⁺`): `pH = pKa + log([B]/[BH⁺])`
        *   **Rule**: When `pH > pKa`, the non-ionized form (`B`) predominates (good for absorption in neutral/alkaline environments like the small intestine).
        *   When `pH < pKa`, the ionized form (`BH⁺`) predominates (poor absorption).
*   **Application**: A weak base with a pKa of 8.5 will be almost entirely ionized and unabsorbable in the stomach (pH ~2.0). In the small intestine (pH ~6.5), while still mostly ionized, a small but significant fraction will be non-ionized, allowing for practical absorption. A weak base with a pKa closer to 7.5 (e.g., 6.5) would be 50% non-ionized in the intestine, making it ideal for absorption there.

### Factors Affecting Absorption
*   **Patient-Related Factors**:
    *   **GI pH**: Dictates the ionization state of the drug (as per the pH-partition hypothesis).
    *   **GI Transit Time & Motility **(胃肠道动力): Faster gastric emptying speeds up the arrival of a drug in the small intestine (the primary site of absorption). Diarrhea can reduce absorption time.
    *   **Food**: Can dilute the drug and slow gastric emptying, thereby retarding absorption (e.g., ampicillin, aspirin). However, it can also reduce gastric irritation.
    *   **Disease States**: Conditions like malabsorption syndromes, achlorhydria (无胃酸症, lack of stomach acid), or liver cirrhosis (肝硬化) can significantly alter absorption and first-pass metabolism.
    *   **Drug-Drug Interactions**: One drug can affect the absorption of another (e.g., Vitamin C enhances iron absorption; calcium in milk forms insoluble complexes with tetracyclines, reducing their absorption).
*   **Drug-Related Factors**:
    *   **Physicochemical Properties**: Solubility, lipid/water partition coefficient, pKa, molecular weight (ideally <500 Da), and chemical stability (e.g., Penicillin-G is acid-labile (对酸不稳定), while Penicillin-V is acid-stable (耐酸)).
    *   **Particle Size **(粒径): For poorly soluble drugs, a smaller particle size increases the surface area for dissolution, enhancing absorption (e.g., chloramphenicol, griseofulvin).
    *   **Dosage Form**: Liquid formulations are generally absorbed faster than solids. Formulation can be designed to target specific sites (e.g., enteric-coated tablets for intestinal release).

## III. Distribution: From Blood to Tissues

Distribution is the process by which a drug leaves the systemic circulation and disperses throughout the body's fluids and tissues.

*   **Body Fluid Compartments**: Drugs distribute into plasma, interstitial fluid (组织间液), intracellular fluid (细胞内液), and specialized fluids like cerebrospinal fluid (CSF, 脑脊液), lymph (淋巴), and aqueous humor (房水).
*   **Plasma Protein Binding **(血浆蛋白结合):
    *   **Mechanism**: Most drugs reversibly bind to plasma proteins, primarily **albumin **(白蛋白) (for acidic drugs) and **alpha-1 acid glycoprotein **(α1-酸性糖蛋白) (for basic drugs). This forms a drug-protein complex.
    *   **Pharmacological Activity**: Only the **free **(unbound, 游离) drug is pharmacologically active, as it is small enough to leave the bloodstream and reach its site of action. The bound drug acts as a reservoir.
    *   **Significance**: High protein binding prolongs the drug's duration of action and delays its excretion. It can also lead to drug-drug interactions if one drug displaces another from its binding site, increasing the free concentration of the displaced drug and potentially causing toxicity (e.g., warfarin, phenytoin, diazepam are >90% bound).
*   **Tissue Barriers**:
    *   **Blood-Brain Barrier **(BBB, 血脑屏障): A highly selective barrier formed by tight junctions between capillary endothelial cells in the brain, enveloped by glial cells (胶质细胞). It is **semi-permeable **(半透性), allowing only **lipid-soluble** drugs to pass (e.g., levodopa, diazepam, barbiturates). Water-soluble and ionized drugs are generally excluded, protecting the central nervous system.

## IV. Metabolism (Biotransformation): Chemical Modification

Metabolism is the body's primary method for detoxifying and preparing drugs for elimination.

*   **Purpose**: To convert lipophilic (fat-soluble) drugs into more **hydrophilic **(亲水性, water-soluble) metabolites that can be easily excreted by the kidneys or bile. This usually results in **inactivation**, but can sometimes produce **active** (e.g., prodrugs like codeine to morphine) or **toxic** metabolites (e.g., paracetamol to NAPQI).
*   **Primary Site**: The **liver **(肝脏) is the main organ of metabolism, though the gut wall, kidneys, and lungs also contribute.
*   **Enzyme Systems**:
    *   **Microsomal Enzymes **(微粒体酶): Located in the smooth endoplasmic reticulum (e.g., liver, gut). The **Cytochrome P450 **(CYP450, 细胞色素P450) family is the most important group for Phase I reactions.
    *   **Non-Microsomal Enzymes **(非微粒体酶): Located in the cytoplasm and mitochondria (e.g., esterases, amidases).
*   **Phases of Metabolism**:
    *   **Phase I **(I相代谢) (Functionalization, 功能化): Introduces or exposes a polar functional group (-OH, -COOH, -NH2) on the drug molecule, making it more water-soluble. Reactions include **Oxidation **(氧化) (most common, e.g., phenytoin, diazepam), **Reduction **(还原) (e.g., chloramphenicol), and **Hydrolysis **(水解) (e.g., pethidine, procaine).
    *   **Phase II **(II相代谢) (Conjugation, 结合): Attaches the Phase I metabolite (or sometimes the parent drug) to a large, highly polar endogenous molecule. This drastically increases water solubility for excretion. Reactions include **Glucuronidation **(葡萄糖醛酸化) (e.g., morphine, chloramphenicol), **Acetylation **(乙酰化) (e.g., sulfonamides, isoniazid), **Methylation **(甲基化) (e.g., adrenaline, histamine), and **Glutathione conjugation **(谷胱甘肽结合) (e.g., paracetamol).
*   **First-Pass Metabolism **(首过代谢):
    *   **Definition**: The extensive metabolism of an orally administered drug that occurs in the liver (and gut wall) **before** it reaches the systemic circulation. This is because all blood from the GI tract drains into the liver via the **portal vein **(门静脉).
    *   **Consequence**: It can drastically reduce the **oral bioavailability** of a drug.
    *   **Examples**:
        *   **Partial First-Pass**: Drugs like propranolol and diazepam have reduced but still significant bioavailability, which can be compensated for by giving a higher oral dose.
        *   **Complete First-Pass**: Drugs like **nitroglycerin**, insulin, and hydrocortisone are almost entirely metabolized on their "first pass" through the liver, resulting in negligible oral bioavailability. These drugs **must** be administered via non-oral routes (e.g., sublingual for nitroglycerin) to be effective.

## V. Excretion: Elimination from the Body

Excretion is the final step in the ADME process, removing the drug and its metabolites from the body.

*   **Major Routes**:
    *   **Renal Excretion **(肾排泄) (Urine): The primary route for most drugs and their metabolites. It involves three key processes:
        1.  **Glomerular Filtration **(肾小球滤过): The unbound, low molecular weight (<10,000 Da) drug in plasma is passively filtered from the blood into the kidney tubules. This process is not dependent on the drug's lipid solubility.
        2.  **Tubular Reabsorption **(肾小管重吸收): Non-ionized, lipophilic drugs in the tubular filtrate can be passively reabsorbed back into the bloodstream. This process is highly dependent on **urine pH** (a key clinical application of the pH-partition hypothesis).
            *   **Weak acids** (e.g., aspirin, barbiturates) are ionized and "trapped" in **alkaline urine**, enhancing their excretion.
            *   **Weak bases** (e.g., pethidine, amphetamine) are ionized and "trapped" in **acidic urine**, enhancing their excretion.
        3.  **Tubular Secretion **(肾小管分泌): An active transport process that moves drugs (including protein-bound drugs that were not filtered) from the peritubular capillaries directly into the tubular fluid. There are separate transport systems for **acidic drugs** (e.g., penicillin, salicylates) and **basic drugs** (e.g., morphine, histamine).
    *   **Biliary Excretion **(胆汁排泄) (Feces): The liver actively secretes certain drugs and metabolites into the bile, which is stored in the gallbladder and released into the intestine.
        *   **Enterohepatic Circulation **(肠肝循环): Some drugs excreted in bile can be reabsorbed from the intestine back into the portal blood, returning to the liver. This cycle can **prolong** the drug's action (e.g., oral contraceptives, chloramphenicol, erythromycin).
        *   Drugs that are not reabsorbed are eliminated in the feces.
    *   **Pulmonary Excretion **(肺部排泄): The primary route for volatile substances like anesthetic gases and alcohol.
*   **Minor Routes**: Drugs can also be excreted in **saliva **(唾液) (can cause a metallic taste, e.g., metronidazole), **sweat **(汗液) (e.g., lithium, rifampicin), **breast milk **(乳汁) (a concern for nursing infants), and vaginal secretions.

## VI. Bioavailability and Bioequivalence

*   **Bioavailability **(F, 生物利用度): The **rate** and **extent** to which the active drug ingredient is absorbed from its dosage form and becomes available at the site of action (systemic circulation).
    *   **Absolute Bioavailability**: The fraction of an oral (or other non-IV) dose that reaches systemic circulation compared to an IV dose (which is 100% bioavailable). `F = (AUC_oral * Dose_IV) / (AUC_IV * Dose_oral)`.
    *   **Factors Reducing Oral F**: Incomplete dissolution/absorption, chemical degradation in the GI tract, and first-pass metabolism.
*   **Bioequivalence **(BE, 生物等效性): Two pharmaceutical products (e.g., a brand-name and a generic) are considered bioequivalent if they are pharmaceutical equivalents (same API, strength, dosage form, route) and their rates and extents of absorption are not significantly different. This is demonstrated by showing that their **AUC **(曲线下面积) (extent) and **Cmax **(峰浓度) (rate) are statistically similar (typically within a 80-125% confidence interval). Bioequivalence is the scientific foundation for generic drug approval.
