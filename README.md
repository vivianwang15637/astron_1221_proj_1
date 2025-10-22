astron_1221_proj_1
---
**Project 11: Space Travel Brochure Generator**
---

- This repository contains the Python project for creating custom vacation brochures for three selected destinations across the Universe. The project combines Object-Oriented Programming (OOP), hardcoded astronomical data, and Large Language Model (LLM) API calls to generate unique, imaginative tour packages based on user-defined goals.

- The project is structured around the SpaceDestination, Activity, and TourPackage classes to manage and present complex travel data, including flight costs (estimated by distance), celestial body specifications, and LLM-generated activities and costs.

---

Setup and Dependencies
This project uses several standard and third-party Python libraries, including those for interacting with LLMs and data visualization.

Installation
You can install the required libraries using pip:

Bash

pip install openai anthropic python-dotenv matplotlib numpy

---

API Key Configuration
The project uses the Anthropic (Claude) API for generating content. You must set up an environment variable for secure API access.

Create a file named .env in the root directory of the project.

Add your Anthropic API key to the file in the following format:

ANTHROPIC_API_KEY="YOUR_API_KEY_HERE"

---

**How to Run the Project**
- Ensure you have completed the Setup and Dependencies steps above.

- Run the main Python script or Jupyter Notebook.

- The program will first prompt you for your vacation goals (e.g., 'budget-friendly', 'luxury experience', 'adventure').

The script will then:

- Call the LLM to select 3 destinations.

- Call the LLM for each of the 3 destinations to generate activities (and print the raw LLM output).

- Create three separate text files (brochures) in the current directory.

- Display a Matplotlib bar chart comparing the base travel costs.



# astron_1221_proj_2
