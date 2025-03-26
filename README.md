<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# InstantCare: A Telemedicine Diagnostic Tool

Welcome to the Telemedicine Diagnostic Tool project! This repository contains a student-level data science project designed to help users quickly assess their symptoms and receive preliminary diagnostic insights along with recommendations and precautionary measures. This project was built to showcase technical process, insights, and recommendations in a clear and compelling format.

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Project Background

This project was developed as part of a data analytics portfolio to demonstrate how to apply machine learning to healthcare diagnostics. The Telemedicine Diagnostic Tool uses user-input symptoms to predict possible diseases and provide personalized recommendations.

Key Points:

	•	Industry: Healthcare / Telemedicine
 
	•	Business Model: Online diagnostic tool supporting remote consultations
 
	•	Project Goals:
 
		•	Quickly capture user symptoms
  
		•	Provide clear diagnostic predictions with confidence scores
  
		•	Offer actionable precautionary measures and personalized recommendations

  

 
## Data Structure & Initial Checks

The primary data used in this project comes from multiple CSV files:

	•	Training.csv & Testing.csv: Contain symptom features and prognosis labels for supervised learning.
 
	•	symptom_Description.csv: Provides detailed descriptions for various diseases.

	•	symptom_severity.csv: Contains severity scores for symptoms.
 
	•	symptom_precaution.csv: Lists precautionary measures for each disease.
 

The main database consists of:

	•	Symptoms Table: Binary and user-rated severity for various symptoms.
 
	•	Prognosis Label: The predicted disease based on the symptom vector.
 

An Entity Relationship Diagram (ERD) of the data structure is available in the repository.

## Executive Summary

### Overview of Findings

After rigorous data cleaning and model tuning, the Telemedicine Diagnostic Tool is able to:

	•	Accurately predict a set of potential diseases based on user-reported symptoms.
 
	•	Display the top three disease predictions along with descriptions and confidence scores.

	•	Provide personalized recommendations and precautionary measures tailored to the user’s inputs.
 

### Key Takeaway:
A healthcare stakeholder (e.g., a remote consultation service provider) can leverage this tool to quickly triage patient symptoms and advise on next steps, improving patient engagement and reducing unnecessary hospital visits.

</footer>
