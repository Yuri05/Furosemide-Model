### In vitro and physicochemical data

A literature search was performed to collect available information on physicochemical properties of furosemide. The obtained information from literature is summarized in the table below, and was used for model building. Final model parameters are stated in [Section 3.1](#31-furosemide-final-input-parameters).

| **Parameter**           | **Unit** | **Value** | Source                               | **Description**                                              |
| :---------------------- | ----------- | --------- | ------------------------------------ | ------------------------------------------------------------ |
| MW                      | g/mol    | 330.74    | [Wishart 2006](#5-references)        | Molecular weight |
| pK<sub>a</sub> (acid)   |          | 3.51      | [Avdeef 2008](#5-references)       | acid dissociation constant |
| pK<sub>b</sub> (base)   |          | 9.87      | [Box 2006](#5-references)       | base dissociation constant |
| Solubility (FaSSIF)     | mg/mL    | 3.20      | [Takács-Novák 2013](#5-references)            | solubility |
| logP                    |          | -0.24     | [Ventura 1996](#5-references), [Avdeef 2003](#5-references) and [Berthod 1999](#5-references) | Partition coefficient between octanol and water |
| fu                      | %        | 2.20      | [Shen 2019](#5-references), [Vree 1995](#5-references), [Andreansen 1977](#5-references), [Smith 1980](#5-references), [Rane 1978](#5-references), [Andreansen 1983](#5-references), [Andreansen 1982](#5-references), [Vree 1994](#5-references) , [Pacifici 1987](#5-references) ,[Andreansen 1974](#5-references)  and [Forrey 1974](#5-references)                         | Fraction unbound in plasma                |                       
| K<sub>m</sub> UGT1A9    | µmol/L   | 72.00     | [Britz 2020](#5-references) | BCRP Michaelis-Menten constant            |
| K<sub>m</sub> OAT3      | µmol/L   | 21.50     | [Ebner 2015](#5-references) | OAT3 Michaelis-Menten constant            |
| K<sub>m</sub> MRP4      | µmol/L   | 27.96     | [Britz 2020](#5-references) | OATP2B1 Michaelis-Menten constant         |
| Weibull shape           | -        | 0.53      | [McNamara 1987](#5-references) and [Langenbucher 1972](#5-references)  | Dissolution profile shape |
| Weibull time            | min      | 26.77     | [Bindschedler 1997](#5-references), [Martin 1984](#5-references), [FDA 2005](#5-references) and [Shoaf 2007](#5-references)                 | Dissolution time (50% dissolved)                             |

### Clinical data

A literature search was performed to collect available clinical data on furosemide in adults. 

The following publications were used for model building (training dataset) and model verification (test dataset):

| **Dose [mg]** | **Dosing** | **PK data** |**Dataset**| **Reference** |
| --------------- | ------------------- | ----------------------- | ----------------- |----------------- |
| 20| iv (bolus), sd |plasma, excretion into urine|training|[Haegeli 2007](#5-references) |
| 20| iv (5 min), sd |plasma|test|[Rosenkranz 1992](#5-references)| 
|22| iv (bolus), sd |plasma|test|[Tilstone 1978](#5-references)| 
| 35.5| iv (bolus), sd |excretion into urine|test|[Alván 1988](#5-references)| 
| 40| iv (bolus), sd |plasma, excretion into urine|test|[Andreansen 1977](#5-references)
| 40| iv (bolus), sd |plasma|test|[González 1982](#5-references)|
| 40| iv (bolus), sd |plasma, excretion into urine|test|[Hammarlund 1984](#5-references)|
| 40| iv (bolus), sd |plasma|test|[Homeida 1977 ](#5-references)|
| 40| iv (bolus), sd |plasma, excretion into urine|training|[Keller 1981](#5-references)|
| 40| iv (bolus), sd |plasma, excretion into urine|test|[Lambert 1983](#5-references)|
| 40| iv (bolus), sd |plasma|training|[Rupp 1974](#5-references)|
| 40| iv (2 min), sd |plasma|test|[Waller 1982](#5-references)|
| 40| iv (3 min), sd |plasma, excretion into urine|test| [Smith 1980a](#5-references)| 
| 40| iv (3 min), sd |excretion into urine|test| [Smith 1980b](#5-references)|  
| 80| iv (bolus), sd |plasma, excretion into urine|training| [Branch 1977](#5-references)|  
| 80| iv (bolus), sd |plasma, excretion into urine|training| [Branch 1977](#5-references)|  
| 80| iv (bolus), sd |plasma|test| [Kelly 1974](#5-references)|
| 80| iv (bolus), sd |plasma|test| [Rane 1978](#5-references)| 
| 80| iv (bolus), sd |plasma, excretion into urine|training| [Verbeeck 1982](#5-references)|
| 80| iv (2 min), sd |excretion into urine|test| [Andreansen 1981](#5-references)| 
| 80| iv (2 min), sd |plasma, excretion into urine|test| [Andreansen 1983](#5-references)|
| 1| po (sol), sd |plasma, excretion into urine|training| [Stopfer 2018](#5-references) |
| 5| po (sol), sd |plasma, excretion into urine|training| [Stopfer 2016](#5-references) |
| 20| po (sol), sd |plasma, excretion into urine|test|[Waller 1985](#5-references) 
| 20| po (tab), sd |plasma, excretion into urine|test|[Haegeli 2007](#5-references)   |
| 20| po (tab), qd |plasma|test|[FDA 2006](#5-references)   |
| 20| po (-), qd |plasma|test|[Vaidyanathan 2008](#5-references)|
| 40| po (sol), sd |plasma|training| [Waller 1982](#5-references)| 
| 40| po (sol), sd |plasma, excretion into urine|training|[Waller 1985](#5-references)|
| 40| po (sol), sd |plasma, excretion into urine|test|[Waller 1988](#5-references)|
| 40| po (tab), sd |plasma|test|[Ballester 2015](#5-references)|
| 40| po (tab), sd |plasma|training|[Bindscheller 1997](#5-references)|
| 40| po (tab), sd |plasma, excretion into urine|test|[Hammarlund 1984](#5-references)|
| 40| po (tab), sd |plasma, excretion into urine|test|[Martin 1984](#5-references)|
| 40| po (tab), sd |plasma, excretion into urine|training|[Rakhit 1987](#5-references)|
| 40| po (tab), sd |plasma, excretion into urine|test|[Rupp 1974](#5-references)|
| 40| po (tab), sd |plasma, excretion into urine|test|[Waller 1982](#5-references)|
| 40| po (tab), qd |plasma|training|[FDA 2005](#5-references)|
| 40| po (tab), sd |plasma|test|[Tilstone 1978](#5-references)|
| 40| po (tab), sd |plasma|test|[Kelly 1974](#5-references)|
| 80| po (sol), sd |plasma, excretion into urine|test|[Waller 1985](#5-references)|
| 80| po (tab), sd |plasma|test|[Kelly 1974](#5-references)|
| 80| po (tab), sd |plasma, excretion into urine|training|[Shoaf 2007](#5-references)|
| 80| po (tab), sd |plasma, excretion into urine|test|[Vree 1995](#5-references)|
