# n8n Quotes Scraper & API Test Workflow

This repository contains an **n8n workflow** that scrapes quotes from [quotes.toscrape.com](https://quotes.toscrape.com/) and demonstrates simple **API testing**.

## Features
- Sends HTTP requests to the quotes API and validates responses.
- Extracts **quote text**, **author**, and **tags** from JSON/HTML.
- Filters quotes by specific authors (e.g., Albert Einstein).
- Automatically appends results to a Google Sheet.

## Setup
1. Import `API_Test_WorkFlow.json` into your **n8n** instance.
2. Connect your **Google Sheets** account.
3. Update the Google Sheet ID and sheet name in the workflow.
4. Trigger the workflow manually or schedule it to run automatically.

## Usage
- Manual trigger via n8n UI.
- Shows basic **API request-response validation** along with data extraction.
- Optionally schedule for periodic scraping/testing.

## Notes
- Make sure you have the required Google Sheets permissions and API access.
