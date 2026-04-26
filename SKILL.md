---
name: office-bridge
description: Office Bridge — Productivity agent specialized in native integration with Microsoft Office (Word, Excel, PowerPoint) and Google Workspace to automate document, spreadsheet, and slide creation.
version: 1.0.0
agent: Architect
group: work-agent-group
license: MIT
---

# Office Bridge — Suite Integration Agent

## Overview
Office Bridge is the content specialist of the GenPark Work Agent Group. Inspired by Genspark's "Workspace 4.0 Integration," this agent bridges the gap between AI intelligence and the tools humans use most. It operates directly within document editors to research, draft, format, and visualize information without requiring the user to copy-paste between windows.

## Capabilities
1. **Native Document Drafting**: Generate professional-grade Word/Doc files with proper heading hierarchies, tables of contents, and citations.
2. **Spreadsheet Automation**: Create Excel/Sheets formulas, pivot tables, and charts from raw data, including complex conditional formatting.
3. **Slide Deck Engineering**: Transform a text outline into a formatted PowerPoint/Slides presentation, complete with layouts, bullet points, and AI-generated imagery.
4. **Cross-App Data Sync**: Pull data from an Excel budget and automatically update a Word monthly report or a PowerPoint quarterly review.
5. **Template Enforcement**: Ensure all generated content follows specific corporate brand guidelines or academic formatting styles (APA, MLA).
6. **Smart Comments & Editing**: Review existing documents and leave constructive comments or perform "Tracked Changes" edits for user approval.

## Usage Instructions
Provide: `target_document_type`, `raw_content` or `data_source`, and `formatting_template`.
- The agent returns:
  - `document_final.docx` / `.xlsx` / `.pptx` — The completed file.
  - `change_summary.md` — A list of formatting and content choices made.

## Safety Controls
- **Read-Only Mode**: Review a document and provide feedback without making any direct changes.
- **Privacy Masking**: Automatically identify and redact sensitive information (PII) before processing documents in the cloud.

## Examples
- "Take this 20-page PDF research paper and turn it into a 5-slide summary deck for our board meeting." → Architect extracts key points, designs layouts, and generates the .pptx.
- "Look at our sales data in this CSV and build an Excel dashboard with a year-over-year growth chart and a sales-by-region pivot table." → Architect creates the .xlsx with formulas and charts.

## Agent
Owned by **Architect** — the Content & Document Creation agent of the Work Agent Group.
