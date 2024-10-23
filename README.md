**Talent Acquisition Solution using Power Platform**

Welcome to the Talent Acquisition Solution repository! This solution is designed as a Proof of Concept (POC) to showcase the capabilities of using Generative AI (Gen AI) in the talent acquisition process. Built with Microsoft Power Platform, it leverages AI Builder and Dataverse to create an intelligent, data-driven approach to managing job roles and candidates.

**Features**

1. Create Job Roles Using AI
Define and create new job roles using AI-based insights.
Utilize AI Builder to assist in the creation process, ensuring roles are well-defined and tailored to organizational needs.

3. Upload C.V. for a Specific Job Role
Easily upload candidate CVs associated with specific job roles.
The uploaded CVs are stored in Dataverse for secure and structured management.

5. Compare and Rate CVs Against Job Roles
Automatically compare and rate uploaded CVs against the predefined job roles.
AI-powered analysis provides a rating that helps hiring managers quickly assess candidate suitability.

7. Review Any CV Against Any Role
Flexibly review any candidate CV against any available job role.
This feature allows for cross-role analysis, making it easier to find alternate fits for candidates.

9. Generate Interview Questions Based on CV and Job Role
Generate custom interview questions tailored to each candidate, considering their CV content and the requirements of the job role.
Helps interviewers focus on key areas and ensures relevant, role-specific questions.

11. Document Extraction Using AI Builder
The solution also uses the Document Extraction AI Builder model to extract relevant information from candidate documents, such as CVs and invoices.
Automatically pulls out key details from uploaded documents for further analysis and storage in Dataverse.

**POC Purpose**

This solution is meant to serve as a Proof of Concept (POC) to demonstrate the potential of Generative AI in streamlining and enhancing the talent acquisition process. While it currently uses Dataverse as the primary data source, it can be easily customized to work with any other data source supported by Power Platform, such as SQL Server, SharePoint, or external APIs.

**Technology Stack**
Power Platform Components

Power Apps: User interface for job role creation, CV management, and reviewing/rating CVs.

Dataverse: Stores job roles, CVs, and associated data in a structured format (can be replaced with other data sources).

AI Builder:
Used for generating job roles and CV ratings.
Utilized for extracting key details from candidate documents using the Document Extraction model.

**AI Features**
AI Builder Prompts: Leverages generative AI capabilities to create job roles, compare CVs, and generate interview questions.

Document Extraction Model: Extracts relevant content from documents (such as CVs and invoices) for structured data storage.

**Prerequisites**

To deploy and run this solution, ensure the following:

A Power Platform environment with access to Dataverse (or an alternative data source).

Necessary AI Builder credits for using AI features like document extraction and generative AI.

Access to the Document Extraction AI Builder Model and AI Builder Prompt functionalities.

**Setup and Deployment**

**Clone the Repository**
Clone this repository to your local environment:

git clone https://github.com/jonhart_microsoft/talent-acquisition-solution.git

Import Power Platform Solution

Open Power Apps and navigate to your environment.
Import the solution ZIP file from the repository.
Ensure the necessary connections (Dataverse, AI Builder) are correctly configured during import.
Configure AI Builder Models

Set up AI Builder models in your Power Platform environment:
AI Builder Prompt: Configure the prompts for job role creation and CV comparison.
Document Extraction Model: Ensure the model is linked for processing CVs and extracting content.
Run the Solution

Once the solution is imported, you can start by creating job roles, uploading CVs, and leveraging AI to automate the hiring process.
Usage
Navigate to the Job Role creation section to define new roles.
Upload CVs in the CV Management section.
Review, compare, and rate CVs using the Compare and Rate feature.
Generate custom interview questions for each candidate based on their CV and the selected job role.
Contributions
Contributions are welcome! Please submit a pull request with any features, bug fixes, or enhancements you'd like to see in the solution.

License
This project is licensed under the MIT License - see the LICENSE file for details.
