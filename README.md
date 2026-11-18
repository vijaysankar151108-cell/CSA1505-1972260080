# AI-Powered Student Performance Analytics System

**Course:** Cloud Computing and Big Data Analytics (CSA15)  
**Assessment:** CO1 – Assessment Tool 1  
**Student:** Vijay Sankar D  
**Register Number:** 1972260080  
**Department:** B.Tech CSE-AI  
**Academic Year / Semester:** 2026–2030 / 2  
**Faculty:** Antony joseph Rajan

## Project overview
A proposed cloud-based student performance analytics application. It organizes authorized academic records, provides dashboards, generates reports and uses an AI/ML module to estimate academic risk. Predictions are decision-support signals and must not replace faculty judgement.

## Tools used
- diagrams.net / draw.io editable diagram source (`.drawio`)
- PNG exports for diagram evidence
- Microsoft Word-compatible DOCX and PDF report
- Cloud architecture concepts: PaaS, DBaaS, STaaS, IDaaS, FaaS, REST APIs, virtualization, elasticity and monitoring

## Repository structure
```text
CSA15_CO1_AT1_1972260080/
├── README.md
├── CSA15_CO1_AT1_1972260080_Report.docx
├── CSA15_CO1_AT1_1972260080_Report.pdf
├── CSA15_CO1_AT1_1972260080_Concept_Maps.drawio
└── diagrams/
    ├── concept_map_1_fundamentals.png
    ├── concept_map_2_evolution.png
    ├── concept_map_3_service_models.png
    ├── concept_map_4_virtualization_web_services.png
    ├── integrated_project_concept_map.png
    └── project_architecture_api_flow.png
```

## Architecture summary
The browser frontend is delivered through static hosting/CDN. Requests pass through an API gateway and identity checks to a stateless backend. The backend uses a managed relational database for structured academic records, private object storage for files, and a separate Python analytics workload. Centralized logs, metrics, backups, encryption and least-privilege access support operations.

## CO1 reflection
This work connects cloud characteristics, hardware/software evolution, service models, virtualization and web services to a proposed cloud solution. The service matrices identify provider/customer boundaries, while the architecture diagram shows how APIs, compute, storage, identity and monitoring work together. The design demonstrates conceptual application of cloud technologies; it is a proposal, not evidence of a live deployment.

## Submission checklist
- [ ] Review all personal details and fill the section field if applicable.
- [ ] Open the `.drawio` file in diagrams.net and confirm/edit the maps.
- [ ] Export final diagrams as PNG/PDF if any edits are made.
- [ ] Confirm faculty-specific naming and submission requirements.
- [ ] Upload DOCX, PDF, PNG evidence and editable `.drawio` source to the GitHub repository.
- [ ] Submit the repository URL in Google Classroom and ensure evaluator access.
