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

### :keyboard: Activity: Your first branch

1. Open a new browser tab and navigate to your newly made repository. Then, work on the steps in your second tab while you read the instructions in this tab.
2. Navigate to the **< > Code** tab in the header menu of your repository.

   ![code-tab](/images/code-tab.png)

3. Click on the **main** branch drop-down.

   ![main-branch-dropdown](/images/main-branch-dropdown.png)

4. In the field, name your branch `my-first-branch`. In this case, the name must be `my-first-branch` to trigger the course workflow.
5. Click **Create branch: my-first-branch** to create your branch.

   ![create-branch-button](/images/create-branch-button.png)

   The branch will automatically switch to the one you have just created.
   The **main** branch drop-down bar will reflect your new branch and display the new branch name.

6. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
