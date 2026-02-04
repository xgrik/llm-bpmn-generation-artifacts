# LLM-Based BPMN Generation Artifacts

This repository contains supplementary artifacts associated with the scientific publication:

**Generating BPMN Healthcare Process Models Using LLMs**

The repository is intended to support transparency and reproducibility of the proposed multi-step LLM-based BPMN generation workflow by providing representative prompt formulations, input documents, and an example generated BPMN process model.

---

## Author and Contact

- **Author:** Adam Grík  
- **Contact:** xgrik@stuba.sk

---

## Repository Structure

### 📁 `documents/`

This directory contains the healthcare procedure documents used to evaluate the proposed workflow.  
The documents are referenced throughout the paper using anonymized identifiers:

- **DOC1** – Comprehensive Psychological Management of an Adult Patient with Chronic Pain  
- **DOC2** – Comprehensive Psychological Management of a Patient with a Somatic Disease  
- **DOC3** – Agoraphobia  
- **DOC4** – Post-Traumatic Stress Disorder  
- **DOC5** – Comprehensive Psychological Management of an Adult Patient with Depressive Disorder and Recurrent Depressive Disorder  

---

### 📁 `prompts/`

This directory contains the original prompt formulations used in the individual steps of the proposed workflow.  
The prompts correspond to the representative examples described in the paper and Appendix.

- **Listing 1.1** – Representative role-based prompt (`prompt_role_based.txt`)  
- **Listing 1.2** – Representative RAG initialization prompt (`prompt_rag_initialization.txt`)  
- **Listing 1.3** – Representative PRIN-based extraction of actors prompt (`prompt_prin_extraction_actors.txt`)
- **Listing 1.3** – Representative PRIN-based extraction of tasks prompt (`prompt_prin_extraction_tasks.txt`)
- **Listing 1.3** – Representative PRIN-based extraction of decisions prompt (`prompt_prin_extraction_decision.txt`)
- **Listing 1.4** – Representative schema-guided and constraint-based prompt (`prompt_schema_guided.txt`)  
- **Listing 1.5** – Representative BPMN XML generation prompt (`prompt_bpmn_generation.txt`)  
- **Listing 1.6** – Representative repair prompt (`prompt_repair.txt`)  

All prompts are provided in their original form as used during the experiments.

---

### 📁 `models/`

This directory contains an example of a final BPMN process model generated using the proposed workflow.

- **DOC1_final_bpmn.svg** – Final BPMN process model generated from **DOC1** using the multi-step LLM-based workflow

---

## Notes

- The repository provides representative artifacts and example outputs to complement the paper.
- The provided materials are intended for research and reproducibility purposes.

---

This repository is provided for academic and research use.  
Please cite the corresponding publication when using the materials.

