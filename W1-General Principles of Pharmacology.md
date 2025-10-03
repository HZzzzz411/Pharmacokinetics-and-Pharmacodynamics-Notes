---
title: "General Principles of Pharmacology"
date: 2025-09-10
---

## I. Core Definitions

*   **Pharmacology**: The **science of drugs** and their **interactions with living systems** to produce a specific effect. It include:
    *   **Pharmacodynamics** (PD 药效学): What the drug does to the body    
        Studies the **drug's effects and mechanisms** of action.
    *   **Pharmacokinetics** (PK 药代动力学): what the body does to the drug
        Studies the **drug's journey through the body** (Absorption吸收, Distribution分布, Metabolism代谢, Excretion排泄 - ADME).
    *   **Pharmacotherapeutics**  (药物治疗学):The use of drugs to treat disease (disease-centered).
    *   **Toxicology** (毒理学): The study of **adverse (harmful) effects** of drugs.
    *   **Clinical Pharmacology** (临床药理学): The study of drugs in humans, focusing on their use in prevention, diagnosis, and treatment(诊断和防治) of diseases (patient-centered).
    *   **Pharmacogenomics** (药物基因组学): The study of how an individual’s **genetic** makeup influences their response to drugs.
    *   In experiments or clinical practice, we measure 3 key parameters to link PK & PD:
        *  Therapeutic dose(治疗剂量): The administered amount of drug（给药量）  
        *  Concentration(浓度): The level of drug measured in plasma/tissues (PK outcome)
        *  Effect: The clinical/biological response observed (PD outcome)
*   **Drug**: The **active chemical** substance with **biological activity** (e.g. Paracetamol 醋氨酚).
*   **Medicine (Pharmaceutical)**: The formulated product for **human use**, containing the active drug + **inactive ingredients** (excipients 赋形剂) like binders or fillers (e.g., Panadol® tablet).
*   **Dose**: The **quantity** of a drug administered at **one time**.
*   **Dosage Form**: The **physical form** in which a drug is administered (e.g. tablet, capsule, injection, syrup, cream, patch).

## II. Pharmacokinetics (PK): 

PK describes the fate of a drug within the body using the LADME framework.

*   **LADME Processes**:
    *   **Liberation (L)**: **Release** of the active drug from its dosage form.
    *   **Absorption (A)**: **Entry** of the drug into the **systemic bloodstream （blood circulation）**.
    *   **Distribution (D)**: Drug distributed throughout organs or tissues of the body
    *   **Metabolism (M)**: **Irreversible** transformation of drug in the body, primarily in the liver.
    *   **Excretion (E)**: **Removal** of the drug and its metabolites from the body (primarily via kidneys or liver).
*   **Key PK Parameters**:
    *   **Bioavailability** (F 生物利用度):
        *   **Definition**: The **rate and extent** to which the **active drug reaches** systemic circulation from its dosage form.
        *   **Measurement**: Fractional availability (F). Calculated as $$F = \frac{AUC(\text{desired route})}{AUC(IV)}$$
        *   **Intravenous (IV 静脉) Route:** 100% bioavailability (F=1), direct entry into bloodstream.
        *   Other Routes: F ≤ 1 (≤100%) due to **incomplete absorption** or first-pass metabolism.
    *   **Area Under the Curve (AUC)**:
        *  The total **area under** the plasma drug **concentration-time curve**. Directly proportional to the total amount of drug absorbed (**extent** of absorption). AUC越大，药物被机体吸收的越完全
    *   **Rate of Absorption**: How fast the drug reaches systemic circulation. Assessed by **Cmax** (peak plasma concentration) and **Tmax** (time to reach Cmax). Relevant for extravascular routes. Cmax he Tmax 对 IV没有意义（进入体内瞬间最大）    
        同一种药物的不同非IV剂型，Cmax和Tmax呈**负相关**趋势：吸收越快，Tmax越短，Cmax越高   
  ![Cmax and Tmax](https://github.com/HZzzzz411/Pharmacokinetics-and-Pharmacodynamics-Notes/raw/picture/image1.png)

    *   **Volume of Distribution (Vd)**:
        *   **Definition**: A theoretical volume **relating** the **total amount of drug** in the body to its **plasma concentration**. Indicates tissue distribution vs. staying in the blood. Calculated by: $$Vd (L/kg) = \frac{\text{Administered dose of drug}(D) × F} {\text{Plasma Concentration} (C)}$$. For IV, F=1, so $$Vd = Dose / C$$.
        *   **Unit**: D often mg/kg (服药量/体重), C is mg/L, so Vd is L/kg
        *   **Interpretation**: Normal adults have approximately **40L of fluids** in their body
            *   Low Vd (3-5 L): Confined to plasma (e.g., Heparin, Warfarin).
            *   Moderate Vd (10-20 L): Distributed in extracellular fluid 细胞外液 (e.g., Aminoglycosides).
            *   High Vd (>40 L): Extensively distributed into tissues/fat (e.g., Chloroquine, Digoxin, Antidepressants).
    *   **Clearance (CL)**: 单位时间内完全清除药物的血浆体积
        *  The volume of plasma completely cleared of drug per unit time. Measures elimination efficiency. $$CL = \frac{\text{Drug concentration in urine}(U) × \text{Urine Flow Rate} (V)}{\text{Plasma Concentration} (C)}$$.
        *   Via Organs: Kidneys, liver, lungs, etc.
    *   **Half-Life ($$t_{1/2}$$)** 半衰期:
        *   Time required for plasma drug concentration to **decrease by 50%** during elimination. （半衰期是不会随着剂量改变而改变的，若100mg代谢到50mg用12h，50mg到25mg也是12h）
        *   Clinical Significance: Determines dosing frequency and time to reach steady-state concentration.
        *   主要受Vd和CL影响，Vd越大或CL越小，半衰期越长
*   **Routes of Administration**:
    *   **Enteral** (via GI Tract 消化道):
        *   Oral (PO): Most common; convenient, but variable absorption/first-pass metabolism.
        *   Sublingual 舌下腺: Under tongue; rapid, bypasses liver.
        *   Rectal (PR) 直肠: Useful if oral not possible (vomiting呕吐 or unconscious昏迷); partial bypass of liver.
    *   **Parenteral** (injection 注射, bypasses GI):
        *   Intravenous (IV): Direct into vein; immediate effect, 100% F.
        *   Intramuscular (IM) 肌肉注射: Into muscle; good for depot/vaccines.
        *   Subcutaneous (SC) 皮下: Under skin; slow, sustained release (e.g., insulin).
    *   **Other Routes**:
        *   Inhalation 吸入: To lungs; rapid absorption (e.g., asthma meds).
        *   Topical 外用: On skin/mucosa for local effect.
        *   Transdermal 透皮: Patch for systemic effect; slow absorption (e.g., nicotine).

## III. Pharmacodynamics (PD):

PD studies the biochemical and physiological effects of drugs and their mechanisms of action.

*   **Drug-Receptor Interactions**:
    *   **Receptor** (受体): A specific **protein macromolecule** on or in a cell that a drug (ligand) binds to, initiating a biochemical effect.
    *   **Ligand** (配位体): A molecule (e.g., drug, hormone) that **binds to a receptor**.
    *   **Agonist** 激动剂: Binds to and **activates a receptor**, producing a response. Has **affinity** (亲和力) and **intrinsic activity/efficacy** (内在活性) 
    *   **Antagonist**: 拮抗剂 Binds to a receptor but does NOT activate it, blocking agonists. Has **affinity** but **no efficacy** 
*   **Key PD Concepts**:
    *   **Efficacy (Intrinsic Activity)**: The maximum therapeutic effect a drug can produce. 
    *   **Potency** : The amount (dose/concentration) needed to produce a given effect. Inversely related to EC₅₀ or ED₅₀.
    *   **EC₅₀ / ED₅₀**: Concentration (EC₅₀) or dose (ED₅₀) producing 50% of the maximum effect. Standard measure for potency comparison. EC₅₀越低potency越高
![Cmax and Tmax](https://github.com/HZzzzz411/Pharmacokinetics-and-Pharmacodynamics-Notes/raw/picture/image2.png)
    *   **Therapeutic Window**: The range of **doses**/concentrations between the **Minimum Effective** Dose/Concentration (MED/MEC) and the **Minimum Toxic** Dose (or maximum 
tolerated dose). Goal is to maintain levels within this window.
    *   **Therapeutic Index (TI)**: 药物安全性的衡量标准
        *   Safety margin measure. $$TI = \frac{TD_{50}}{ED_{50}}$$.
        *   TD₅₀: Dose toxic in 50% of population.
        *   ED₅₀: Dose effective in 50% of population.
        *   Narrow TI: Dangerous drugs where effective dose is close to toxic dose (e.g., Warfarin, Digoxin, Phenytoin). Requires Therapeutic Drug Monitoring (TDM).

## IV. Adverse Drug Reactions (ADRs) & Related Concepts

*   **Adverse Drug Reaction (ADR)**: Any unintended, harmful reaction to a drug at normal doses.
*   **Classification of ADRs**:
    *   **Type A (Augmented)**: Predictable, dose-dependent, pharmacological mechanism (e.g., side effects, toxic effects).
        *  **Side Effect**: Predictable, secondary effect at therapeutic doses (e.g., drowsiness from antihistamines). 与剂量相关
        *  **Toxic Effect**: Severe reaction from **overdose**/accumulation (e.g., liver failure from paracetamol overdose).
    *   **Type B (Bizarre)**: Unpredictable, dose-independent, immune or genetic mechanism 免疫或遗传机制 (e.g., allergic, idiosyncratic reactions).
        *   **Allergic Reaction**: Unpredictable, immune-mediated 免疫介导反应 (e.g., rash, anaphylaxis from penicillin).
        *   **Idiosyncratic Reaction**: Rare, unpredictable, genetically-based abnormal reaction (e.g., hemolysis in G6PD-deficient patients on sulfonamides).
*   **Tolerance** 耐受性: Decreased response with repeated use, requiring higher doses (e.g., opioids, nitrates).
*   **Dependence** : State where withdrawal symptoms(戒断症状) occur upon cessation (can be physical or psychological).
*   **Resistance** 耐药性: Reduced drug effectiveness against a disease (e.g., antibiotic resistance in bacteria).

## V. Drug Sources & Nomenclature

*   **Sources of Drugs**:
    *   **Natural**: Plants (Morphine, Digoxin), Animals (Insulin, Hormones), Minerals (Iron, Lithium), Microorganisms (Penicillin).
    *   **Synthetic**: Lab-created (majority of modern drugs, e.g., Omeprazole, Diazepam).
    *   **Biotechnology**: Genetically engineered (e.g., Human Insulin, Monoclonal Antibodies like Adalimumab).
*   **Drug Nomenclature**:
    *   **Chemical Name**: Precise molecular structure (e.g., N-(4-hydroxyphenyl)acetamide). Rarely used clinically.
    *   **Generic Name (Non-proprietary)**: Official, simplified name (e.g., Paracetamol/Acetaminophen). Standard for use. 非专有的，各品牌药物通用
    *   **Trade/Brand Name (Proprietary)**: Company marketing name (e.g., Tylenol®, Panadol®). One generic can have many brands.
