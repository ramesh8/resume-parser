# Project : Resume Parser

## Task:

Create Training Data for Spacy Named Entity Recognition Model (Resume Parsing),
use any open source Data Labeling / Annotator Tool ⁉ (e.g. Label Studio).

## Goals:

1.  - Training Data should have atleast 5 Labels
    - Each label should have 50-100 Samples
    - i.e. 50-100 resumes with 5 labels annotated

2.  Following Labels are recommended (pick any 5):

    - Name of the candidate (resume_name) (⭐mandatory)
    - Email (resume_email)
    - Phone (resume_phone)
    - Address (resume_address)
    - Education (resume_education)
    - Skills (resume_skill)
    - Projects (resume_project)
    - Experience (resume_experience)
    - Certifications (resume_certification)

Note:

1.  Training Data Format should be json and as specified in given sample (files/entities.json).

2.  You can use given excel file (files/resume.zip) or use kaggle.com to download other resume datasets.

3.  Please pick your data labeling / annotation tool and dataset wisely. Any issues with picked tool and dataset will not be accepted as an excuse for non-completion of the project.
