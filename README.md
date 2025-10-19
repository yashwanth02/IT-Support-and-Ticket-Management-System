# IT Supported Ticketing System

This **IT Supported Ticketing System** is designed to streamline the process of assigning support tickets within organizations. Manual ticket assignment is often inefficient, error-prone, and time-consuming, particularly in large organizations. This project leverages **machine learning** and **natural language processing (NLP)** techniques to automatically route support tickets to the appropriate person or team.

## Overview

Traditional support systems often require users to select categories manually or fill out long forms. This can lead to:

- Incorrect category selection by users unfamiliar with the system.
- Increased response times due to manual routing.
- Misallocation of resources and reduced end-user satisfaction.

This system addresses these challenges by analyzing the text of submitted tickets and automatically assigning them to the most relevant support group. It minimizes user effort and reduces delays in issue resolution.

## Key Features

- Automated classification of tickets using **ML and NLP models**
- Accurate routing to the correct department or support staff
- Cross-platform support (Windows, Linux, macOS)
- Scalable for small teams and large enterprises
- Reduces human error and improves response times

## How It Works

1. A user submits a support ticket by describing their issue in natural language.
2. The system processes and analyzes the text using NLP and machine learning.
3. The issue is categorized and routed to the appropriate support group.
4. The ticket is resolved more quickly due to proper assignment.

**Example:**  
User submits: _"I can’t connect to the company VPN."_  
→ System detects a **network issue**  
→ Ticket is auto-assigned to the **Network Support Team**

## Requirements

- Python 3.3+
- Any operating system (Windows, Linux, macOS)
- Dependencies listed in `requirements.txt`

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/keusuanl-sec/it-supported-ticketing-system.git
   cd it-supported-ticketing-system

   ```

2. Create and activate a virtual environment (recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux / macOS
   venv\Scripts\activate      # Windows

   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt

   ```

4. Run the system:
   ```bash
   python main.py
   ```



