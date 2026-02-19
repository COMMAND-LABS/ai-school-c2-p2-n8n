# TLDR

Survey Response Analyzer designed by Sofia Espinoza as part of AI School Cohort 2 Phase 2

## STEPS

1. Sofia will send a survey made with Typeform (https://www.typeform.com/) to prospective participants of a program she is helping produce called AI Academy targeted towards AI beginners

2. When the survey is filled out, it'll trigger an n8n workflow

3. After the n8n workflow receives the survey response, the information will get passed to an AI Agent tasked with analyzing aspects of the responses and doing additional research on the associated individual (via a Web Search tool)

4. After the survey has been analyzed, a record of the survey response will be added to a Google Sheet for later analysis

## LIST OF PLATFORMS/TOOLS USED

- n8n (https://n8n.io/)
- Anthropic API (https://platform.claude.com/)
- Typeform (https://www.typeform.com/)
- Google Sheets (https://docs.google.com/spreadsheets/create)
- Google Search Tool (https://serper.dev/)
