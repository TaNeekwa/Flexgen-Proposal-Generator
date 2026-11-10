# Energy Proposal Intake Prototype

A Python and Streamlit prototype for organizing energy-storage proposal requirements into a consistent intake workflow.

## Business problem

Proposal preparation requires customer details, system configuration, service scope, and currency choices. A structured form can make handoffs clearer and reduce repeated information gathering.

## What this version demonstrates

- Project and customer information intake.
- Battery and power-conversion system configuration fields.
- Service-scope selections and custom requirements.
- Currency and exchange-rate inputs.

## Status and limitations

This is an early interface prototype. The “Generate Proposal” button currently displays a confirmation message; document generation, pricing calculations, validation, and export are not implemented. Some conditional fields still need refinement.

Professional automation results described elsewhere should not be interpreted as measured results of this repository.

## Tools

Python · Streamlit · Conda

## Run locally

```bash
conda env create -f environment.yml
conda activate proposal-gen-env
streamlit run streamlit_app.py
```

The environment includes packages beyond the current interface’s needs.

## Responsible demonstration

Use fictional inputs only. Employer branding and the repository name do not establish permission to distribute employer-owned work or imply endorsement. Confirm ownership and publication permission before featuring or extending this prototype.

## Next improvements

- Validate required inputs and show a structured summary.
- Use synthetic data and neutral branding.
- Implement a generic document template and export.
- Test country-specific fields and form completion.
