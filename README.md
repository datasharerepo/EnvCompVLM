**Can Vision-Language Models Assess Environmental Reporting Compliance? A Benchmark for Requirement-Level Disclosure Alignment**

**Dataset Description**
The GHG Disclosure Alignment Benchmark is a multimodal sustainability-reporting dataset designed for evaluating requirement-level disclosure alignment against TWO established sustainability reporting frameworks: GRI and ESRS. The benchmark focuses on environmental disclosures related to greenhouse gas (GHG) emissions and climate targets under these frameworks. Complete data will be released after acceptance of paper.

**Dataset Schema Details:**
  Company Id: Unique company identifier
  Sector: Company's sector
  Disclosure: Name and ID of disclosure 
  Requirements: Associated Reporting Requirements to Disclosure
  Alignment: Alignment Annotation (Full, Partial, No)
  Gaps: Set of sub-requirements for which evidence data is not present
  
**Dataset Statistics:**
  Sustainability Reports: 43
  Industry Sectors: 11
  Reporting Frameworks: GRI, ESRS
  Disclosures addressed: GRI 305, ESRS E1-4, ESRS E1-6
  Disclosure Alignment Instances: 731
  Expert Annotators: 3

**Annotation Labels:**
  Full (F): All reporting requirements for the disclosure are satisfied
  Partial (P): At least one reporting requirements for the disclosure are satisfied
  No (N): Not a single reporting requirement for the disclosure is satisfied

**Disclosures Covered:**
    1.	GRI 305
        o	GRI 305-1: Direct (Scope 1) GHG Emissions
        o	GRI 305-2: Energy Indirect (Scope 2) GHG Emissions
        o	GRI 305-3: Other Indirect (Scope 3) GHG Emissions
        o	GRI 305-4: GHG Emissions Intensity
        o	GRI 305-5: Reduction of GHG Emissions
        o	GRI 305-6: Ozone-Depleting Substances (ODS)
        o	GRI 305-7: Other Significant Air Emissions
    
    2.	ESRS E1-4
        o	P33: Climate Targets
        o	P34: GHG Reduction Targets
    
    3.	ESRS E1-6
        o	P44: Scope 1, 2, 3 and Total Emissions
        o	P46: Operational-Control Emissions
        o	P47: Reporting Boundary Changes
        o	P48: Scope 1 Emissions and ETS Exposure
        o	P49: Location-Based and Market-Based Scope 2 Emissions
        o	P50: Emissions Disaggregation
        o	P51: Scope 3 Category-Level Emissions
        o	P52: Total GHG Emissions Disclosure
        
**Gap Annotations:**
A key contribution of this benchmark is the inclusion of requirement-level gap annotations. For every disclosure, annotators identify which reporting requirements are missing from the company's sustainability report.
