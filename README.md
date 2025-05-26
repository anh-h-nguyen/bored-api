# 🥱 Bored API

## Technologies Used
- Programming Language: Python  
- Libraries: requests, json  
- Tools: Any Python IDE (e.g., VS Code, PyCharm, Jupyter Notebook)

## Project Overview

This Python script interacts with the Bored API to generate activity suggestions when users are feeling bored. The program fetches random activities, displays them, and allows users to request new recommendations or exit the program. 

## Table of Contents

1. Introduction  
2. Features  
3. How It Works  
4. Usage Instructions  
5. Future Improvements  

## Introduction

The Bored API project is designed to provide users with spontaneous activity ideas when they’re looking for something to do. This program:
- Retrieves activity suggestions from the Bored API.
- Displays the suggested activity along with its category.
- Allows users to request additional activities interactively.
- Provides a simple and engaging experience for those seeking entertainment or inspiration.

## Features

- Instant Activity Suggestions: Generates new activities with a simple API call.
- Interactive Experience: Users can request multiple suggestions until they find something interesting.
- Categorized Activities: Each activity comes with a type (e.g., recreation, education, social).
- Error Handling: Detects failed API requests and displays appropriate messages.

## How It Works
1. Fetching Activity Data – The script sends a request to the **Bored API** and retrieves a random activity.
2. Parsing the API Response – The returned JSON data is processed and displayed.
3. User Interaction – Users can request a new activity or exit the program.
4. Main Functionality – The script runs in a loop until the user decides to stop.

## Usage Instructions
1. Install dependencies (if needed):
   ```bash
   pip install requests

## Future Improvements
- Add activity filtering: Allow users to specify activity types (e.g., "I want a social activity").
- Implement multiple API calls: Retrieve and display multiple suggestions at once.
- Integrate with other APIs: Connect with a scheduling or weather API for context-aware suggestions.
- Build a GUI or web app: Make the experience more visual and interactive with a Streamlit or Flask interface.
