# Analyzing the Stability of Coal Supply Chain
This repository documents the data extraction and financial tail risk modeling processes associated with the Master's thesis **"Analyzing the Stability of Coal Supply Chain"** by **Yueni** and **Ying**, submitted in partial fulfillment of the requirements for the Master of Science in Statistics and Data Science at KU Leuven.
This work aims at studying the financial impact on India’s coal supply chain, with the fo-
cus on asset-, firm-, and portfolio- level under extreme flood events using the P-RISK
framework with an agent-based model extension developed by the working paper of
Kerkhofs et al.. The main contribution of the work is the construction of India’s
coal supply chain network using the public data from Global Energy Monitor (GEM), and analyzing the financial tail-risk and impact of several firm structural character-
istics by Quantile Regression and validated by the LightGBM algorithm.
## 📁 Repository Structure
The repository is organized into the following main components:


- **`Data Folder/`**  
  Includes raw and processed datasets used throughout the project.  
  
  - The sub-folder **`new coal/`** contains the updated version of coal project data from *Global Energy Monitor (GEM)*.  
  - The files **`agg_asset_results`** and **`agg_firm_results`** are flood simulation datasets provided by co-supervisor **Ruben**.  
  - Other files represent intermediate datasets used in subsequent analyses.

- **`Preprocessing Codes Folder/`**  
  Contains code for data extraction and NLP processes, ownership tree construction, supply chain network building and other preparation prior to analysis.  
  - ⚠️ *Note: The files* `Modification 1`, `Modification 2`, *and* `Modification 3` *are included for reference only with the purpose of obtaining the data *coal_supply_chain_india_updated2* and are not executable.*

- **`Descriptive_Analysis.ipynb/`**  
  Scripts and results for initial data exploration and statistical summary of financial impact on asset, firm and portfolio level.

- **`Main Analysis.ipynb/`**  
  Contains the core modeling files, including tail risk modeling and stability analysis of the coal supply chain using classic quantile regression and LightGBM quantile regression.

## 📢 AI Assistance Disclosure

Portions of this codebase were generated or significantly assisted by Generative AI tools (e.g., ChatGPT). 

### Areas of AI Contribution:
- Function scaffolding and documentation
- Refactoring suggestions
- Model building logic 
- Exception handling and error messages
- Unit test generation

Generated code has been reviewed, tested, and integrated by the authors.

Citation:
> OpenAI. (2025). ChatGPT (GPT-4). https://openai.com/chatgpt