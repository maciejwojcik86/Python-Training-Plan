# Introduction to python

## Setup

- Anaconda
there a other tools to manage environments but this is one of most popular and easiest. Once installed Anaconda you already have python and other tools installed. Creating and activating env can be done via windows app or in windows terminal 

https://www.youtube.com/watch?v=WUeBzT43JyY

- Code editor
There are many options With anaconda you will have already VS Code, Jupyter Notebooks, Spyder and other but I recommend to install Cursor and start using it straigh away. It is extension of VS Code for anything that apply to VS Code works with Cursor.

https://www.cursor.com/

## Introduction to VS Code and Python

https://www.youtube.com/watch?v=6i3e-j3wSf0
great short tutorial how to use it and its options
You dont need to install python as you already have it with anaconda. Same with managing venv.
https://code.visualstudio.com/docs/python/python-tutorial

## Notebooks

by default python code is in scripts .py files where each script can be run as independet app or they can be linked by importing functions or variables from one to another. Thats how whole complicated application is build.
https://code.visualstudio.com/docs/datascience/data-science-tutorial

There is another option especially useful for testing, data science or learning: Jupyter Notebooks which allows to code and run small parts of code and see results in the same file. You can use notebooks in browser (Jupyter or Google Colab) or better create .ipynb files (insted of .py) in VS Code (or Cursor)

## Python In depth course

- HarvardX: CS50's Introduction to Programming with Python:
it long, but in depth and fun
https://www.edx.org/learn/python/harvard-university-cs50-s-introduction-to-programming-with-python
or 
https://www.youtube.com/watch?v=nLRL_NcnK-4

- Complete Python Course For Beginners: Python Tutorial For 2024
shorter and cover most of what is needed
https://www.youtube.com/watch?app=desktop&v=CmtRRVSeR58

### First apps to learn

- Always try to copy code from tutorials and run it yourself
- create a lot of different mini projects and save them separately to practice creating environments and always have some previously created tools and lessos for you reference
- Maybe as 1st projects try to process some data in notebooks, import excels .cvs files with pandas, try to decay correct some actity, create graphs with pyplot. This may be already useful at work

## AI with python

### Use LLM as Tutor

Ask chatbots to explain concepts, provide examples and pieces of code which try to run
Paste them errors and ask to explain or fix. You can use them for free:
- https://chatgpt.com/
- https://claude.ai/new
- https://huggingface.co/chat/ 
    (with the best free model: meta-llama/Meta-Llama-3.1-405B-Instruct-FP8 )
- or directly in Cursor editor

### Theoreretical course about AI and LLM
https://learnprompting.org/docs/introduction

### AI Python app
Dont be shy to try creating some AI app:

- Quick and simple tutorial how to use OpenAI API with Streamlit (UI library)
https://www.kdnuggets.com/beginners-guide-to-building-llm-apps-with-python

- Easy introduction how to setup and start agents in Autogen
https://www.youtube.com/watch?v=V2qZ_lgxTzg&t=1s

## For Later

Learn techs needed for collaboration and work with my LIMS/QMS project

- Git/Github
https://www.youtube.com/watch?v=jLWZaFzPS6Q

- SQLModel (to handle database in python)
https://sqlmodel.tiangolo.com/tutorial/

- Streamlit (for UI)
https://docs.streamlit.io/develop/tutorials

------
------

# Training plan according to ChatGPT
I asked ChatGPT to create training plan for you, which is very reasonable, matches what I listed above

my prompt:
```
I build my small python project which is laboratory information management system. I mainly use SQLModel, streamlit as UI and some LLM capabilities like autogen and OpenAI API. I want to involve my friend who has no experience with this at all but can quickly learn. Can you prepare a training plan of concepts he would need to learn? Starting with initial setup ( I recommend anaconda and vs code), up to familiarisation to LLM and packages I mentioned.
```

Certainly! Here's a structured training plan that will help your friend get up to speed with your laboratory information management system (LIMS) project. This plan assumes your friend is familiar with basic programming concepts but has no specific experience with Python, SQLModel, Streamlit, or LLM (Large Language Model) capabilities.

### **Week 1: Setting Up the Environment**

**Day 1-2: Initial Setup**
- **Objective**: Set up the development environment.
- **Tasks**:
  - Install **Anaconda** (for managing packages and environments).
  - Install **VS Code** (as the IDE).
  - Configure VS Code with Python extensions.
  - Learn basic terminal commands (navigating directories, creating environments, etc.).
  - Create a new Conda environment specifically for the project.

**Day 3-4: Python Basics Refresher**
- **Objective**: Refresh Python programming basics.
- **Tasks**:
  - Learn about Python data types, loops, functions, and error handling.
  - Practice with simple Python scripts to ensure understanding.
  - Familiarise with virtual environments using Conda.

**Day 5-7: Git and Version Control**
- **Objective**: Learn to use Git for version control.
- **Tasks**:
  - Install Git and configure GitHub.
  - Learn basic Git commands (clone, commit, push, pull).
  - Practice with a simple Git workflow (e.g., creating branches, resolving conflicts).
  - Clone the LIMS project repository.

### **Week 2: Core Python Libraries**

**Day 1-3: Introduction to SQLModel**
- **Objective**: Understand SQLModel and its role in the project.
- **Tasks**:
  - Install and configure SQLModel.
  - Learn the basics of SQLModel and how it integrates with databases.
  - Practice creating models, connecting to a database, and performing CRUD operations.
  - Explore the SQLModel documentation and simple examples.

**Day 4-5: Working with Databases**
- **Objective**: Understand database basics and how to interact with them using SQLModel.
- **Tasks**:
  - Introduction to SQL databases (e.g., SQLite for simplicity).
  - Learn to write basic SQL queries.
  - Understand relationships (One-to-Many, Many-to-Many) in databases.
  - Practice with SQLModel to create and query these relationships.

**Day 6-7: Introduction to Streamlit**
- **Objective**: Build a simple UI with Streamlit.
- **Tasks**:
  - Install and configure Streamlit.
  - Explore basic Streamlit components (text, input fields, buttons).
  - Create a simple interactive app (e.g., a form to input and display data).
  - Understand the concept of state management in Streamlit.

### **Week 3: Building on the Basics**

**Day 1-3: Intermediate SQLModel and Streamlit**

- **Objective**: Dive deeper into SQLModel and Streamlit.
- **Tasks**:
  - Implement more complex queries and operations in SQLModel.
  - Integrate SQLModel with Streamlit to display data dynamically.
  - Create more sophisticated Streamlit layouts (e.g., using sidebars, multi-page apps).
  - Experiment with Streamlit components like charts, maps, and file uploads.

**Day 4-5: Working with APIs**

- **Objective**: Learn how to interact with APIs.
- **Tasks**:
  - Introduction to RESTful APIs and JSON.
  - Learn to make API requests using Python’s `requests` library.
  - Explore how to integrate external APIs with the LIMS project.
  - Practice by fetching data from a public API and displaying it in Streamlit.

**Day 6-7: Introduction to LLMs and the OpenAI API**

- **Objective**: Get an initial understanding of LLMs and how to use the OpenAI API.
- **Tasks**:
  - Overview of Large Language Models (LLMs) and their applications.
  - Introduction to the OpenAI API (setup API key, basic usage).
  - Create a basic script that interacts with the OpenAI API to generate text.
  - Integrate a simple LLM-based feature into Streamlit (e.g., generating lab reports).

### **Week 4: Advanced Topics and Project Integration**

**Day 1-3: Advanced Streamlit Features**

- **Objective**: Leverage advanced Streamlit capabilities.
- **Tasks**:
  - Explore advanced UI components (e.g., custom components with Streamlit's component API).
  - Learn how to optimise Streamlit apps for performance.
  - Implement user authentication and session management.
  - Integrate data visualisation libraries (e.g., Plotly, Matplotlib) within Streamlit.

**Day 4-5: Advanced LLM and AutoGen**

- **Objective**: Get familiar with AutoGen and more complex LLM use cases.
- **Tasks**:
  - Overview of AutoGen for generating code or structured data.
  - Learn to create prompts for more specific tasks (e.g., summarisation, classification).
  - Integrate AutoGen into the LIMS system (e.g., generating summaries of lab results).
  - Experiment with fine-tuning the interaction with the OpenAI API.

**Day 6-7: Final Integration and Project Work**

- **Objective**: Combine all learned concepts into the LIMS project.
- **Tasks**:
  - Work on a real feature of the LIMS project, integrating SQLModel, Streamlit, and LLMs.
  - Collaborate on GitHub, using issues and pull requests.
  - Perform code reviews and learn best practices.
  - Refactor and optimise code based on peer feedback.

### **Ongoing Learning and Resources**

- **Online Courses**: Recommend relevant online courses (e.g., Coursera, Udemy) for deeper dives.
- **Documentation**: Encourage frequent reference to official documentation for SQLModel, Streamlit, and OpenAI.
- **Practice Projects**: Suggest small, separate projects for honing skills.

This plan should give your friend a strong foundation in the tools and technologies used in your project. Adjust the pace as necessary based on their progress.
