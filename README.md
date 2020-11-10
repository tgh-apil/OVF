
High Acuity Limited Operability (HALO) Emergency Ventilator: Performance and Regulatory Assessment 
===
## The purpose of this document is to serve as a guide towards the assessment and evaluation of available open source emergency ventilators in accordance with the global standards and requirements as disclosed by various healthcare organizations such as Health Canada (HC), Medicines and Healthcare products Regulatory Agency (MHRA), U.S. Food and Drug Administration (FDA), Australia’s Therapeutic Goods Administration (TGA) and open source regulatory organizations such as Open Source Hardware Association (OSHWA).


![downloads](https://img.shields.io/github/downloads/atom/atom/total.svg)
[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/)


## Table of Content

#### 1. Introduction	
[1.1. Purpose](Introduction/Purpose.md)

[1.2. Use Case](Introduction/Use_Case.md)	

[1.3. Considerations](Introduction/Considerations.md)


---

#### 2. Methodology	
[2.1. Evaluation Framework ](Methodology/Evaluation_Framework.md)

>This section provides the rationale behind the development of the proposed evaluation framework and describes 3 Levels of proposed evaluation. 
  
##### 2.2. Assessemnt of Regulatory Requirements: Sources
- [2.2.1. Regulatory Requirements](Methodology/Regulatory_Requirements.md)
- [2.2.1.1. Health Canada (CA)](Methodology/Health_Canada.md)
- [2.2.1.2. FDA (USA)](Methodology/FDA.md)
- [2.2.1.3. MHRA (EU)](Methodology/MHRA.md)
- [2.2.1.4 TGA (AUS)](Methodology/TGA.md)

##### 2.2.2. Required Standards

> Provided below are all relevant links and subsequent lists of sregulatory standards relevant to the development of the evaluation checklist.
> ##### [Required Standards: Links](Methodology/Required_Standards_Links.md)
- [2.2.2.1. ISO, IEC](Methodology/ISO_IEC.md)
- [2.2.2.2. FDA, Health Canada, AAMI, ANSI/IEEE](Methodology/FDA_Health_Canada_AAMI_ANSI_IEEE.md)
- [2.2.2.3. MHRA, TGA](Methodology/MHRA_TGA.md)

##### 2.2.3. Guide for ISO/IEC, AAMI & MECA Standards
- [2.2.3.1. Guide Through ISO/IEC Standards](Methodology/Guide/Guide_Through_ISO_IEC_Standards.md)
- [2.2.3.2. General Requirements](Methodology/Guide/General_Requirements.md)
- [2.2.3.3. General Requirements for testing ME Equipment](Methodology/Guide/General_Requirements_for_testing_ME_Equipment.md)
- [2.2.3.4. Classification of ME Equipment and ME System](Methodology/Guide/Classification_of_ME_Equipment_and_ME_System.md)
- [2.2.3.5. ME Equipment Identification, marking and documents](Methodology/Guide/ME_Equipment_Indentification_marking_and_documents.md)
- [2.2.3.6. Protection against electrical hazards from ME Equipment](Methodology/Guide/Protection_against_electrical_hazards_from_ME_Equipment.md)
- [2.2.3.7. Protection against mechanical hazards of ME Equipment and ME System](Methodology/Guide/Protection_against_mechanical_hazards_of_ME_Equipment_and_ME_System.md)
- [2.2.3.8. Protection against unwanted and excessive radiation Hazards	](Methodology/Guide/Protection_against_unwanted_and_excessive_radiation_Hazards.md)
- [2.2.3.9. Protection against excessive temperatures and other Hazards	](Methodology/Guide/Protection_against_excessive_temperatures_and_other_Hazards.md)
- [2.2.3.10 Accuracy of controls and instruments and protection against hazardous outputs	](Methodology/Guide/Accuracy_of_controls_and_instruments_and_protection_against_hazardous_outputs.md)
- [2.2.3.11. Hazardous situations and fault conditions for ME Equipment](Methodology/Guide/Hazardous_situations_and_fault_conditions_for_ME_Equipment.md)	
- [2.2.3.12. Programmable Electrical Medical Systems (PEMs)](Methodology/Guide/Programmable_Electrical_Medical_Systems.md)	
- [2.2.3.13. Construction of ME Equipment	](Methodology/Guide/Construction_of_ME_Equipment.md)
- [2.2.3.14. Construction of ME System](Methodology/Guide/Construction_of_ME_Equipment.md)
- [2.2.3.15. Electromagnetic Compatibility of ME Equipment and ME Systems](Methodology/Guide/Electromagnetic_Compatibility_of_ME_Equipment_and_ME_Systems.md)	
- [2.2.3.16. Additional Requirements to general standards (ISO 80601-2-80)](Methodology/Guide/Additional_Requirements_to_General_Standards.md)

> ##### AAMI & MECA Checklist
- [2.2.3.2. Guide Through AAMI](https://hackmd.io/RI94hY4pQWmrx7danaPAOA?both)
- [2.2.3.3. Guide Through MECA Checklist](https://hackmd.io/FB4fxOd1TJiSmmFXvukOBA?both)
- [2.3. Methodology of Synthesis	](https://hackmd.io/0PvHueU7TNeAhbs1OpDhQA?both)
- [2.4.  Limitations](https://hackmd.io/jqfZoly0THi_s7jcVMAwTg?both)	

---



#### 3.  OVF Specifications Database
##### [3.1.  Introduction ](https://hackmd.io/I4Iakq84RSuN3u6gznZPxg?both)		
##### [3.2. Database organization and content](https://hackmd.io/WdB4Uit-RmekGK3lbVyBAQ?both)
- [3.2.1. Performance Parameters	](https://hackmd.io/ZCIi4ZDfTuSuPvHGb7aDgw?both)
- [3.2.2. Risk Assessment](https://hackmd.io/I_Ga1kjfTz6vLSFQu0sFww?both)	
- [3.2.3. Human Factors Evaluation](https://hackmd.io/2i64ZZHwRXK1w7YLzn4Jsw?both)	
- [3.2.4. Mechanical Systems Assessment](https://hackmd.io/RVIyDQweRU2ZQICMaHh9Sw?both)
- [3.2.5. Electrical Systems Assessment](https://hackmd.io/9XONKiWKSP6Z0qoYR9lTbw?both) 
- [3.2.6. Infection Control](https://hackmd.io/6G72Ay5UQIOL3m89kqcf8A?both) 
- [3.2.7. Testing](https://hackmd.io/Ck55g0NMShyQ4qs2y-X6gA?both) 
- [3.2.8. General Items](https://hackmd.io/LO3vCGcFTECcKRiSz7Ic3w?both) 
- [3.2.9. Open Source Assessment](https://hackmd.io/zTqCdas2TRiuAU2Pq27q7A?both) 

#### 4 Walkthrough
> This section describes a step-by-step walkthrough of using the evaluation framework.
> #### [OVF Database Structure](https://hackmd.io/rVuMZwrjRyuTSJY652o3Dw?both)
- [4.1. Level 1 Evaluation](/mBOmSmCFQGOpj55bQqmTHA)
- [4.2. Level 2 Evaluation](/7d1yk-6UR5yIUlGZACV7fQ)
- [4.3. Level 3 Evaluation](/naIgEDJLQw242PvJ36nKYA)

#### 5 Appendices 

- [Assessment of **RepRepable Automated Open Source Bag Valve Mask-based Ventilator**](https://hackmd.io/B7lCqHVFTjyyT7X4T4BOHg?both)
> Following section includes an example evaluation that showcases how proposed evalaution framework vcan be applied to an open source ventilator design to assess its level of development, readiness, and compliance with the international standards.

> ### [**Evaluation of Reprapable Ventilator Design**](https://docs.google.com/spreadsheets/d/1Sm4jFiruWwtPTFmreUmV_ouC7RH_kJslhLav-8cOgDM/edit?usp=drive_web&ouid=110063970478845364701)





Usage
---


### File Download 

Publically available version of Handbook can be found here: *insert link


## Appendix and FAQ

:::info
**Find this document incomplete?** Leave a comment!
:::




