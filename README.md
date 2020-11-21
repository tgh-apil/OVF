
# Open Emergency Ventilator Evaluation Framework

The purpose of this document is to serve as a guide towards the assessment and evaluation of available open source emergency ventilators in accordance with the global standards and requirements as disclosed by various healthcare organizations such as Health Canada (HC), Medicines and Healthcare products Regulatory Agency (MHRA), U.S. Food and Drug Administration (FDA), Australia’s Therapeutic Goods Administration (TGA) and open source regulatory organizations such as Open Source Hardware Association (OSHWA).


![downloads](https://img.shields.io/github/downloads/atom/atom/total.svg)
[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc/4.0/)

# Original Development Team
--- 
The following have actively contributed towards the formulation of the corresponding framework:<br/>
(Listed in alphabetical order of their last names)<br/>

Dr. Kamran Behdinan | PEng., FAAAS, FASME, FCAE, FCSME, FEIC, FPWC, AFAIAA <br/>
Professor <br/> 
NSERC Chair in "Multidisciplinary Engineering Design" <br/>
Director, U of T - Institute for Multidisciplinary Design and Innovation (IMDI) <br/>
Department of Mechanical & Industrial Engineering <br/>
Faculty of Applied Science & Engineering | University of Toronto <br/>
5 King's College Rd.| Toronto | Ontario, Canada | M5S 3G8<br/>
www.mie.utoronto.ca/labs/ARL-MLS/
http://imdi.mie.utoronto.ca/

Dr. Azad Mashari | MD FRCPC<br/>
Assistant Professor | Department of Anesthesia and Pain Medicine | University of Toronto, <br/>
Staff Anesthesiologist and Director of the Lynn and Arnold Irwin Advanced Perioperative Imaging Lab | Department of Anesthesiology and Pain Management | Toronto General Hospital | University Health Network <br/>
200 Elizabeth Street | Toronto| Ontario | M5G 2C4 <br/>

Dr. Aviv S. Gladman | MASc, MD, P.Eng, FRCPC <br/>
Chief Information Officer and Chief Medical Information Officer <br/>
Critical Care Physician | Mackenzie Richmond Hill Hospital <br/>
10 Trench Street | Richmond Hill | Ontario | L4C 4Z3<br/>

Kate Kazlovich | Graduate Student, Clinical Engineering Trainee <br/>
International Centre for Surgical Safety | St. Michael's Hospital <br/>
Institute of Biomaterials and Biomedical Engineering (BME) <br/>
Faculty of Applied Science & Engineering | University of Toronto <br/>
209 Victoria Street | Toronto | Ontario | M5B 1T8 <br/>

Dr. Jesse May | BA, MD <br/>
Resident Physician (CoD/PGY4) | Department of Anesthesiology and Pain Medicine | University of Toronto <br/>
200 Elizabeth Street | Toronto| Ontario | M5G 2C4 <br/>

S Ranjan Mishra | Graduate Student, B. Tech <br/>
Advanced Research Laboratory for Multifunctional Lightweight Structures <br/>
Department of Mechanical & Industrial Engineering <br/>
Faculty of Applied Science & Engineering | University of Toronto <br/>
5 King’s College Rd | Toronto | Ontario | M5S 3G8 <br/>

We would like to acknowledge the support of the Natural Sciences and Engineering Research Council of Canada (NSERC), [NSERC Alliance Grants # ALLRP 550058 – 20]. A.M. also supported the Department of Anesthes and Pain Management, University Health Network and the [Toronto General and Western Hospital Foundation](https://tgwhf.ca). 

We would also like to acknowledge support and guidance from our colleagues at Glia Inc., London Health Sciences Center; University Health Network and Mackenzie Innovation Institute. Finally, we would like to thank Nirmal Pol and Dorotea Gucciardo for their supporting contributions to this project. 

# Table of Contents

## 1. Introduction	
[1.1. Purpose](Introduction/Purpose.md)

[1.2. Use Case](Introduction/Use_Case.md)	

[1.3. Considerations](Introduction/Considerations.md)


---

### 2. Methodology	
[2.1. Evaluation Framework ](Methodology/Evaluation_Framework.md)

This section provides the rationale behind the development of the proposed evaluation framework and describes 3 Levels of proposed evaluation. 
  
#### 2.2. Assessemnt of Regulatory Requirements: Sources
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
- [2.2.3.2. Guide Through AAMI](Methodology/Checklists/Guide_Through_AAMI.md)
- [2.2.3.3. Guide Through MECA Checklist](Methodology/Checklists/Guide_Through_MECA_Checklist.md)
- [2.3. Methodology of Synthesis	](Methodology/Methodology_of_Synthesis.md)
- [2.4.  Limitations](Methodology/Limitations.md)	

---



#### 3.  OVF Specifications Database
##### [3.1.  Introduction ](OVF_Database/Limitations.md)		
##### [3.2. Database organization and content](OVF_Database/Database_organization_and_content.md)
- [3.2.1. Performance Parameters	](OVF_Database/Performance_Parameters.md)
- [3.2.2. Risk Assessment](OVF_Database/Risk_Assessment.md)	
- [3.2.3. Human Factors Evaluation](OVF_Database/Human_Factors_Evaluation.md)	
- [3.2.4. Mechanical Systems Assessment](OVF_Database/Mechanical_Systems_Assessment.md)
- [3.2.5. Electrical Systems Assessment](OVF_Database/Electrical_Systems_Assessment.md) 
- [3.2.6. Infection Control](OVF_Database/Infection_Control.md) 
- [3.2.7. Testing](OVF_Database/Testing.md) 
- [3.2.8. General Items](OVF_Database/General_Items.md) 
- [3.2.9. Open Source Assessment](OVF_Database/Open_Source_Assessment.md) 

#### 4 Walkthrough
> This section describes a step-by-step walkthrough of using the evaluation framework.
> ##### [OVF Database Structure](OVF_Walkthrough/Database_Structure.md)
- [4.1. Level 1 Evaluation](OVF_Walkthrough/Level_1.md)
- [4.2. Level 2 Evaluation](OVF_Walkthrough/Level_2.md)
- [4.3. Level 3 Evaluation](OVF_Walkthrough/Level_3.md)

#### 5 Appendices 

- [Assessment of **RepRepable Automated Open Source Bag Valve Mask-based Ventilator**](Sample_Evaluation/RepRepable.md)
> Following section includes an example evaluation that showcases how proposed evalaution framework vcan be applied to an open source ventilator design to assess its level of development, readiness, and compliance with the international standards.

> ### [**Evaluation of Reprapable Ventilator Design**](https://docs.google.com/spreadsheets/d/1Sm4jFiruWwtPTFmreUmV_ouC7RH_kJslhLav-8cOgDM/edit?usp=drive_web&ouid=110063970478845364701)


Usage
---

:::info
**Find this document incomplete?** Leave a comment or contact the authors!
:::




