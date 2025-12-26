# Module Extraction AI Agent

## Overview
This project implements an AI agent that processes technical documentation URLs and automatically extracts structured modules and submodules.

## Approach
- Documentation pages are crawled with controlled depth
- HTML content is cleaned and parsed
- Semantic grouping is applied to identify:
  - Modules (high-level features)
  - Submodules (specific actions or components)
- Final output is generated as structured JSON

## Output
The agent produces a `module_output.json` file containing extracted modules and submodules.

## Limitations
- JavaScript-heavy pages may require browser-based crawling
- Module naming depends on documentation structure

## Demo Video
A short video walkthrough explaining the approach and generated output:
https://drive.google.com/file/d/1LZeZNcnYV1NJsq6sP3g3Q5fgA3NzY-La/view?usp=drivesdk

