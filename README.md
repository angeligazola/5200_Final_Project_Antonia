# Building an Expert System to Guide Diagnosis and Management of Rhinossinusitis
**by Antonia Angeli Gazola as part of her Master in Biomedical Informatics studies at the University of Pennsylvania**  

- **Course:** BMIN 5200-001 202430 Foundations Of Artificial Intelligence In Health
- **Course Professor:** Prof. Dr. Joseph Daniel Romano

This repository contains the work associated with my final project for the **5200 AI** course as part of the **Master's in Biomedical Informatics** program at the **Perelman School of Medicine**, **University of Pennsylvania**. The project focuses on building an expert system to guide diagnosis and management of rhinossinusitis in clinical practice.

### Project Overview

During this project, a detailed expert system was developed using CLIPS.py. The proposed expert system for this project uses clinical guidelines from IDSA and AAO-HNS with data from a clinical case provided by the clinical provider, such as symptoms, presentation duration, and clinical findings and conclusions. The system assists in distinguishing rhinosinusitis from upper respiratory viral infections, differentiating viral from bacterial rhinosinusitis, and classifying cases as acute, subacute, or chronic. Moreover, it will provide evidence-based management recommendations, considering potential complications and the need for hospitalization or referrals. The aim is for the developed tool to diminish diagnostic variability and antibiotic overprescription, providing standardized assistance, that potentially helps to improve patient outcomes.

The code was tested in a Jupyter Notebook, in Anaconda, using Python 3.12.4 (packaged by Anaconda, Inc.).
The project's report was written using LaTeX, through OverLeaf, using the AMIA paper template, containing the following structure: background, introduction, materials and methods, design, demonstration, discussion and conclusion, acknowledgements and references.

### Repository Overview

This repository includes:

- **Expert_system_project_ANTONIA** (files included in the original jupyter notebook folder to ensure the expert system runs as expected):  
	- **5200_step1.png**: Flow Diagram with the first steps used to build the expert system, until diagnosis of Acute Bacterial Rhinosinusitis, or subacute in need of acute management (added to the notebook for reference);
	- **5200_step2.png**: Flow Diagram with the following steps used to build the expert system, from diagnosis of Acute Bacterial Rhinosinusitis, or subacute in need of acute management, to providing treatment recommendations (added to the notebook for reference).
	- **final_project_Antonia_ANGELIGAZOLA.ipynb**: jupyter notebook with the expert system code, written with CLIPS.py;
	- **clips_util.py, \__init__\.py and util.cpython-312.pyc**: files to ensure the expert system runs as expected in the clips.py environment created.
- **README.md**: overview of the project and repository contents;
- **5200_step1.drawio**: the draw.io draft of the Flow Diagram with the first steps used to build the expert system, until diagnosis of Acute Bacterial Rhinosinusitis, or subacute in need of acute management;
- **5200_step2.drawio**: the draw.io draft of the Flow Diagram with the following steps used to build the expert system, from diagnosis of Acute Bacterial Rhinosinusitis, or subacute in need of acute management, to providing treatment recommendations;
- **BMIN_5200_Final_Project_Antonia_ANGELIGAZOLA.pdf**: Final Project Report pdf, written with LaTeX, via Overleaf, and rendered into a pdf file;
- **Figure3_output_examples.png**: Figure containing four output examples from the expert system, used in the report;
- **output_examples.pptx**: examples of all combinations of outputs from the expert system;
- **references.bib**: bib file with the references used to write the LaTeX report;
- **rhinossinusitis-4.drawio and rhinossinusitis-4.png**: initial flow diagram draft created, serving as the first draft of the decision track expert system.


### Instructions for Running the Expert System

To view and run the expert system locally, follow these instructions:

1. Install **Anaconda/Jupyter Notebooks, python and CLIPS** on your system. Follow the installation instructions on the [Jupyter website](https://docs.jupyter.org/en/latest/install/notebook-classic.html) and [CLIPS website](https://www.clipsrules.net).
2. Download the files in the **Expert_system_project_ANTONIA** folder from here or clone this repository to your local computer using Git and then download the files.
3. Open Jupyter notebooks, through Anaconda, and create a new folder.
4. Add the downloaded files into that new folder.
5. From there, open the **final_project_Antonia_ANGELIGAZOLA.ipynb** and run it to see the system working.
