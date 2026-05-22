# STAR — Strategic Targeting & Alliance Resource

**AWS Workflow Automation Case Study**  
Chrome Extension | Amazon Bedrock | Claude 3 Haiku | API Gateway | AWS Lambda | Amazon SES | Amazon Cognito | Amazon Q Developer

STAR is a workflow automation project I built during my internship at Amazon Web Services (AWS). It was designed to reduce the manual effort required in partner engagement workflows by helping users process partner data, prioritize stakeholders, and generate personalized outreach more efficiently.

> Note: This repository is a public case study. Internal code, credentials, private architecture details, stakeholder names, and proprietary implementation information are not included.

---

## Overview

Partner outreach workflows often require users to manually review data files, cross-reference account information, identify the right stakeholders, and draft tailored messages. This process can be repetitive, time-consuming, and difficult to scale across multiple partner relationships.

STAR was built as a Chrome extension to streamline that process through AWS services and generative AI. The tool helped automate multiple manual workflows while still allowing users to review, edit, and control the final output.

---

## Problem

Before STAR, partner outreach preparation involved several manual steps:

- Reviewing partner customer data files
- Cross-referencing account-mapping information
- Identifying relevant AWS stakeholders
- Prioritizing outreach targets
- Drafting personalized partner engagement messages
- Repeating similar steps across multiple partners and workflows

This created a workflow that could take hours and limited the amount of time users could spend on higher-value partner strategy.

---

## What I Built

I built STAR as a Chrome extension that supported AI-assisted partner outreach workflows.

At a high level, STAR allowed users to:

1. Select a configured workflow
2. Provide required partner and account inputs
3. Process the information through a secure AWS-based workflow
4. Generate structured outreach content using Claude 3 Haiku through Amazon Bedrock
5. Review and edit the generated output
6. Use the final content for partner engagement

---

## My Role

My role combined software development, AWS service configuration, prompt logic, workflow design, testing, documentation, and stakeholder collaboration.

I worked on:

- Chrome extension setup and workflow design
- Amazon API Gateway integration
- AWS Lambda service configuration
- Amazon Cognito / MFA authentication setup
- Amazon SES email workflow configuration
- Claude 3 Haiku prompt logic through Amazon Bedrock
- Structured prompt output design
- Testing materials comparing STAR outputs against manual use cases
- Architecture diagrams and AWS console setup documentation
- Stakeholder demos, feedback summaries, and handoff materials

---

## Tech Stack

### Cloud & APIs
- AWS
- Amazon API Gateway
- AWS Lambda
- Amazon Cognito
- Amazon SES
- Amazon Bedrock
- REST APIs

### Generative AI
- Claude 3 Haiku
- Prompt logic design
- Structured AI output generation
- AI-assisted workflow automation

### Development & Tools
- Chrome Extension
- JavaScript
- VS Code
- Amazon Q Developer
- Technical documentation
- Architecture diagrams

---

## Claude 3 Haiku / Amazon Bedrock Usage

STAR used **Claude 3 Haiku through Amazon Bedrock** to generate personalized partner engagement content.

My work focused on designing the prompt logic so that the output followed a consistent structure while still adapting specific sections based on the user’s inputs. This helped make the generated content more standardized, reviewable, and useful for real partner outreach workflows.

The prompt logic supported:

- Standardized message structure
- Input-driven personalization
- Partner-specific context
- Clear outreach language
- Editable final output for user review

---

## Amazon Q Developer Usage

I used **Amazon Q Developer in VS Code** to support AI-assisted development. This included using Amazon Q Developer to help:

- Write code
- Debug issues
- Explain code behavior
- Improve implementation logic
- Accelerate troubleshooting during development

I treated Amazon Q Developer as a development assistant, while still reviewing and validating the work myself.

---

## Impact

STAR demonstrated measurable business and workflow impact:

- Automated **2+ manual partner outreach workflows**
- Reduced repetitive outreach preparation time by up to **97%**
- Reduced a process that could take **5–10 hours** to approximately **15 minutes**
- Enabled users to generate multiple personalized outreach messages more efficiently
- Engaged **33+ stakeholder contributors** during feedback and validation
- Supported **10+ live demos**
- Presented at the **2025 AWS Global AI Solutions Expo**
- Recognized with an innovation award

---

## Documentation & Handoff Materials

To make the project easier to understand, maintain, and transition, I created several handoff-ready materials:

- Architecture diagrams
- AWS console setup guides
- Demo materials
- Stakeholder feedback summaries
- Testing materials
- “Next Steps” roadmap
- Workflow documentation

These materials helped communicate how STAR worked, what it solved, and what would be needed for long-term ownership.

---

## What I Learned

This project strengthened my experience in:

- Building workflow automation tools
- Working with AWS services
- Designing AI-assisted workflows
- Structuring prompts for consistent outputs
- Integrating cloud services through APIs
- Testing automated outputs against manual processes
- Using AI-assisted development tools responsibly
- Documenting technical systems clearly
- Translating stakeholder needs into product and technical requirements

It also reinforced how much I enjoy building tools that reduce manual work and make complex workflows easier to understand and use.

---

## Confidentiality Note

This was a professional AWS internship project. To protect confidentiality, this repository does not include:

- Internal source code
- Credentials
- API keys
- Private AWS account details
- Internal architecture diagrams
- Proprietary implementation details
- Stakeholder names
- Internal screenshots
- Private business data

This repository is intended to communicate the project’s purpose, tools, technical approach, and impact at a high level.

---

## Repository Status

This repository is currently a public case study. Future updates may include:

- Sanitized diagrams
- A simplified mock workflow
- Public technical documentation
- Example prompt structures with fake/sample data
- A non-confidential demo concept
