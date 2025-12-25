# Setting-up-a-SIEM-using-Splunk

**Objective**

The objective of this project was to gain hands-on experience with a full end-to-end Splunk SIEM workflow by completing a comprehensive 7-part tutorial. The focus was on ingesting log data, performing structured searches using SPL, enriching events with lookups, and creating actionable reports and dashboards.

This lab simulates how raw log data is transformed into meaningful security and operational insights, closely resembling real-world SIEM usage in SOC environments.

**Skills Learned**

- Practical understanding of SIEM architecture and workflows
- Hands-on experience with log ingestion and data onboarding
- Proficiency in Splunk Search Processing Language (SPL)
- Ability to analyze logs using fields, time ranges, and filters
- Experience with subsearches and advanced SPL pipelines
- Knowledge of lookup tables and data enrichment
- Creating reports, dashboards, and visualizations
- Improved troubleshooting and iterative problem-solving skills

**Tools Used**

- *Splunk (Search & Reporting App)* - log ingestion, search, reporting, and dashboards
- *Splunk Add Data Wizard* - onboarding tutorial datasets
- *SPL (Search Processing Language)* - querying and transforming data
- *CSV Lookup Tables* - enriching events with contextual information
- *Cryptomator* - secure storage of raw project artifacts and screenshots
- *Microsoft Word / PDF* - offline documentation and evidence capture

**Project Steps & Evidence**

Each screenshot included below represents a key milestone in the project.  
A full step-by-step screenshot archive (56 images) is maintained offline.

**1. Data Ingestion Using Add Data Wizard**

- Uploaded the Buttercup Games tutorial dataset using Splunk's Add Data Wizard
- Configured host assignment using path segment extraction
- Verified successful ingestion into the Search app
<img width="825" height="251" alt="Screenshot 2025-12-24 173821" src="https://github.com/user-attachments/assets/4d931963-3f00-4643-8f97-ad144add6e03" />

<img width="715" height="290" alt="Screenshot 2025-12-24 174751" src="https://github.com/user-attachments/assets/8b89eb95-acf8-43a6-88ac-78752b4009fc" />

**2. Initial Searches & Time Range Analysis**

- Performed keyword-based searches on ingested logs
- Compared results across preset and custom time ranges
- Understood differences between historical and real-time searches
<img width="1908" height="810" alt="Screenshot 2025-12-24 175122" src="https://github.com/user-attachments/assets/047e5b44-0464-43bd-a05b-afd2dcd80ee8" />

<img width="1919" height="758" alt="Screenshot 2025-12-24 182659" src="https://github.com/user-attachments/assets/3be8caf2-996d-4cad-8026-d8e0a9296e0e" />

**3. Field Exploration and Selection**

- Explored Interesting Fields and Selected Fields
- Added relevant fields (action, categoryId, productId) to search results
- Reviewed field summaries and value distributions

<img width="1551" height="641" alt="Screenshot 2025-12-24 184949" src="https://github.com/user-attachments/assets/17800afc-33fa-4c53-a02f-9f0029029702" />

<img width="756" height="516" alt="Screenshot 2025-12-24 190030" src="https://github.com/user-attachments/assets/0ae50955-6750-4f84-beb1-034b0fda4c9b" />

**4. Targeted SPL Searches & Pipelines**

- Built SPL queries using pipes (|)
- Applied commands such as top, stats, table, and rename
- Identified trends such as successful vs failed purchases
  
<img width="1917" height="728" alt="Screenshot 2025-12-24 191724" src="https://github.com/user-attachments/assets/ea872b3a-ec00-4151-9d95-9cc201ef6811" />


**5. Subsearches and Advanced Queries**

- Used subsearches to identify the most frequent customer
- Compared single-search vs subsearch approaches
- Extracted meaningful insights from nested SPL logic
<img width="1848" height="536" alt="Screenshot 2025-12-24 193948" src="https://github.com/user-attachments/assets/9abe81fa-69fe-4b5e-82c6-b550652dae12" />
<img width="1919" height="810" alt="Screenshot 2025-12-24 194220" src="https://github.com/user-attachments/assets/70c36181-ae69-4925-8c77-b7468117d05c" />


**6. Lookup Tables & Data Enrichment**

- Uploaded CSV lookup files containing product details
- Created lookup definitions and automatic lookups
- Enriched raw events with product names and prices
<img width="938" height="469" alt="Screenshot 2025-12-24 194642" src="https://github.com/user-attachments/assets/d6e4c944-dedd-4387-ade0-34032fccb319" />
<img width="1919" height="827" alt="Screenshot 2025-12-24 195226" src="https://github.com/user-attachments/assets/38b3c251-974e-460e-92d4-73478411d3d8" />
<img width="1919" height="620" alt="Screenshot 2025-12-24 195641" src="https://github.com/user-attachments/assets/26bc64b3-034f-403b-9c18-98bd89c736d7" />


**7. Reports, Dashboards & Visualizations**

- Saved SPL searches as reports
- Built dashboards with multiple panels
- Created visualizations (pie, column, line, sparkline)
- Added shared time range picker for dynamic analysis
<img width="1916" height="897" alt="Screenshot 2025-12-24 230138" src="https://github.com/user-attachments/assets/32e1490c-39b6-4494-bea4-39167ce578ab" />
<img width="1916" height="706" alt="Screenshot 2025-12-24 230929" src="https://github.com/user-attachments/assets/03d1022a-eec2-4c14-892c-07aa832b913c" />
<img width="1919" height="908" alt="Screenshot 2025-12-24 231611" src="https://github.com/user-attachments/assets/64a467f8-9a63-44a0-9112-2d21303a479c" />
<img width="1919" height="574" alt="Screenshot 2025-12-24 233848" src="https://github.com/user-attachments/assets/9becc4bc-cf23-4dd9-bc4f-1907888577b7" />

**Key Takeaways**

- SIEM work is iterative, not linear - mistakes require re-ingestion and reconfiguration
- Proper SPL construction is essential for accurate detection and reporting
- Data enrichment significantly improves the usability of raw logs
- Dashboards are only effective when backed by well-structured searches
- Documentation is critical for reproducibility and proof of work

  <img width="1890" height="814" alt="Screenshot 2025-12-24 235024" src="https://github.com/user-attachments/assets/3a4c85e8-6eb5-4fef-aa8b-3f451ece70d0" />


**Artifacts & Documentation**

- 📄 Offline step-by-step execution notes
- 📑 Compiled PDF with 56 sequential screenshots
- 🔐 All raw artifacts securely stored using encryption

**Disclaimer**

This project was completed for educational purposes only using a publicly available Splunk tutorial dataset. No real user or production data was involved.
