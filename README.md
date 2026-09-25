# DataPipeline

A robust ELT data pipeline for ingesting, transforming, and observing financial market data.

## Prerequisites

- Python 3.11+
- Docker Desktop with Docker Compose

## Getting Started

1. Create and activate a virtual environment:

   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1

2. Install dependencies:
   ```PowerShell
   pip install -r requirements.txt

3. Spin up the local database container:
   ```PowerShell
   docker compose up -d

## Teardown

Stop the running services:

```powershell
docker compose down
