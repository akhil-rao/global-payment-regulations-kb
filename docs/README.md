# Global Payment Regulations Knowledge Base

## Project Vision
To build the world's most comprehensive, structured, and open-source knowledge base for global payment regulations. This repository serves as a single source of truth for compliance officers, developers, and researchers. It is optimized for human browsing, GitHub Pages, and AI/RAG indexing.

## Repository Structure
- `countries/`: Regulations grouped by jurisdiction (e.g., `singapore/`, `united-kingdom/`).
- `regulators/`: Profiles and mandates of central banks and financial authorities.
- `topics/`: Thematic deep-dives (e.g., ISO 20022, Open Banking, AML).
- `templates/`: Strict Markdown templates for all document types.
- `schemas/`: JSON schemas for metadata validation.
- `scripts/`: Automation scripts for validation and navigation generation.

## How to Browse
- **By Country:** Navigate to the `countries/` folder and select a jurisdiction.
- **By Regulator:** Navigate to the `regulators/` folder to see rules by authority.
- **By Topic:** Navigate to the `topics/` folder for cross-border thematic rules.

## Contribution Guide
We welcome contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.
1. Fork the repository.
2. Copy the relevant template from `/templates/` to the target directory.
3. Fill out the YAML front matter and all mandatory sections.
4. Submit a Pull Request.

## Metadata & Documentation Standards
Every regulation must include standardized YAML front matter. This ensures consistent AI/RAG chunking and metadata filtering. See `schemas/regulation-frontmatter.json` for the exact required fields.

## Versioning Strategy
We use Semantic Versioning for major releases. Individual regulation updates are tracked via the `Revision History` section inside each document and the global `CHANGELOG.md`.

## Roadmap
- [x] Phase 1: Repository structure and templates
- [ ] Phase 2: Initial data entry (Top 10 countries)
- [ ] Phase 3: GitHub Pages website deployment
- [ ] Phase 4: AI/RAG integration and search optimization
