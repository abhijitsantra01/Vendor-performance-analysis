🧠 Vendor Data Analysis — Business Sentiment & AI Story Report
📊 Overview

Vendor Data Analysis is an AI-powered project designed to analyze news data from multiple vendor companies, extract key business events, cluster them by company, and generate automated business sentiment reports and investment recommendations using OpenAI’s GPT models.

This system provides a comprehensive view of vendor performance, strategic direction, and potential investment insights — helping investors and corporate partners make data-driven decisions.

🚀 Features

JSON Data Parsing: Reads and processes vendor news data from a JSON source.

Clustering by Company: Automatically groups all events by company_name.

Sentiment Story Reports: Generates concise business sentiment summaries for each company using gpt-4o-mini.

Investment Analysis: Evaluates strategic relationships between investor companies (e.g., Alphabet/Google) and vendors (e.g., Reliance Industries).

AI-Generated Business Insights: Produces human-readable, professional-grade reports with risk–opportunity analysis and recommendations.

🧩 Workflow

Load Vendor Data

Load raw JSON data containing fields like company_name, headline, news_event, date, and sentiment_tag.

Cluster Events

Use a Python script to group all news_event entries by company name.

Generate Story Reports

For each company cluster, feed recent news events into an LLM prompt to create a concise sentiment and trend report.

Investment Analysis

Use another prompt to analyze whether an investor company (like Alphabet/Google) should continue, expand, or reconsider its partnerships with specific vendors.

Output

AI-generated story reports and investment advisory notes are printed in the console for quick review.
