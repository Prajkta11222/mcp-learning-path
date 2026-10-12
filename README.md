# MCP Learning Path Generator 

An AI-powered learning assistant that transforms learning goals into personalized study paths, helping learners discover relevant YouTube learning resources for focused preparation.

## 🚀 Live Demo

[Open the MCP Learning Path Generator](https://mcp-learning-path-3yrrzw7e7gavvn3rkcakpx.streamlit.app/)

## Overview

The MCP Learning Path Generator is a Streamlit-based application that uses GPT and YouTube data to help users explore learning resources based on their goals.

Users can enter goals such as:

- "I want to learn DSA in 7 days."
- "I want to revise DBMS for my exam."
- "I want to prepare for coding interviews."

The application generates a learning path intended to help users organize their preparation and discover relevant educational content.

## Features

- **Goal-based learning:** Enter a learning objective in natural language.
- **AI-assisted planning:** Use GPT-powered functionality to generate personalized learning guidance.
- **YouTube resource discovery:** Retrieve relevant learning resources through the application's YouTube data integration.
- **Interactive interface:** Explore learning paths through a Streamlit application.
- **Multiple learning goals:** Try the application with programming, interview preparation, and exam revision objectives.

## Tech Stack

- **Language:** Python
- **Frontend / UI:** Streamlit
- **AI:** GPT via API integration
- **Data integration:** YouTube data/API integration
- **Protocol / concepts:** Model Context Protocol (MCP)

*Technologies are listed based on the project's implementation; verify the actual API and MCP integration before describing the underlying architecture in more detail.*

## How It Works

1. Enter a learning goal in the application.
2. The application processes the goal using its AI-powered workflow.
3. Relevant learning guidance and educational resources are generated or retrieved.
4. Review the results and use them to organize your study plan.

## Example Use Case

**Goal:** Prepare for DSA coding interviews.

The application can help explore a structured learning path and relevant educational resources for interview preparation.

## Project Exploration and Testing

I explored the application by testing custom learning goals, reviewing generated outputs, and capturing screenshots to document example workflows.

This hands-on exploration helped me understand how AI APIs, interactive Python applications, and educational-resource integrations can work together in a practical learning tool.

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Prajkta11222/mcp-learning-path.git
   cd mcp-learning-path
   ```

2. Create and activate a Python virtual environment.

3. Install the dependencies listed in the repository's requirements file:

   ```bash
   pip install -r requirements.txt
   ```

4. Configure the required API credentials using the project's expected environment variables or secrets configuration. Never commit API keys.

5. Start the Streamlit application using the repository's actual entry-point filename:

   ```bash
   streamlit run app.py
   ```

   Replace `app.py` if the entry point has a different name.

## Screenshots
| **Step**      | **Screenshot**                                                |
| ------------- | ------------------------------------------------------------- |
| 🎯 Input Goal | [input](input1.png)    |
| ⚙️ Generating | [progress](generating.png) |
| ✅ Result (1)  | [r1](result1.png)       |
| ✅ Result (2)  | [r2](result2.png)       |
| ✅ Result (3)  | [r3](result3.png)       |


## What I Learned

- Exploring GPT-powered application workflows.
- Working with Streamlit-based interfaces.
- Understanding API integrations in an AI application.
- Testing different user goals and reviewing generated outputs.
- Documenting application behavior and example results.

## Repository

GitHub: https://github.com/Prajkta11222/mcp-learning-path

## Credits and Attribution

This repository was originally provided as part of a guided learning program. My contribution focused on exploring the application, testing custom inputs, reviewing outputs, and documenting its behavior.

Original project authorship and licensing should be respected.
