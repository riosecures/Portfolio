# Purpose
Herein is the methodology used by **Pym Technology** to identify, analyze, and evaluate information security risks.  
This policy ensures a consistent, reproducible, and effective approach to risk assessment in support of the **Information Security Management System (ISMS).**

# Scope
These processes apply to all information assets, personnel, systems, and operations within the scope of **Pym Technology’s ISMS**, specifically related to the development, deployment, and maintenance of the **SaaS marketing platform.**

# Risk Assessment Process Overview
The risk assessment process consists of the following stages:

1. Asset Identification  
2. Threat and Vulnerability Identification  
3. Risk Analysis (**Likelihood × Impact**)  
4. Risk Evaluation  
5. Risk Ownership Assignment  
6. Documentation of Results

Risk Assessment Criteria
### Likelihood rating   

| ⭐ Score | 📖 Description |
|---------|----------------|
| 1| 🟩  Rare: May occur in exceptional circumstances |
| 2| 🟩  Unlikely: Not expected but possible |
| 3| 🟨 Possible: Might occur at some time |
| 4| 🟧 Likely: Expected to occur occasionally |
| 5| 🟥 Almost Certain: Expected to occur frequently |

### Impact rating

| ⭐ Score | 📖 Description |
|---------|----------------|
| 1| 🟩  Negligible: No significant disruption or damage |
| 2| 🟩  Minor: Minor disruption or limited financial/reputation impact |
| 3| 🟨 Moderate: Noticeable impact requiring management attention |
| 4| 🟧 Major: Serious impact on operations, finances, or compliance |
| 5| 🟥 Severe: Critical impact, regulatory breach, or long-term damage |

### Risk level calculation:
#### Risk Score = Likelihood × Impact
##### Maximum Score = 25 

### 📊 Risk Matrix (Heatmap)

| Likelihood ↓ / Impact → | 1 (Insignificant) | 2 (Minor) | 3 (Moderate) | 4 (Major) | 5 (Severe) |
|--------------------------|------------------|-----------|--------------|-----------|------------|
| 1 Rare| 🟩 Low | 🟩 Low | 🟨 Medium | 🟨 Medium | 🟧 High |
| 2 Unlikely</span> | 🟩 Low | 🟨 Medium | 🟨 Medium | 🟧 High | 🟥 Extreme |
| 3 Possible</span> | 🟨 Medium | 🟨 Medium | 🟧 High | 🟥 Extreme | 🟥 Extreme |
| 4 Likely</span> | 🟨 Medium | 🟧 High | 🟥 Extreme | 🟥 Extreme | 🟥 Extreme |
| 5 Almost Certain</span> | 🟧 High | 🟥 Extreme | 🟥 Extreme | 🟥 Extreme | 🟥 Extreme |

### Risk Acceptance Criteria
1.  Low risks are generally acceptable with monitoring.
2. Medium risks require business justification or resort to partial mitigation.
3. High risks must be treated or explicitly accepted by senior management.

### Asset Identification
Assets considered in risk assessments may include, but not limited to:
1. Source code repositories (internal and external)
2. CI/CD Pipeline
3. Cloud infrastructure
4. Employee devices
5. All Data

### Threats and Vulnerabilities
Pym Technology uses recognized sources such as:
1. OWASP Top 10
2. NIST SP 800-30
3. Industry threat intelligence
4. Internal incident history
Each asset is assessed for applicable threats and vulnerabilities that could compromise confidentiality, integrity, and/or availability.

### Risk Ownership
1. Every identified risk is assigned to a Risk Owner, typically the owner of the associated asset or business process
2. Risk Owners are responsible for validating assessments and supporting treatment efforts.

### Review and Frequency
1. Reviewed at least every 12 months
2. Re-evaluated when there are significant changes to systems, processes, or threats
3. Updated before management reviews and internal audits.

### Outputs and Records
1. Risk Register
2. Risk Assessment Report
3. Updated Asset Inventory
4. Treatment Plan input
5. Statement of Applicability (SOA) input

### Policy Review
#### The contents within this document are to be audited every 12 months or upon significant change to the environment or regulatory requirements.

|Date |Version |Author | Description |Approval by | Last Updated | Review Frequency |Next Review|
|------|---|----------|--------------------|----------|------|------|------|
| &nbsp; | &nbsp; |  &nbsp;  |   &nbsp; |  &nbsp; |  &nbsp; |  &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |  &nbsp;  |   &nbsp; |  &nbsp; |  &nbsp; |  &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |  &nbsp;  |   &nbsp; |  &nbsp; |  &nbsp; |  &nbsp; | &nbsp; |

