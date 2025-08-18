# n8n Sample Workflows for Box MCP Server

This repository contains sample n8n workflows demonstrating integrations with the Box Model Context Protocol (MCP) server. These workflows showcase document generation, metadata extraction, and insurance claim processing using Box and n8n automation.

## Contents

- **doc-gen-claim-generation/**  
  Document generation for insurance claims using Box DocGen and sample data.
  - `Box DocGen Claim Generation.json`: n8n workflow for generating claim documents.
  - `sample-data/insurance_claim_template.docx`: Word template for claims.
  - `sample-data/sample_claims_data.json`: Example claim data.

- **enhanced-metadata-extraction/**  
  Enhanced metadata extraction from Box files.
  - `Enhanced Metadata extraction.json`: n8n workflow for extracting metadata.

- **insurance-demo/**  
  Insurance claim demo workflow.
  - `Insurance Demo No agents.json`: n8n workflow for insurance claims (no agents).

- **simple-box-mcp-agent/**  
  Simple Box MCP agent workflow.
  - `Simple Box MCP Agent.json`: n8n workflow for Box MCP agent integration.

## Prerequisites

- [n8n](https://n8n.io/) installed and running.
- Access to a Box MCP server and Box account.
- Import the provided `.json` workflows into n8n.

## Usage

1. Clone this repository.
2. Import the desired workflow `.json` file into your n8n instance.
3. Configure Box credentials and MCP server endpoints as required.
4. Run the workflow to automate document generation, metadata extraction, or insurance claim processing.

## License

See `LICENSE` for details.
