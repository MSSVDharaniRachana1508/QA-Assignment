# Repository Overview

This repository contains the submission for Task 1 and Task 2, focused on QA testing and workflow automation.

## Task 1 – QA Testing Report

Task 1 includes a manual QA testing report created for the RealWorld Demo Application. The testing covered important user flows such as sign-up, login, article creation, editing, logout, navigation, validation, accessibility, and error handling. Multiple bugs were identified, documented, and analyzed with severity levels, reproduction steps, expected vs actual results, suggested fixes, and root cause analysis for a critical issue.

## Task 2 – Workflow Automation using n8n

Task 2 includes an automation workflow built using n8n. The workflow automatically fetches trending stories from the Hacker News API, processes and filters the data, enriches it using a second API request, applies conditional logic using an IF node, and sends the final digest to a Discord webhook notification channel.

The workflow also includes:

* Schedule Trigger automation
* API integration
* Data transformation using Code nodes
* Conditional branching
* Error handling using Continue On Fail
* Secure credential usage without hardcoding secrets

## Repository Contents

* QA Report document
* n8n workflow JSON export
* Workflow screenshots
* Successful execution screenshots
* Supporting README/documentation files

This repository demonstrates practical skills in manual testing, bug reporting, API handling, automation workflows, conditional logic, and basic system integration using no-code/low-code tools.
