
# Automated Job Discovery & AI-Powered Job Alert Pipeline

An automated job discovery and notification system built using n8n, Docker, and REST APIs.

## Project Overview

This project aims to automate the process of discovering relevant job opportunities, filtering them based on user-defined preferences, removing duplicates, and delivering a daily email digest.

## Planned Features

- Automated job collection from supported job sources
- Job data extraction and normalization
- Keyword and location-based filtering
- Duplicate detection
- Persistent job storage
- Daily email notifications using SMTP
- Optional AI-based job relevance scoring

## Technology Stack

- n8n Community Edition
- Docker and Docker Compose
- REST APIs
- SMTP
- Git and GitHub

## Workflow Architecture

Coming soon.

## Screenshots

 - **daily_job_alert_workflow.png**: Shows the Daily Job Alert - Test Workflow with Schedule Trigger connected to Edit Fields.
 - **HTTP_request-API_test.png**: Shows the HTTP Request-API Test Workflow with Manual trigger, HTTP request node, Filter Node and Edit Fields.
 - **http_request_output.png**: Show the HTTP Request node and the JSONPlaceholder API response.
 - **filter_output.png**: Show the Filter node output with 10 items.
 - **data_transformation.png**: Show the Edit Fields node output containing only post_id, post_title, and user_id.

## Project Status

### Day 1 – Completed
- Set up n8n Community Edition using Docker.
- Created a scheduled workflow using Schedule Trigger.
- Tested REST API integration using HTTP Request.
- Retrieved and processed multiple JSON records.
- Implemented filtering and field extraction.
