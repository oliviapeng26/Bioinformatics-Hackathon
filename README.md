# Key Biomarkers in Kidney Transplant Failure - 🥇 Place

---

## Research Question
**What are the key differential gene expressions driving kidney transplant rejection and fibrosis, and how can we investigate these biomarkers to enhance patient outcomes?**

## Problem Context & Motivation
- Kidney transplants face significant challenges, with nearly **40% failing within 10 years**.
- Genetic factors play a major role in **allograft rejection** and **fibrosis** conditions.
- Differential gene expression analysis is critical for improving outcomes and tailoring treatments.

**Key Objectives:**
- Analyse gene expressions to identify pathways linked to kidney transplant failure.
- Highlight top genes contributing to rejection and fibrosis.
- Recommend future approaches to enhance genetic screening and patient care.

---

## Methods
1. **Dataset**: Personally collected by Harvard PhD student, presented as a shiny app where we identified datasets with genetic parameters relevant to kidney transplant rejection and fibrosis.
2. **Analysis**:
   - Generated Gene Set Enrichment Analysis (**GSEA**) plots for rejection and fibrosis to locate faulty genes.
   - Performed differential gene expression analysis using **Limma** in RStudio. Genetic correlation to conditions were ranked according to B score.
   - Created a **Venn diagram** to find top 5/500 overlapping genes between rejection and fibrosis.
3. **Key Genes**: 
   - **UTS2R**: Reduces blood flow to the kidney.
   - **C15orf40**: Causes inflammation, scarring, and immune response.
   - **NXNL2**: Contributes to long-term kidney failure.
   - **UBA1**: Leads to protein accumulation and damage.
   - **CYB53**: Causes oxidative stress and impaired kidney function.

---

## Recommendations
1. **In-depth Genetic Pathway Studies**: Focus on genes involved in rejection and fibrosis during transplants.
2. **Enhanced Genetic Screening**:
   - Advocate for better regulation and improvement of donor genetic screening.
   - Leverage AI technologies for advanced screening processes.
3. **Future Research Directions**:
   - Explore CRISPR for targeted gene regulation.
   - Develop nanotechnology-based targeted drug delivery systems.

## Conclusion
A deeper understanding of genetic pathways is crucial for addressing rejection and fibrosis. Overall, continued attention to genetic factors is essential for success in transplant medicine. This project shows that AI-driven screening and genetic analysis can revolutionize kidney transplant outcomes.

---

## Acknowledgements
This project was developed during the **2024 Bioinformatics Hackathon**, where it won **First Place**. We thank the organisers (COMBINE, SUDATA, SPDSC) for hosting and our team members for their collaborative efforts.

---

### Project Structure
- `data_instructions.md`: Datasets used for the analysis are linked externally. The `.Rmd` file requires specific `.rds` files to run. To download the datasets, refer to [`data_instructions.md`](./data_instructions.md) for instructions.
- `/code`: Scripts for Limma analysis, GSEA plots, and venn diagram.
- `/results`: Final output of project presentation.

---

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

### Contact
Created by Olivia Peng. Feel free to reach out :)
