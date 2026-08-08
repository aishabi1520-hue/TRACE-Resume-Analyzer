# TRACE – Transparent Resume Alignment and Coverage Engine

## Overview

TRACE is a rule-based Resume Requirement Coverage System developed using Python.

The system compares a Job Description with a Candidate Resume and determines how well the candidate satisfies the requirements.

Unlike a simple keyword matching system, TRACE creates a Requirement Coverage Map that explains:

- Which requirements are satisfied
- Which requirements are missing
- Which requirements are exceeded
- The priority of each requirement
- Evidence found in the resume
- The overall candidate score
- The final recommendation

## Problem

Recruiters receive many resumes for a job position and manually compare each resume with the Job Description.

This process takes time and can lead to inconsistent evaluation.

## Proposed Solution

TRACE automatically analyzes the Job Description and Resume using a rule-based approach.

### Process

Job Description
→ Requirement Extraction
→ Priority Classification
→ Resume Analysis
→ Evidence Matching
→ Requirement Coverage
→ Weighted Scoring
→ Recommendation

## Main Features

- Job Description analysis
- Resume analysis
- Skill matching
- Mandatory/Preferred/Optional classification
- Evidence matching
- Experience comparison
- Weighted scoring
- Missing requirement identification
- Requirement Coverage Map
- Candidate recommendation
- Simple graphical interface

## Technology

Python

Tkinter is used for the graphical user interface.

## Restrictions

The project does not use:

- External AI APIs
- LLM APIs
- Third-party resume analysis APIs
- Machine learning models
- External Python analysis packages

The analysis is implemented using Python's built-in functionality and rule-based algorithms.

## How to Run

Make sure Python 3 is installed.

Run:

    python trace_resume_analyzer.py

The application will open a graphical interface.

Enter the Job Description and Resume and click:

ANALYZE RESUME

## Output

The system generates:

- Requirement status
- Priority
- Evidence
- Requirement score
- Overall score
- Recommendation
- Missing requirements
- Matched requirements