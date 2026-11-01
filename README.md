# Urban Mart – AI-Powered Customer Feedback Intelligence System

## Project Overview

An AI-powered customer feedback analysis and complaint management system built using **n8n, Google Gemini, Google Sheets, and Gmail**.

The system analyses customer feedback to identify recurring issues, detect emerging trends and anomalies, and generate actionable recommendations to improve customer experience and business operations.

Rather than simply collecting complaints, the system uses multiple AI agents to investigate feedback, identify supporting evidence, evaluate recommendations, and prepare reports for management review.

## Key Features

- **Automated Feedback Classification:** Categorises incoming customer feedback and complaints.
- **Trend & Pattern Analysis:** Identifies recurring customer concerns and patterns over time.
- **Anomaly Detection:** Detects unusual changes or spikes in customer complaints and feedback.
- **Evidence-Based Recommendations:** Generates improvement suggestions supported by actual customer feedback.
- **Complaint Investigation:** Retrieves relevant feedback records to provide supporting evidence for identified problems.
- **AI Quality Assurance:** Validates recommendations and checks evidence integrity.
- **Management Reporting:** Generates structured reports with findings and recommendations.
- **Human Approval Workflow:** Sends reports for management approval and tracks approval decisions.

## AI Agent Architecture

The workflow uses six specialised AI agents:

1. Classification Agent
2. Trend and Pattern Analyst
3. Emerging Trend and Anomaly Agent
4. Recommendation Agent
5. Guardrail / Quality Assurance Agent
6. Management Report Writer

Each agent handles a specialised task within the feedback analysis process.

## Technologies Used

- n8n – Workflow automation
- Google Gemini – AI-powered analysis
- Google Sheets – Feedback storage and tracking
- Gmail – Management report and approval communication
- JavaScript – Data processing and workflow logic

## Repository Contents

- `urban-mart-workflow.json` – Exported n8n workflow.
- `project-report.pdf` – Project documentation.
- `screenshots/` – Workflow architecture.

## Setup

1. Download the workflow JSON file.
2. Open your n8n instance.
3. Import the workflow from the downloaded JSON file.
4. Configure your Google Gemini, Google Sheets, and Gmail credentials.
5. Connect the required Google Sheets and configure the relevant data sources.
6. Test the workflow using sample feedback before running it with live data.

**Note:** API credentials, Google account connections, and external integrations must be configured separately.

## Project Goal

To help Urban Mart transform customer feedback into meaningful business insights through AI-powered analysis, evidence-backed recommendations, proactive issue detection, and structured management decision-making.
