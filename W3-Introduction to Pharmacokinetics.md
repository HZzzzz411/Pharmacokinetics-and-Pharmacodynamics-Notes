# W3 - Introduction to Pharmacokinetics (ADME)

## I. Core Definition and Scope of Pharmacokinetics (PK)

*   **Definition**: Pharmacokinetics is the study of the **movement of drug** (into, within, out) molecules within the body. It describes the quantitative relationship between the administered dose and the resulting drug concentration at the site of action over time.
*   **The ADME Framework**: PK is structured around four sequential and interconnected processes that define a drug's journey:
    1.  **Absorption** (吸收): The process by which a drug moves from its site of administration into the systemic bloodstream. (directly: IV, indirectly: others)
    2.  **Distribution** (分布): The reversible transfer of a drug from the blood to the various tissues and fluids (interstitial 间质 and intracellular fluids 细胞内液) of the body.
    3.  **Metabolism** (Biotransformation, 生物转化): The chemical alteration of the drug, primarily in the liver, to convert it into metabolites that are typically more water-soluble for excretion.
    4.  **Excretion** (排泄): The process by which the drug and its metabolites are eliminated from the body (in urine尿液, bile胆汁, feces粪便).
*   **LADME Extension**: The process often begins with **Liberation **(释放), which is the release of the active drug from its dosage form (e.g., a tablet disintegrating and dissolving).   
![PK & PD](https://github.com/HZzzzz411/Pharmacokinetics-and-Pharmacodynamics-Notes/raw/picture/image8.png)

## II. Absorption: Entry into the Systemic Circulation

Absorption is the critical first step for any non-intravenous drug to exert a systemic effect.

### Processes for Solid Oral Dosage Forms
Before a drug in a solid oral form (e.g., a tablet) can be absorbed, it must undergo a series of physical transformations:
1.  **Disintegration**(崩解): The tablet breaks down into smaller granules.
2.  **Deaggregation**(解聚): The granules break apart into fine particles.
3.  **Dissolution**(溶解): The fine particles dissolve in the gastrointestinal (GI) fluids to form an aqueous solution. Only the dissolved drug can be absorbed.

### Mechanisms of Drug Transport Across Membranes
*   **Cell membrane (biological membrane)**: 双层磷脂(phospholipids) + protein molecules   
    lipid soluble substances 可溶于细胞膜并易渗透进入细胞   
    junctions between adjacent 上皮(epithelial)或内皮(endothelial)细胞有小孔(pores), 小的水溶性分子可通过
Drugs cross biological membranes through several mechanisms:
*   **Passive Diffusion**(被动扩散): The most common mechanism. It is a **non-saturable**, **energy-independent** process where drugs move **down** their concentration gradient (from high to low concentration). It is highly dependent on the drug's lipid solubility, 通常是亲脂性药物。
    *  水溶性药物（离子化的）会通过水通道或孔隙穿过细胞膜；脂溶性（非离子化）药物由于能溶解于生物膜的脂质双层中，所以能够轻易地穿过大多数生物膜。
*   **Facilitated Diffusion**(易化扩散): A **carrier-mediated** (transporter proteins转运蛋白), **energy-independent** process that moves drugs **down** their concentration gradient. It is specific and can become **saturate**d (e.g., glucose absorption via GLUT transporters).
    *   依赖载体蛋白的数量。glucose，iron 和 amino acids(氨基酸)从肠道吸收就是易化扩散。
*   **Active Transport**(主动转运): A **carrier-mediated**, **energy-dependent** (requires ATP) process that moves drugs **against** their concentration gradient. It is highly **specific and saturable** (e.g., absorption of iron and certain amino acids).
    *   化合物(compound)和膜一侧的特定载体结合后穿过细胞膜进入细胞, 在细胞另一侧复合物分解，载体回去转运其他分子
*   **Endocytosis**(胞吞作用): A process used for the absorption of **exceptionally large** molecules (e.g., proteins, peptides). The cell membrane **engulfs** the substance, forming a **vesicle**(囊泡) that transports it into the cell.

### The pH-Partition Hypothesis and the Henderson-Hasselbalch Equation
This is a central principle governing the absorption of weak acids and bases.
*   **Core Principle**: Biological membranes are composed of lipids. Therefore, only the **non-ionized**(unionized, 非离子化) form of a drug, which is **lipid-soluble**, can readily cross these membranes via passive diffusion. The **ionized **(离子化) form is **water-soluble** and is effectively "trapped" on one side of the membrane.
*   **离子化**：酸提供H+，碱接受H+，细胞膜对非离子化形式比离子化更具渗透性（在体液的生理pH=7.4的情况下脂溶性更高的药物以非离子化形式存在，水溶性更高的药物以离子化形式存在）
*   弱酸性药物在酸性介质中，弱碱性药物在碱性(allkaline)介质中 => 保持非离子化 => readily absorbed   
    弱酸性药物在碱性介质中，弱碱性药物在酸性介质中 => 离子化 => slowly absorbed
*   **Henderson-Hasselbalch Equation**:
    *   For a **Weak Acid**(弱酸) ($HA ⇌ H⁺ + A⁻$): $pH = pKa + log(\frac{[A⁻]}{[HA]})$
        *   When **pH < pKa**, the **non-ionized form (HA/RCOOH) predominates** (good for absorption in acidic environments like the stomach). 酸更酸吸收好
        *   When **pH > pKa**, the **ionized form (A⁻/RCOO⁻) predominates** (poor absorption).
        *   log中是离子化/非离子化，因此数值大代表环境偏碱性，酸被离子化，难吸收
    *   For a **Weak Base**(弱碱) ($B + H⁺ ⇌ BH⁺$): $pH = pKa + log(\frac{[B]}{[BH⁺]})$
        *   When **pH > pKa**, the **non-ionized form (B/ $RNH_2$) predominates** (good for absorption in neutral/alkaline environments like the small intestine). 碱更碱吸收好
        *   When **pH < pKa**, the **ionized form (BH⁺/ $RNH_{3}^{+}$) predominates** (poor absorption).
        *   log中是非离子化/离子化，因此数值大代表环境偏碱性，碱保持非离子化，易吸收（log中数值大都代表环境偏碱性）
*   pH = pKa时大约50%的分子离子化：pKa时分子50%离子化，50%非离子化的ph值
*   当药物在肠道中向下移动时，pH值增加，酸性药物更多离子化，而碱性药物的电离程度较低

### Factors Affecting Absorption
*   **Patient-Related Factors**:
    *   **GI pH**: Dictates the ionization state of the drug (as per the pH-partition hypothesis).
    *   **GI Transit Time & Motility**(胃肠道动力): Faster gastric emptying speeds up the arrival of a drug in the small intestine (the primary site of absorption). Diarrhea can reduce absorption time.
    *   **Surface area of GI organs**: 表面积越大吸收越快。小肠吸收比胃快因为表面积更大
    *   **Food**: Can dilute the drug and slow gastric emptying, thereby retarding absorption (e.g., ampicillin, aspirin). However, it can also reduce gastric irritation胃刺激.
    *   **Disease States**: Conditions like malabsorption(吸收不良), achlorhydria (无胃酸症, lack of stomach acid), Thyrotoxicosis(甲亢) or liver cirrhosis (肝硬化) can significantly alter absorption and first-pass metabolism.
    *   **Drug-Drug Interactions**: One drug can affect the absorption of another (e.g., Vitamin C enhances iron absorption; calcium in milk forms insoluble complexes with tetracyclines, reducing their absorption).
    *   **First pass metabolism**
*   **Drug-Related Factors**:
    *   **Physicochemical Properties**:
        *   physical state：液体比固体剂型在胃肠道吸收更快更好
        *   Solubility
        *   lipid/water partition coefficient: 脂溶性药物吸收更好
        *   pKa
        *   molecular weight (ideally <500 Da): 高分子量的药物通常不会口服(可能因酶降解而失活，如insulin)
        *   chemical stability: Penicillin-G 青霉素G is acid-labile (对酸不稳定) 不适合口服, while Penicillin-V is acid-stable (耐酸).
    *   **Particle Size**(粒径): For poorly soluble drugs, a smaller particle size increases the surface area for dissolution, enhancing absorption (e.g., chloramphenicol, griseofulvin).
        *   Neomycin (新霉素) is purposely given orally with poor absorption so it can act locally in the intestine

## III. Distribution: From Blood to Tissues

Distribution is the process by which a drug leaves the systemic circulation and disperses throughout the body's fluids and tissues.

*   **Body Fluid Compartments**: Drugs distribute into plasma, interstitial fluid (组织间液), intracellular fluid (细胞内液), GI fluid and specialized fluids like cerebrospinal fluid (CSF, 脑脊液), lymph (淋巴), and aqueous humor (房水).
    *   淋巴(Lymph)是流经淋巴系统(lymphatic system)的水样液体。淋巴帮助您的淋巴系统支持您的整体健康，为细胞和组织提供营养, 保护身体免受病毒、细菌和癌细胞等外来入侵者的侵害。
*   **Plasma Protein Binding**(血浆蛋白结合):
    *   **Mechanism**: Most drugs reversibly bind to plasma proteins like albumin (白蛋白), globulin (球蛋白), glycoprotein (糖蛋白), transferrin (转铁蛋白), and lipoprotein (脂蛋白: LDL, VLDL and HDL) to form drug-protein complexes.
        *   **albumin**(白蛋白) for acidic drugs and alpha-1 acid glycoprotein(α1-酸性糖蛋白) and others for basic drugs. Drug-protein binding depends on the **affinity** of drug for the protein
        *   药物和血浆蛋白结合后到drug depot (drug reservoir)被储存, no pharmacological action (无法穿过细胞膜)。随着游离药物分子经历代谢和排泄，drug-protein complexes会解离(dissociates)以提供更多的药物分子
    *   **Pharmacological Activity**: Only the **free**(unbound, 游离) drug is pharmacologically active, as it is small enough to leave the bloodstream and reach its site of action. The bound drug acts as a reservoir.
    *   **Significance**: High protein binding **prolongs the drug's duration** of action and **delays its excretion**. It can also lead to drug-drug interactions if one drug displaces another from its binding site, increasing the free concentration of the displaced drug and potentially causing toxicity (e.g. doxycycline多西环素, warfarin华法林, indomethacin吲哚美辛, propranolol普萘洛尔(心得安) and phenytoin苯妥英 are >90% bound).
*   **Tissue Barriers**:
    *   **Blood-Brain Barrier**(BBB, 血脑屏障): A highly selective barrier formed by tight junctions between **capillary endothelial cells**(毛细血管内皮细胞) in the brain, enveloped by **glial cells** (胶质细胞). It is **semi-permeable**(半透性), allowing only **lipid-soluble** drugs to pass (e.g., levodopa, diazepam, barbiturates). Water-soluble and ionized drugs are generally excluded, protecting the central nervous system.

## IV. Metabolism (Biotransformation): Chemical Modification

Metabolism is the body's primary method for detoxifying and preparing drugs for elimination.

*   **Purpose**: To convert lipophilic (fat-soluble) drugs into more **hydrophilic**(亲水性, water-soluble) metabolites that can be easily excreted by the kidneys or bile. This usually results in **inactivation**, but can sometimes produce **active** (e.g., prodrugs like codeine to morphine) or **toxic** metabolites (e.g., paracetamol to NAPQI).
    *   **Functionalization and conjugation**: chemical reactionsthat produce more watersoluble metabolites.
*   **Primary Site**: The **liver**(肝脏) is the main organ of metabolism, though the gastrointestinal, kidneys, plasma and lungs also contribute.
*   **Enzyme Systems**:
    *   **Microsomal Enzymes**(微粒体酶): Located in the **smooth endoplasmic reticulum**（平滑内质网), e.g., kidney, liver, gut. The **Cytochrome P450**(CYP450, 细胞色素P450) family is the most important group for Phase I reactions.
    *   **Non-Microsomal Enzymes**(非微粒体酶): Located in the **cytoplasm and mitochondria**(胞质和线粒体) (e.g., esterases, amidases).
*   **Phases of Metabolism**:
    *   **Phase I**(I相代谢, Functionalization): Introduces or exposes a **polar** functional group (-OH, -COOH, -NH2) on the drug molecule, making it more water-soluble. Reactions include **Oxidation**(氧化) (most common, e.g., phenytoin, diazepam), **Reduction**(还原) (e.g., chloramphenicol), and **Hydrolysis**(水解) (e.g., pethidine, procaine).
    *   **Phase II**(II相代谢, Conjugation): **Attaches the Phase I metabolite** (or sometimes the parent drug) to a large, highly polar endogenous molecule. This drastically increases water solubility for excretion. Reactions include **Glucuronidation**(葡萄糖醛酸化) (e.g., morphine, chloramphenicol), **Acetylation**(乙酰化) (e.g., sulfonamides, isoniazid), **Methylation**(甲基化) (e.g., adrenaline, histamine), **glycine conjugation**(甘氨酸结合), and **Glutathione conjugation**(谷胱甘肽结合) (e.g., paracetamol).
*   **First-Pass Metabolism**(首过代谢):
    *   **Definition**: The extensive metabolism of an orally administered drug that occurs in the liver (and gut wall) **before** it reaches the systemic circulation. This is because all blood from the GI tract drains into the liver via the **portal vein**(门静脉).
    *   **Consequence**: It can drastically reduce the **oral bioavailability** of a drug.
    *   **Examples**:
        *   **Partial First-Pass**: Drugs like propranolol and diazepam have reduced but still significant bioavailability, which can be compensated for by **giving a higher oral dose**.
        *   **Complete First-Pass**: Drugs like **nitroglycerin**(NTG), insulin, and hydrocortisone are almost entirely metabolized on their "first pass" through the liver, resulting in negligible oral bioavailability. These drugs must be **administered via non-oral routes** (e.g., sublingual for nitroglycerin) to be effective.

## V. Excretion: Elimination from the Body

Excretion is the final step in the ADME process, removing the drug and its metabolites from the body.

*   **Major Routes**:
    *   **Renal Excretion**(肾排泄) (Urine): The primary route for most drugs and their metabolites. It involves three key processes:
        1.  **Glomerular Filtration**(肾小球滤过): The **unbound, ionized, low molecular weight** (<10,000 Da) drug in plasma is passively filtered from the blood into the kidney tubules. This process is **not dependent on the drug's lipid solubility**(所有亲水性或亲脂性的药物都能穿过肾小球膜).
        2.  **Tubular Reabsorption**(肾小管重吸收): **Non-ionized, lipophilic** drugs in the tubular filtrate can be passively reabsorbed back into the bloodstream (也几乎完全通过被动扩散从肾小球滤液中重吸收回血流). Occur in both the ways in proximal and distal convoluted tubules(在近端和远端小管中以两种方式发生). This process is highly dependent on **urine pH** 
            *   **Weak acids** (e.g., aspirin, barbiturates巴比妥类药物, salicylates水杨酸盐) are ionized and "trapped" in **alkaline urine**, enhancing their excretion. 弱酸在碱性尿液中快速消除
            *   **Weak bases** (e.g., pethidine哌替啶, amphetamine苯丙胺) are ionized and "trapped" in **acidic urine**, enhancing their excretion. 弱碱在酸性尿液中快速排泄
        3.  **Tubular Secretion**(肾小管分泌): An active transport process that moves drugs (including protein-bound drugs that were not filtered) from the **peritubular capillaries**(围小管毛细血管) directly into the tubular fluid. There are separate transport systems for **acidic drugs** (e.g., penicillin, salicylates) and **basic drugs** (e.g., morphine, histamine).
![Renal Excretion](https://github.com/HZzzzz411/Pharmacokinetics-and-Pharmacodynamics-Notes/raw/picture/image9.png)

![Tubular Reabsorption](https://github.com/HZzzzz411/Pharmacokinetics-and-Pharmacodynamics-Notes/raw/picture/image10.png)
        *   **nephron**: the structural and functional unit of the kidney , each kidney has about 1–1.5 million nephrons. It is responsible for filtering blood, forming urine, and maintaining fluid and electrolyte balance
    *   **Biliary Excretion**(胆汁排泄) (Feces): The liver actively secretes certain drugs and metabolites into the bile, which is stored in the gallbladder and released into the intestine.
        *   **Enterohepatic Circulation**(肠肝循环): Some drugs excreted in bile can be reabsorbed from the intestine back into the portal blood, returning to the liver. This cycle can **prolong** the drug's action (e.g., oral contraceptives, chloramphenicol, erythromycin).
            *   The cycle is: Liver -> Bile -> (Gallbladder for storage) -> Intestine -> Reabsorption -> Portal Vein -> Liver... 肝脏-> 胆汁->（胆囊储存）-> 肠道-> 重吸收-> 门静脉-> 肝脏
        *   Drugs that are not reabsorbed are eliminated in the feces.
        *   高分子量、水溶性代谢物和极性药物(polar drugs)会经历胆汁排泄。
    *   **Pulmonary Excretion**(肺部排泄): The primary route for **volatile substances** like gases and volatile liquids (general anaesthetics, paraldehyde and alcohol).
*   **Minor Routes**: Drugs can also be excreted in **saliva**(唾液) (can cause a metallic taste, e.g., metronidazole), **sweat**(汗液) (e.g., lithium, rifampicin锂、利福平等类金属元素和mercury等重金属), **breast milk**(乳汁) (pH=6.5,脂溶性强的碱性药物容易在乳液中累积), and vaginal secretions.

## VI. Bioavailability and Bioequivalence

*   **Bioavailability**(F, 生物利用度): The **rate** and **extent** to which the active drug ingredient is absorbed from its dosage form and becomes available at the site of action (systemic circulation).
    *   **Absolute Bioavailability**: The fraction of an oral (or other non-IV) dose that reaches systemic circulation compared to an IV dose (which is 100% bioavailable). $F = \frac{AUC_oral * Dose_IV} {AUC_IV * Dose_oral}$.
    *   **Factors Reducing Oral F**: Incomplete dissolution/absorption, chemical degradation in the GI tract, plasma protein biding (血浆蛋白结合) and first-pass metabolism.
*   **Bioequivalence**(BE, 生物等效性): If the **difference in the bioavailability** of these two preparations (same drugs, same dose, same dosage forms) is **less than 20%**, these are known to be bioequivalent.
