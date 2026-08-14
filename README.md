# 🌍 Smart Tourism Travel Planning & Recommendation Automation

An AI-powered travel planning and recommendation automation system built using **n8n, Groq, Google Sheets, Google Calendar, Gmail, Geocoding API, Weather API, and JavaScript**.

The system collects a customer's travel requirements through an automated registration form, processes the submitted information, uses AI to recommend a suitable destination, retrieves location and weather information, generates a personalized travel itinerary, creates a Google Calendar event, stores the final travel record in Google Sheets, and sends personalized travel recommendations through Gmail.

---

# 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Problem Statement](#-problem-statement)
- [Business Context](#-business-context)
- [Project Objectives](#-project-objectives)
- [Stakeholders](#-stakeholders)
- [Pain Points](#-pain-points)
- [Solution](#-solution)
- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [Workflow Architecture](#-workflow-architecture)
- [Detailed Workflow](#-detailed-workflow)
- [AI-Powered Decision Making](#-ai-powered-decision-making)
- [API Integrations](#-api-integrations)
- [Data Flow](#-data-flow)
- [Workflow Nodes](#-workflow-nodes)
- [Conditional Logic](#-conditional-logic)
- [Google Sheets Integration](#-google-sheets-integration)
- [Google Calendar Integration](#-google-calendar-integration)
- [Gmail Integration](#-gmail-integration)
- [Output](#-output)
- [Technology Stack](#-technology-stack)
- [Repository Structure](#-repository-structure)
- [Installation and Setup](#-installation-and-setup)
- [Credential Configuration](#-credential-configuration)
- [Importing the Workflow](#-importing-the-workflow)
- [Configuration Requirements](#-configuration-requirements)
- [Security](#-security)
- [Testing](#-testing)
- [Example Workflow Execution](#-example-workflow-execution)
- [Advantages](#-advantages)
- [Limitations](#-limitations)
- [Future Enhancements](#-future-enhancements)
- [Capstone Requirements Mapping](#-capstone-requirements-mapping)
- [Demo](#-demo)
- [Screenshots](#-screenshots)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

# 🌟 Project Overview

Travel planning often requires customers to provide their requirements, compare destinations, check weather conditions, create itineraries, arrange schedules, and communicate with travel planners.

These activities can involve multiple tools and significant manual effort.

The **Smart Tourism Travel Planning Automation** solves this problem by connecting AI, APIs, databases, calendars, and email communication into a single automated workflow.

A customer provides information such as:

- Full Name
- Email
- Phone Number
- Travel Date
- Number of Travelers
- Estimated Budget
- Trip Duration
- Travel Interests
- Accommodation Preference
- Transportation Preference

The automation then processes this information and generates a personalized travel experience.

---

# ❗ Problem Statement

Traditional travel planning involves several repetitive activities:

1. Collecting customer information.
2. Understanding travel preferences.
3. Selecting an appropriate destination.
4. Researching destination information.
5. Checking weather conditions.
6. Preparing a day-wise itinerary.
7. Recording customer information.
8. Scheduling travel-related events.
9. Sending personalized communication.

Performing these tasks manually can be:

- Time-consuming
- Repetitive
- Error-prone
- Difficult to scale
- Difficult to personalize for every customer

The goal of this project is to automate these activities using an AI-powered workflow.

---

# 🏢 Business Context

The system can be used by:

- Travel agencies
- Tourism companies
- Travel consultants
- Online travel platforms
- Hospitality businesses
- Corporate travel planners
- Personal travel assistants

A travel business can use this automation to process customer requests automatically instead of manually preparing every travel plan.

The workflow can handle customer data, make AI-based recommendations, enrich the data using external APIs, schedule travel events, and communicate the final result.

---

# 🎯 Project Objectives

The main objectives are:

### 1. Automate Travel Registration

Collect customer travel requirements through an automated form.

### 2. Automate Destination Recommendation

Use Groq-powered AI to analyze:

- Budget
- Trip duration
- Number of travelers
- Travel interests
- Accommodation preferences
- Transportation preferences

and recommend a suitable destination.

### 3. Enrich Destination Information

Use external APIs to retrieve:

- Geographic information
- Latitude and longitude
- Weather information

### 4. Generate Personalized Itineraries

Generate a day-wise travel plan based on the customer's requirements.

### 5. Automate Scheduling

Create a Google Calendar event for the trip.

### 6. Automate Communication

Send the customer a personalized email containing their travel plan.

### 7. Maintain Records

Store customer and travel information in Google Sheets.

### 8. Generate Premium Recommendations

Provide optional premium travel recommendations such as:

- Luxury accommodation
- Private transportation
- Premium dining
- Exclusive experiences

---

# 👥 Stakeholders

## Primary Stakeholders

### Customers

Customers provide their travel preferences and receive a personalized travel plan.

### Travel Agencies

Travel agencies can use the system to automate customer processing and travel planning.

### Travel Consultants

Consultants can use AI-generated recommendations as a starting point for customer planning.

## Secondary Stakeholders

- Tourism businesses
- Hotels
- Transportation providers
- Hospitality companies
- System administrators

---

# 😓 Pain Points

The system addresses the following problems:

| Problem | Automated Solution |
|---|---|
| Manual customer registration | n8n form |
| Manual destination research | Groq AI |
| Manual weather checking | Weather API |
| Manual location lookup | Geocoding API |
| Manual itinerary creation | AI-generated itinerary |
| Manual record keeping | Google Sheets |
| Manual scheduling | Google Calendar |
| Manual email communication | Gmail |
| Repetitive premium recommendations | AI-generated recommendations |

---

# 💡 Solution

The proposed solution is an **AI-powered workflow automation system**.

The system follows this basic pipeline:

```text
Customer
   ↓
Travel Registration Form
   ↓
Customer Data Processing
   ↓
Google Sheets
   ↓
AI Destination Recommendation
   ↓
Destination Data Processing
   ↓
Geocoding API
   ↓
Weather API
   ↓
AI Personalized Itinerary
   ↓
Google Calendar
   ↓
Premium Recommendation
   ↓
Final Travel Record
   ↓
Google Sheets
   ↓
Gmail
