# diabetes-readmission-prediction
Understanding Readmission Risks: An Explainable Framework for Predicting Outcomes in Diabetes Care


## Understanding Readmission Risks: An Explainable Framework for Predicting Outcomes in Diabetes Care

**Project for AMIA 2025 Annual Symposium**

**Team Members:**

*   Devavrat Singh Bisht ([dkbisht@ucdavis.edu](mailto:dkbisht@ucdavis.edu))
*   Pranav Gupta ([pgpt@ucdavis.edu](mailto:pgpt@ucdavis.edu))
*   Sanchit Kaul ([skkaul@ucdavis.edu](mailto:skkaul@ucdavis.edu))
*   Prabhu Rv Shankar(PI) ([rvpshankar@ucdavis.edu](mailto:rvpshankar@ucdavis.edu))

## Table of Contents

1.  [Project Overview](#project-overview)
2.  [Research Proposal](#research-proposal)
3.  [Datasets](#datasets)
4.  [Timeline and Milestones](#timeline-and-milestones)
5.  [Technology Stack](#technology-stack)
6.  [Getting Started](#getting-started)
7.  [Contributing](#contributing)
8.  [License](#license)
9.  [Contact](#contact)
10. [Statistics](#statistics)

## Project Overview

This project aims to develop an explainable AI model to predict the risk of hospital readmission for patients with diabetes. We will be leveraging large-scale datasets, including the AI-READI and UC Irvine Diabetes datasets, to build and validate our model. The project is intended for submission to the AMIA 2025 Annual Symposium.

## Research Proposal

The detailed research proposal, including the problem statement, background, significance, research questions, hypotheses, methods, and literature review, can be found in the `proposal` directory: [Proposal Document](proposal/MHI_289H_Project_Proposal.md)

Here are some key highlights from the proposal:

**Problem Statement:**

How can machine learning (ML) models be used to effectively predict and reduce the number of patients at high risk of hospital readmission? How can we explain the contribution of the features towards the risk prediction?

**Research Questions:**

*   How well can we predict the likelihood of readmission of a patient within 30 days?
*   What are the key demographic and clinical factors that significantly help in predicting the likelihood of readmission within 30 days for diabetic patients?

**Hypotheses:**

*   **Null Hypothesis (H0):** Predictive analytics through ML does not have a significant influence in improving the accuracy of predicting readmission risks predictions over traditional risk models.
*   **Alternative Hypothesis (H1):** Predictive analytics through machine learning does have a significant influence in improving the accuracy of predicting readmission risks predictions over traditional risk models.

## Datasets

We will be primarily using the following datasets:

1.  **AI-READI:**
    *   Link: [https://fairhub.io/datasets/2](https://fairhub.io/datasets/2)
    *   Size: 1.873 TB
    *   Will be stored in Google Drive due to its size. [Link to data in GDrive](link-to-gdrive-folder) (to be added once uploaded).
2.  **UC Irvine Diabetes 130-US Hospitals (1999-2008):**
    *   Link: [https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for-years+1999-2008](https://archive.ics.uci.edu/dataset/296/diabetes+130-us-hospitals+for-years+1999-2008)
    *   Smaller dataset, can be directly downloaded and used.

**Old Project (MHI\_0001) Data and Files:**

*   MHI289 Class project files: [https://drive.google.com/drive/folders/1s8T3ifhd-qsk0-FVMUj4mKFqmQ-IENZe?usp=drive\_link](https://drive.google.com/drive/folders/1s8T3ifhd-qsk0-FVMUj4mKFqmQ-IENZe?usp=drive_link)

## Timeline and Milestones

| Task                               | Deadline           | Status       |
| :--------------------------------- | :----------------- | :----------- |
| Initial Project Setup                | December 19, 2023   | Completed    |
| Data Acquisition (AI-READI)         | December 25, 2023   | To Do        |
| Data Preprocessing & Exploration    | January 15, 2024   | To Do        |
| First Batch of Model Results       | January 30, 2024    | To Do        |
| First Draft of Paper               | February 15, 2024   | To Do        |
| Proposal Submission                 | March 10, 2024      | To Do        |

## Technology Stack

*   **Cloud Platform:** Google Cloud Platform (GCP)
*   **Compute:** Colab Pro+ (for GPU access)
*   **Storage:** Google Cloud Storage
*   **Programming Language:** Python
*   **Libraries:** TensorFlow, Keras, Scikit-learn, Pandas, NumPy, SHAP/LIME (for explainability)
*   **Version Control:** Git and GitHub

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [invalid URL removed]
    cd AMIA_DiabetesAI_Research
    ```
2.  **Set up your GCP environment:**
    *   Create a GCP project.
    *   Enable billing for your project.
    *   Set up a virtual machine (if needed).
    *   Create a Google Cloud Storage bucket for data storage.
3.  **Set up Colab Pro+:**
    *   Subscribe to Colab Pro+ for enhanced GPU resources.
4.  **Install necessary libraries:**
    ```bash
    pip install -r requirements.txt
    ```

## Contributing

We welcome contributions from all team members! Please follow these guidelines:

1.  **Branching:** Create a new branch for each feature or bug fix:

    ```bash
    git checkout -b feature/your-feature-name
    ```
2.  **Committing:** Make clear and concise commit messages:

    ```bash
    git commit -m "Add: Initial data loading code"
    ```
3.  **Pull Requests:** Submit pull requests to merge your changes into the `main` branch. Please provide a detailed description of your changes in the pull request.
4.  **Code Style:** Follow PEP 8 style guidelines for Python code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or concerns, please reach out to the project lead:

*   Prabhu Shankar (contact information to be added)

## Statistics

### Race

*   **According to the U.S. Census Bureau (2023), the racial composition of the United States is:**
    *   White: 58.9% (Not Hispanic or Latino)
    *   Hispanic or Latino: 19.1%
    *   Black or African American: 13.6%
    *   Asian: 6.3%
    *   American Indian and Alaska Native: 1.3%
    *   Native Hawaiian and Other Pacific Islander: 0.3%
    *   Two or More Races: 10.2%
*   **Diabetes Prevalence by Race/Ethnicity (CDC, 2022):**
    *   American Indians/Alaska Natives: 14.5%
    *   Non-Hispanic Blacks: 12.1%
    *   Hispanics: 11.8%
    *   Non-Hispanic Asians: 9.5%
    *   Non-Hispanic Whites: 7.4%

### Gender

*   **U.S. Population by Gender (U.S. Census Bureau, 2023):**
    *   Female: 50.5%
    *   Male: 49.5%
*   **Diabetes Prevalence by Gender (CDC, 2022):**
    *   Men: 15.3%
    *   Women: 11.7%

### Age

*   **U.S. Population by Age Group (U.S. Census Bureau, 2023):**
    *   Under 18 years: 22.8%
    *   18 to 64 years: 60.2%
    *   65 years and over: 17.0%
*   **Diabetes Prevalence by Age (CDC, 2022):**
    *   18-44 years: 4.3%
    *   45-64 years: 15.6%
    *   65 years and over: 29.2%

### Weight

*   **Obesity Prevalence in U.S. Adults (CDC, 2023):**
    *   Overall: 41.9%
    *   Non-Hispanic Black adults: 49.9%
    *   Hispanic adults: 45.6%
    *   Non-Hispanic White adults: 41.4%
    *   Non-Hispanic Asian adults: 16.1%

### Readmission Rates

*   **National Average Readmission Rate (all conditions, CMS, 2022):** 15.0%
*   **Diabetes-Related Readmission Rate (various studies):** 14% to 22%

**Note:** The above statistics are from various sources and may have different methodologies and timeframes. For the most up-to-date and specific data, please refer to the original sources cited.
