# Project Proposal Summarizer

An AI-powered tool for analyzing and summarizing project proposals using agent-based workflows.

## Overview

The Project Proposal Summarizer is a sophisticated tool that leverages multiple AI agents, each with specialized roles, to analyze project proposals from different perspectives and generate comprehensive, insightful summaries and recommendations.

## Key Features

- **Multi-Agent Analysis**: Uses six specialized agents with distinct roles:
  - Project Proposal Analyzer
  - Market Research Specialist
  - Technical Feasibility Expert
  - Financial Viability Assessor
  - Risk Management Specialist
  - Executive Summary Specialist

- **Comprehensive Evaluation**: Analyzes proposals across multiple dimensions:
  - Business objectives and strategic alignment
  - Market potential and competitive landscape
  - Technical feasibility and architecture
  - Financial projections and ROI
  - Risk assessment and mitigation strategies

- **Advanced Summarization**: Uses transformer-based models to generate concise yet comprehensive executive summaries

- **Detailed Logging**: Provides rich, multi-format logging for transparency and debugging

## Project Structure

```
project-proposal-summarizer/
├── agents/
│   ├── __init__.py
│   └── definitions.py
├── data/
│   ├── __init__.py
│   └── proposal.py
├── models/
│   ├── __init__.py
│   └── summarization.py
├── processing/
│   ├── __init__.py
│   └── simulation.py
├── tasks/
│   ├── __init__.py
│   └── definitions.py
├── utils/
│   ├── __init__.py
│   ├── config.py
│   ├── logger.py
│   └── system_info.py
├── config.json
├── settings.yaml
├── main.py
├── requirements.txt
└── README.md
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project-proposal-summarizer.git
   cd project-proposal-summarizer
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the main script:

```bash
python main.py
```

This will:
1. Load the sample project proposal
2. Initialize the agent-based workflow
3. Simulate the analysis process with detailed logging
4. Generate a final summary report

## Configuration

The application can be configured using:

- `config.json`: JSON-based configuration for agents, models, and process settings
- `settings.yaml`: YAML-based configuration for logging, display settings, and process parameters

## Requirements

See `requirements.txt` for a complete list of dependencies. Key requirements include:

- crewai
- transformers
- tabulate
- termcolor
- pandas
- numpy

## License

MIT License
