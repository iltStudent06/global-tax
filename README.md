# Global Tax Data Collection

A centralized web application for collecting tax-related information from all country operations to support Liberty Mutual's tax planning and reporting.

## Overview

This application helps distributed teams submit country-specific tax data into a single system with consistent structure, auditability, and role-based access. It supports configurable submission templates, validations, and exports for downstream tax and finance processes.

## Key Features

- **Standard intake for multi country data**: Standardized forms and requirements
- **Validation rules**: Required fields and format checks
- **Workflow & approvals**: Draft → Submitted → Reviewed → Approved
- **Audit trail**: Field-level changes, timestamps, and user attribution
- **Exports**: CSV exports
- **Access control**: Roles for Contributors, Reviewers, Admins

## What Data This App Collects

The application captures:

- Operation location and currency details
- Projected pre-tax income/loss and tax expense/benefit

## Architecture

- **Frontend**: Web UI for country teams to enter and upload tax data
- **Backend API**: Authentication, validation, workflow, audit logs
- **Database**: Structured storage for entities, periods, tax attributes, and metadata
- **Object Storage**: Secure storage for supporting documents
- **Job/Worker**: Scheduled reminders, export jobs, data quality checks

## Getting Started

### Prerequisites

- Git
- Python 3.11+
- PostgreSQL

### Installation

```bash
git clone https://github.com/iltStudent06/global-tax.git
cd global-tax
npm install
```
