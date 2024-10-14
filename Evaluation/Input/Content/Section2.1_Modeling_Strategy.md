To avoid identifiability issues, renal uptake of furosemide was incorporated in the model via OAT3 only, as a substitute for transport by both, OAT1 and OAT3, since both transporters are predominantly expressed in the kidney and show a similar affinity to furosemide *in vitro*. 

The general concept of building a PBPK model has previously been described by Kuepfer et al. ([Kuepfer 2016](#5-references)). Relevant information on anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in adults was gathered from the literature and has been previously published ([Willmann 2007](#5-references)). The information was incorporated into PK-Sim® and was used as default values for the simulations in adults.

The applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available PK-Sim® Ontogeny Database Version 7.3 ([PK-Sim Ontogeny Database Version 7.3](#5-references)) or otherwise referenced for the specific process.

A mean model was built based on clinical data from studies with intravenous and oral administration of furosemide. The studies reported individual or mean plasma concentrations of furosemide, from which 27 studies reported fraction excreted unchanged in urine profiles following intravenous and oral administration. In the intravenous studies, furosemide was administered in doses of 20–80 mg. In the oral studies, furosemide was administered in doses of 1–80 mg. The mean PBPK model The PBPK models were built based on data from healthy
individuals, using the reported sex, ethnicity and mean values for age, weight and height from each study protocol. If no demographic information was reported in the respective clinical study, the following default values were used: male, European, 30 years of age,73 kg body weight and 176 cm body height. The relative tissue-specific expressions of the enzyme and transporter predominantly being involved in the metabolism/transport of furosemide (UGT1A9, OAT3, ABCC4) were considered ([Meyer 2012](#5-references)). A Weibull function was fitted to describe the oral dissolution of furosemide.  

The clinical datasets for furosemide PBPK modeling were divided into a training dataset for model building and a test dataset for model evaluation. Both datasets are presented in [Section 2.2](#22-data-used).

A specific set of parameters ([Section 2.3.4.](#22-data-used)) were optimized to describe the disposition of furosemide using the Parameter Identification module provided in PK-Sim®. To limit the parameters to be optimized during model building,the minimal number of processes necessary to mechanistically describe the pharmacokinetics and drug-drug interactions (DDIs) of the modeled drugs were implemented into the models. The furosemide OAT1 and OAT3 transport rate constants would be highly correlated in a model parameter optimization since there is no further information found to distinguish these two transporters. To avoid indentifiability issues, renal uptake of furosemide was implemented by the transporter with the slightly higher affinity for the respective substrate (OAT3) was implemented, to describe a transport that probably is accomplished by both transporters in vivo. Structural model selection was mainly guided by visual inspection, mean relative deviation and geometric mean fold error of all predicted AUClast and Cmax values.

The model was verified by simulating further clinical studies reporting pharmacokinetic concentration-time profiles after intravenous and oral administration of furosemide (test datasets).

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#22-data-used).

Details about the structural model and its parameters can be found in [Section 2.3](#23-model-parameters-and-assumptions).




