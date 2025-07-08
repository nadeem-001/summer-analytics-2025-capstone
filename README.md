#  Dynamic Pricing for Urban Parking Lots

##  Overview
This project was built as part of the Summer Analytics 2025 Capstone hosted by the Consulting & Analytics Club, IIT Guwahati.  
The goal is to simulate a real-time pricing engine for 14 urban parking lots using demand signals like occupancy, queue length, traffic, and special events.

##  Tech Stack
- Python
- Pandas, NumPy
- Bokeh, Panel (for visualization)
- Pathway (for real-time simulation)
- Google Colab

##  Architecture Diagram
```mermaid
flowchart TD
    A[CSV Dataset] --> B[Preprocessing]
    B --> C[Pricing Models]
    C --> D[Bokeh Visualization]
    B --> E[Pathway Streaming]
    E --> F[Real-Time Pricing Output]

 Workflow
Load and clean the dataset

Engineer features like occupancy rate and vehicle weight

Implement two pricing models:

Baseline (linear with occupancy)

Demand-based (weighted score)

Visualize price trends using Bokeh

Simulate real-time pricing using Pathway’s replay_csv()

Display real-time output using Panel

 Repository Contents
dynamic_parking_pricing.ipynb: Complete notebook

dataset.csv: Sample dataset

README.md: This file

star1.png, star2.png: Screenshots of starred repos

 How to Run
Open the notebook in Google Colab

Upload your dataset

Run all cells

View Bokeh and Pathway visualizations

 Contact
Name: Nadeem Mohammad Qureshi Email: nadeemrock1467@gmail.com
