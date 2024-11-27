# Building an Expert System to Guide Diagnosis and Management of Rhinossinusitis
**by Antonia Angeli Gazola as part of her Master in Biomedical Informatics studies at the University of Pennsylvania**  

- **Course:** BMIN 5200-001 202430 Foundations Of Artificial Intelligence In Health
- **Course Professor:** Prof. Dr. Joseph Daniel Romano

This repository contains the work associated with my final project for the **5200 AI** course as part of the **Master's in Biomedical Informatics** program at the **Perelman School of Medicine**, **University of Pennsylvania**. The project focuses on building an expert system to guide diagnosis and management of rhinossinusitis in clinical practice.

### Project Overview

During this project, a detailed expert system will be developed using CLIPS.py. The proposed expert system for this project will use clinical guidelines from IDSA and AAO-HNS with data from a clinical case provided by the clinical provider, such as symptoms, presentation duration, and clinical findings and conclusions. The system will assist in distinguishing rhinosinusitis from upper respiratory viral infections, differentiating viral from bacterial rhinosinusitis, and classifying cases as acute, subacute, or chronic. Moreover, it will provide evidence-based management recommendations, considering potential complications and the need for hospitalization or referrals. The aim is for the developed tool to diminish diagnostic variability and antibiotic overprescription, providing standardized assistance, that potentially helps to improve patient outcomes.

The project's report is being written using LaTeX, through OverLeaf, using the AMIA paper template, containing the following structure: background, introduction, materials and methods, design, demonstration, discussion, conclusion, acknowledgements and references.

### Repository Overview

This repository includes:

- **README.md**: overview of the project and repository contents.  
- **5200_step1.drawio and 5200_step1.png**: Flow Diagram with the first steps used to build the expert system, until diagnosis of Acute Bacterial Rhinosinusitis.
- **5200_step2.drawio and 5200_step2.png**: Flow Diagram with the following steps used to build the expert system, from diagnosis of Acute Bacterial Rhinosinusitis to providing treatment recommendations.
- **rhinossinusitis-4.drawio and rhinossinusitis-4.png**: initial flow diagram created, searving as the first draft of the decision track expert system.
- **references.bib**: bib file with the references used to write the LaTeX report.
- **Expert_system_project_ANTONIA** (jupyter notebook folder)
-- **final_project_demo_Antonia.ipynb**: jupyter notebook with the expert system, written with CLIPS.py.
-- **src**:  folder containing some utility documents to ensure the expert system runs smootly.

### Next Steps

- Refine project report draft,
- Reach a final version of the project.
- Create project presentation slides
- **Final Submission:** The completed project will be uploaded to this repository by **12/11/24** (due date).

### Instructions for Running the Expert System

To view and run the expert system locally, follow these instructions:

1. Install **Anaconda/Jupyter Notebooks, python and CLIPS** on your system. Follow the installation instructions on the [Jupyter website](https://docs.jupyter.org/en/latest/install/notebook-classic.html) and [CLIPS website](https://www.clipsrules.net).
2. Download the files in the **Expert_system_project_ANTONIA** folder from here or clone this repository to your local computer using Git and then download the files.
3. Open Jupyter notebooks, through Anaconda, and create a new folder.
4. Add the downloaded files into that new folder.
5. From there, open the **final_project_demo_Antonia.ipynb** and run it to see the system working.
