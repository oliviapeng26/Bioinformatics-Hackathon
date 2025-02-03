# Key Biomarkers in Kidney Transplant Failure - 🥇 Place

## Overview
This project investigates key differential gene expressions associated with kidney transplant rejection and fibrosis. Our work focuses on identifying potential biomarkers that can inform treatment strategies and improve patient outcomes.

**Key Objectives:**
- Analyze gene expressions to identify pathways linked to kidney transplant failure.
- Highlight top genes contributing to rejection and fibrosis.
- Recommend future approaches to enhance genetic screening and patient care.

## Problem Context & Motivation
- Kidney transplants face significant challenges, with nearly **40% failing within 10 years**.
- Genetic factors play a major role in **allograft rejection** and **fibrosis** (excess collagen deposition).
- Understanding gene expression differences is critical for improving outcomes and tailoring treatments.

## Research Question
**What are the key differential gene expressions driving kidney transplant rejection and fibrosis, and how can we investigate these biomarkers to enhance patient outcomes?**

## Methods
1. **Dataset Selection**: Identified datasets with genetic parameters relevant to kidney transplant rejection and fibrosis.
2. **Analysis Framework**:
   - Performed differential gene expression analysis using **Limma** in RStudio.
   - Generated Gene Set Enrichment Analysis (**GSEA**) plots for rejection and fibrosis.
   - Created a Venn diagram to find overlapping genes between these conditions.
3. **Key Genes Identified**:
   - **UTS2R**: Reduces blood flow to the kidney.
   - **C15orf40**: Causes inflammation, scarring, and immune response.
   - **NXNL2**: Contributes to long-term kidney failure.
   - **UBA1**: Leads to protein accumulation and damage.
   - **CYB53**: Causes oxidative stress and impaired kidney function.

## Results
- Top 5 overlapping genes were identified as the most critical contributors to kidney transplant failure.
- These biomarkers provide valuable insights into rejection processes and fibrosis pathways.

## Recommendations
1. **In-depth Genetic Pathway Studies**: Focus on genes involved in rejection and fibrosis during transplants.
2. **Enhanced Genetic Screening**:
   - Advocate for better regulation and improvement of donor genetic screening.
   - Leverage **AI** technologies for advanced screening processes.
3. **Future Research Directions**:
   - Explore **CRISPR** for targeted gene regulation.
   - Develop nanotechnology-based targeted drug delivery systems.

## Data Access
The `.Rmd` file requires specific `.rds` files to run the analysis. To download the required data files, refer to the [`data_instructions.md`](./data_instructions.md) file for detailed instructions.

## Conclusion
- A deeper understanding of genetic pathways is crucial for addressing rejection and fibrosis.
- AI-driven screening and genetic analysis can revolutionize kidney transplant outcomes.
- Continued attention to genetic factors is essential for success in transplant medicine.

## Acknowledgements
This project was developed during the **2024 Bioinformatics Hackathon**, where it won **First Place**. We thank the organisers and our team members for their collaborative efforts.

---

### Project Structure
- `data_instructions.md`: Datasets used for the analysis (linked externally).
- `/code`: Scripts for Limma analysis, GSEA plots, and venn diagram.
- `/results`: Final output of project presentation.

---

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
