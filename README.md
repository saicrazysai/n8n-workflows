# n8n Workflows Collection

This repository is a collection of powerful, ready-to-use workflows for the low-code automation platform [n8n.io](https://n8n.io/). Each project is included as a submodule and contains its own detailed documentation.

These workflows demonstrate how to automate complex processes, integrating various APIs and AI services to minimize manual work and increase efficiency.

## Workflows

| Workflow                                                              | Description                                                                                                                                                                                          | Key Technologies                                       |
| --------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| [**Invoice Automation**](https://github.com/umur957/n8n-invoice-automation/tree/7e03c77a2ee90a0a844dc339f7d8b068aae8d6a5)                   | Extracts data from PDF invoices received via Gmail using AI-powered OCR (Mistral & Gemini), parses the content into a structured format, and saves it to Google Sheets and Google Drive.                 | AI, OCR, Gemini, Mistral AI, Gmail, Google Sheets      |
| [**Job Application Assistant**](https://github.com/umur957/n8n-job-application-workflow/tree/45de7d295c6102c4c27db9b5b6f8e335b0953b6c)      | Automates the job search process by scraping LinkedIn for relevant jobs, using OpenAI (GPT-4) to filter listings, dynamically tailoring a resume for each role, and sending personalized application emails. | Web Scraping, AI, OpenAI, Apify, Google Docs, Gmail     |
| [**Lead Qualification**](https://github.com/umur957/n8n-remwaste-challenge/tree/0a62ffc3cd0bcd35be00f89e028a6ae3089b19ea)                   | Captures new leads from a web form (Tally.so) via a webhook, automatically scores them based on custom logic (e.g., budget, interest), and sends instant Slack notifications for "Hot Leads".            | Webhook, Lead Scoring, Tally.so, Google Sheets, Slack |

## Usage

Each workflow folder contains a `workflow.json` file that can be imported directly into your n8n instance.

For detailed setup instructions, credentials, and configuration, please refer to the `README.md` file within each respective submodule's directory.

## Contributing

Contributions, issues, and feature requests are welcome! If you have a workflow you'd like to add, please feel free to open a pull request.

**Author: UMUR KIZILDAS**
