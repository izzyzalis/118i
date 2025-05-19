# AquaAnalyzer 💧

<!--
![GitHub Logo](/aquaanalyzer_logo.png)
-->
![Alt Text](/aquaanalyzer_icon.png)

##

## Overview

We built an AI tool that automatically retrieves and analyzes public water quality reports for San Jose and delivers clear, plain-language summaries of potential health concerns and recommendations. Using OCR to extract data from scanned PDFs and GPT-3.5 Turbo for summary generation, the tool increases transparency, improves public understanding, and makes environmental data accessible to non-technical users.

## AquaAnalyzer: What is it?

AquaAnalyzer is an AI-powered tool designed to help residents and local organizations better understand the safety and quality of their drinking water. It processes monthly city-issued water quality reports and outputs a simplified summary of potential contaminants, regulatory compliance, and action-oriented insights.

## Why AquaAnalyzer?

Most municipal water quality reports are published as dense PDFs with complex terminology and formatting that are difficult for the average person to interpret. As a result, residents may be unaware of what’s actually in their water or whether it's safe to drink.

- Existing public access tools often:

  - Focus on raw data with little explanation  
  - Require users to interpret chemical thresholds themselves  
  - Are not mobile- or accessibility-friendly  

Our AI tool addresses these gaps by:

- Automatically extracting water quality data from scanned reports (PDFs)
- Using GPT-3.5 to translate complex reports into everyday language
- Providing a summary of the top 5 potential issues and 5 recommended actions
- Eliminating manual input—users simply click a button to get the latest summary
- Enhancing public awareness and trust in environmental health data

This project supports environmental transparency and public health by making critical water safety information easy to access and understand.

## Our Solution

We created a prototype designed to ingest official water reports (including scanned PDFs), apply Optical Character Recognition (OCR) to extract text, and generate a friendly summary using GPT-3.5 Turbo. The entire process is built on a Python and Streamlit framework for a simple, fast, and interactive user experience.

There are three key components of the system:

**PDF Text Extraction:** Uses PyMuPDF and pytesseract to pull text from scanned water quality reports.

**AI Summary Generator:** Sends cleaned report text to OpenAI’s GPT-3.5 Turbo to generate a list of health risks and recommendations in everyday language.

**No-Input Workflow:** Designed for public use—no user input required. The tool uses preloaded official reports and returns clear insights with one click.

The app was built with public transparency in mind and can easily be expanded in the future to include more cities, alert systems, or live database/API integration.


<!-- Optional screenshots or live demo links can go here -->

