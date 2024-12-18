The presented model building and evaluation report evaluates the performance of a PBPK model for furosemide in healthy adults.

The herein presented model was developed and published by Hanke et al. [Britz 2020](#5-references) and adjusted later on to PK-Sim V11 by re-optimizing OAT3 and ABCC4 Kcat. 

Furosemide is a loop diuretic, and its primary mechanism of action involves inhibition of tubular re-absorption of sodium and chloride in the kidneys, specifically by blocking the sodium-chloride-potassium transporter system in the thick ascending limb of the loop of Henle [Ponto and Schoenwald 1990](#5-references)). Furosemide is used to treat edema or high blood pressure.

Furosemide is a poorly soluble and permeable compound and is classified as a BCS IV drug. Transporters play an essential role in
furosemide absorption, distribution and elimination. Furosemide bioavailability is highly variable (37%–83%), and influenced by dosage form and fasted/fed state of the patient. The poor bioavailability has been hypothesized to be due to the poor solubility of the compound, but also site-specific absorption, pre-systemic metabolism and/or other unknown mechanisms ([Ponto and Schoenwald 1990](#5-references)). 
The kidney is the main organ for furosemide metabolism and excretion, 50% to 80% of an intravenously administered dose and 20% to 55% of an orally administered dose are excreted unchanged in urine. The majority of furosemide dose is eliminated unchanged through active secretion mediated primarily by organic anion transporters (i.e., OAT1 and OAT3), and multidrug resistance-associated protein 4 (MRP4, also known as ABCC4), whereas the remaining dose is metabolized by uridine 5'-diphospho-glucuronosyltransferase 1A9 (UGT1A9).

The herein presented PBPK model of furosemide PBPK model has been developed using 42 different clinical studies, including intravenous (single dose) and oral (single- and multiple dose) administration as a solution or an immediate-release tablet. The model has then been evaluated by comparing simulations to observed data of both intravenously and orally administered furosemide covering a dose range of 1 mg to 80 mg. 

The presented model includes the following features:

- metabolism by UGT1A9,
- transport by OAT3,
- transport by ABCC4,
- renal clearance by glomerular filtration,
- oral absorption with dissolution rate assigned to a Weibull function.
