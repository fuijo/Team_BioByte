# Team_BioByte

![image](https://github.com/user-attachments/assets/b977fd30-56fd-4844-b3e8-a9b8554e51b4)

**Single-Cell RNA Sequencing of Circulating Tumor Cells in Breast Cancer**

**1. Introduction**  Breast cancer remains a leading cause of cancer-related mortality, with metastasis being a critical factor in patient prognosis. Circulating tumor cells (CTCs) are pivotal in the metastatic process, interacting with peripheral blood mononuclear cells (PBMCs) to potentially influence disease progression. This study utilized single-cell RNA sequencing (scRNA-seq) to analyze the heterogeneity of CTC populations and their interactions with PBMCs, offering insights into metastatic mechanisms.

**EDA Exploratory Analysis**

**Dataset 1:**
![image](https://github.com/user-attachments/assets/68e14023-2d48-43d9-be82-5bd047c99e30)

**Dataset 2:**
![image](https://github.com/user-attachments/assets/62664b8f-5e8a-4f60-8fa4-5687427abaa0)

**Merged Dataset:**
![image](https://github.com/user-attachments/assets/3157397e-cdb4-4f5a-a3e8-9cff8412dddc)

**Some resources files during the study**
![image](https://github.com/user-attachments/assets/ae11d259-2555-4b9d-94d6-10106665e332)

**Test data and the predictions for CTC interactions**
![image](https://github.com/user-attachments/assets/0ed3b895-2983-4916-a8f3-3b6fc39982f1)

**Keras model for prediction with CTC interaction in metastasis and non-metastasis cells.**
![image](https://github.com/user-attachments/assets/f165619d-a18c-4707-9469-f43f882eff6a)
![image](https://github.com/user-attachments/assets/a50ef48a-26e6-4f6e-9427-f890ac906567)

**Linear regression for the final_merged dataset of the study**
+ Training Matrix
  ![image](https://github.com/user-attachments/assets/02587c48-5610-42a5-830f-c389f2eba33b)

+ Test Matrix
  ![image](https://github.com/user-attachments/assets/8989dfa4-8f24-4148-a946-3489c169097c)

+ Training Classification report **
  ![image](https://github.com/user-attachments/assets/57dc07d5-b07f-4498-8273-16ab0cb3b1fd)

+ Interaction of gen EPCAM with cells in the full dataset**
  ![image](https://github.com/user-attachments/assets/18a350c7-4c52-4e62-8788-df0f234bf407)

**2. Key Findings**

+ **CTC Heterogeneity:** Distinct transcriptional profiles were identified within CTC populations, revealing significant heterogeneity between metastatic and localized breast cancer samples.

+ **Differential Gene Expression:** Metastatic CTCs exhibited upregulation of genes associated with epithelial-to-mesenchymal transition (EMT), immune evasion, and survival pathways compared to localized CTCs.

+ **Immunomodulatory Mechanisms:** Analysis suggested that CTCs in metastatic cases had altered cytokine signaling pathways, potentially modulating PBMC responses and fostering an immune-suppressive microenvironment.

+ **Pathway Enrichment Analysis:** Key signaling pathways such as EPCAM were significantly enriched in metastatic CTCs, indicating their role in promoting metastasis and immune interactions.

**3. Implications for Treatment and Prognosis**

+ **Potential Biomarkers:** The distinct gene expression patterns identified in metastatic CTCs suggest potential prognostic biomarkers that could help in early detection and monitoring of disease progression.

+ **Therapeutic Targets:** Disrupting key pathways identified in metastatic CTCs, such as PI3K/AKT and TGF-β signaling, may present viable therapeutic strategies to inhibit tumor cell dissemination.

+ **Immune-based Strategies:** The findings emphasize the need for targeted immunotherapies to counteract CTC-mediated immune suppression and enhance anti-tumor immunity.

**4. Conclusion** This study provides a comprehensive analysis of CTC heterogeneity and their interactions with immune cells, shedding light on mechanisms that drive metastasis. The identification of unique transcriptional signatures and immunomodulatory pathways offers valuable insights for the development of novel prognostic markers and targeted therapies for breast cancer patients. Future research should focus on validating these findings in larger patient cohorts and exploring therapeutic interventions based on identified molecular pathways.
