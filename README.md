# Assessing the Alignment of University Library Collections with Scholarly Research Outputs: UW–Madison Case Study

This repository contains the Jupyter Notebooks used in the project *Assessing the Alignment of University Library Collections with Scholarly Research Outputs: UW–Madison Case Study*.

## Repository Contents

The workflow is organized into the following notebooks:

- `1_uwm_paper_get.ipynb`  
  Extracts publications affiliated with the University of Wisconsin–Madison from the Web of Science (WOS) dataset.

- `2_wos_ref_count.ipynb`  
  Retrieves reference information from the selected UW–Madison papers.

- `3_reference_analysis.ipynb`  
  Extracts ISSN/ISBN and other metadata from the references for subsequent matching.

- `4_mysql_oa_data.ipynb`  
  Retrieves Open Access status and discipline classifications from OST MySQL data.

- `5_library_data_match.ipynb`  
  Matches the processed reference data with university library holdings data.

## Notes

- Each notebook includes selected cell outputs to help illustrate the purpose and logic of each step in the workflow.
- The code has been simplified to remove redundant or overly complex steps, as well as to avoid potential issues related to proprietary or sensitive data.
- For questions regarding the code, please feel free to contact **wgu53@wisc.edu**.