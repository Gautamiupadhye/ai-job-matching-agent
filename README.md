# AI Job Matching and Career Intelligence Agent

## Overview
An AI-powered job matching agent built using n8n, GPT-5-mini, the Himalayas Jobs API, and Gmail. It analyzes job postings against a candidate profile, estimates match scores, identifies skill gaps, and sends email notifications.

## Features
- Fetches software engineering job postings.
- Analyzes job descriptions using AI.
- Calculates job-match percentages.
- Sends alerts for jobs scoring 85% or higher.
- Reports missing skills for lower-scoring jobs.
- Sends email notifications through Gmail.

## Technologies
- n8n Cloud
- GPT-5-mini
- Himalayas Jobs API
- Gmail
- JSON

## Workflow
1. Load the candidate profile.
2. Fetch job postings.
3. Filter and limit job results.
4. Analyze each job using AI.
5. Separate jobs based on the 85% match threshold.
6. Send job alerts or skill-gap reports by email.

## Setup
1. Import `job-matching-agent.json` into n8n.
2. Configure your candidate profile.
3. Connect your own Gmail credentials.
4. Configure any required API settings.
5. Run the workflow and review the results.

## Security
Never upload API keys, passwords, access tokens, or private candidate information.

## Disclaimer
AI-generated match scores are estimates and should be reviewed before applying.
