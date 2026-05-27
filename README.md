Integrated Cytometry Analysis: Python and R

A methodological comparison of cytometry analysis pipelines across Python and R, examining where computational choices converge, diverge, and shape biological interpretation.

Status:
In active development. This is the capstone project of a computational immunology portfolio I'm building throughout 2026 as preparation for graduate study. Target completion: August-September 2026. Until then, this README serves as a planning document for the project's scope and structure. Code, notebooks, and figures will be added as each stage of the analysis is completed.
This repository depends on the completion of cytometry-python and cytometry-r; the work completed here is dependent on both of those repositories. 

Project Goal:
To take a singular public cytometry dataset and analyze it with parallel pipelines in Python (scanpy + FlowKit) and R (CATALYST + diffcyt). Critical analysis will examine where the two analyses agree, where they diverge, and what those differences reveal about the methodological choices embedded in each ecosystem.
The output is a written analysis that will address the following questions:
- How do clustering results compare between Leiden (Python) and FlowSOM (R) on the same data?
- Where do the languages' default transformations and normalizations produce different downstream results?
- What does cross-language reproducibility look like in practice for a typical cytometry study?
- Which choices matter scientifically, and which are matters of convention?

Why This Project:
Most computational immunology analyses are conducted in a single language ecosystem, which can obscure the degree to which methodological choices shape published findings. This project examines that gap directly using a real dataset.

Planned Structure:
- A short written introduction framing the biological and methodological questions
- Parallel notebooks: one Python (Jupyter), one R (RMarkdown)
- A comparison section addressing concordance, divergence, and interpretation
- A discussion of practical implications for reproducibility in cytometry research

The full analysis will be rendered as a small website using Jupyter Book or Quarto and hosted via GitHub Pages.

Tools:
Both Python (scanpy, FlowKit, scikit-learn) and R (CATALYST, diffcyt, flowCore) stacks. Environment management via conda for Python and renv for R, with the rendering toolchain documented in the project README at completion.

Background:
I work a Resource Technologist at the University of Pennsylvania's Institute for Immunology and Immune Health. This portfolio represents independent computational work undertaken in preparation for graduate study in molecular biotechnology. 

See also:

cytometry-python ; 
cytometry-r ; 
python-r-fundamentals

License
MIT — see LICENSE file.
