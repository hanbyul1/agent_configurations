# Agent Configurations – Task Analyses and Implementations

This repository contains analysis and implementation files for experiments on **agent configurations** in LLM-assisted software development.  
The materials include both **task-level analysis notes** (`.tex` files, plain text) and **Jupyter Notebooks** (`.ipynb`) for running and reproducing experiments.  

## Repository Structure

### Analysis Files
agent_configurations/
├── task1-analysis.tex
├── task2-analysis.tex
├── task3-analysis.tex
├── task4-analysis.tex
├── task5-analysis.tex
├── task6-analysis.tex
├── task7-analysis.tex
├── task8-analysis.tex
├── task9-analysis.tex

- Each `.tex` file contains the analysis for one designated task.  
- The content is **plain text** (not LaTeX compilable) but formatted via LaTeX editors.  
- Each file documents results for:  
  - **Three systems**: TORS (Tour Reservation System), SWS (Smart Home System), FODS (Food Ordering and Delivery System)  
  - **Three configurations**: Task-Specialist, Phase-Specialist, Process-Generalist  

---

### Implementation Files
agent_configurations/
├── TORS-individual-task.ipynb
├── TORS-individual-phase.ipynb
├── TORS-single-agent.ipynb
├── SWS-individual-task.ipynb
├── SWS-individual-phase.ipynb
├── SWS-single-agent.ipynb
├── FODS-individual-task.ipynb
├── FODS-individual-phase.ipynb
├── FODS-single-agent.ipynb

- Each `.ipynb` Jupyter Notebook contains executable code for reproducing results in one of the three systems.  
- For each system (**TORS, SWS, FODS**), three configurations are provided:  
  - `*-individual-task.ipynb` → Task-Specialist configuration  
  - `*-individual-phase.ipynb` → Phase-Specialist configuration  
  - `*-single-agent.ipynb` → Process-Generalist configuration  

---

## Purpose

Together, the analysis files and notebooks provide a full replication package for the experiments.  

- The **analysis files** describe and interpret the results.  
- The **implementation notebooks** reproduce the actual runs for each system and configuration.  

This structure allows other researchers to both **inspect the reasoning** and **replicate the execution** of the experiments.

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/agent_configurations.git
   cd agent_configurations

2.	Open the Jupyter Notebooks to reproduce experiments:

jupyter notebook TORS-individual-task.ipynb

3.	Open the .tex analysis files in any text editor to review task-specific analysis results.

License

This repository is released under the MIT License.
