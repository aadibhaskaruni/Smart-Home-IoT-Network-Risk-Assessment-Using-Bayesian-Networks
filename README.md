# Smart-Home-IoT-Network-Risk-Assessment-Using-Bayesian-Networks
A Python implementation demonstrating the methodology for assessing security risks in a Smart Home IoT network using a Bayesian Network (BN), based on the research paper: "Smart Home IoT Network Risk Assessment Using Bayesian Networks"

# Smart Home IoT Risk Assessment using Bayesian Networks (CMD Implementation) 🏠💻

This repository contains a simplified, demonstrative implementation of the risk assessment methodology proposed in the research paper:

**"Smart Home IoT Network Risk Assessment Using Bayesian Networks"**
*Authors: Miguel Flores, Diego Heredia, Roberto Andrade, and Mariam Ibrahim*
*Publication: Entropy 2022, 24, 668*

## 📚 Overview

The project models the probabilistic dependencies between cyber attacks in a smart home environment using a **Bayesian Network (BN)** and quantifies the final risk ($Risk = Probability \times Impact$) for target attacks (DoS, MitM).

This implementation uses the `pgmpy` library to demonstrate key steps:
1.  **Defining the Network Structure** (DAG).
2.  **Simulating Attack Data** (to address data scarcity).
3.  **Learning Parameters** (CPTs) using Maximum Likelihood Estimation.
4.  **Performing Inference** to get attack probabilities.
5.  **Quantifying Risk** and comparing mitigation priorities.

## ▶️ Getting Started

### Prerequisites

* Python 3.x
* The `requirements.txt` file lists all necessary packages.

### Installation and Execution

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/aadibhaskaruni/Smart-Home-IoT-Network-Risk-Assessment-Using-Bayesian-Networks.git](https://github.com/aadibhaskaruni/Smart-Home-IoT-Network-Risk-Assessment-Using-Bayesian-Networks.git)
    cd Smart-Home-IoT-Network-Risk-Assessment-Using-Bayesian-Networks
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the analysis:**
    You can open the notebook to view the code, output, and visualizations:
    ```bash
    jupyter notebook iot_risk_assessment.ipynb
    ```



    # Reference Paper
**Reference Paper Link - https://www.mdpi.com/1099-4300/24/5/668** 

   # View Presentation  
**View Here / Download - https://github.com/aadibhaskaruni/Smart-Home-IoT-Network-Risk-Assessment-Using-Bayesian-Networks/raw/refs/heads/main/Smart-Home-IoT-Network-Risk-Assessment-Using-Bayesian-Networks.pptx**
