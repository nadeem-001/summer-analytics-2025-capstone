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

##  Architecture Diagram (Mermaid)
> Note: GitHub doesn’t render Mermaid diagrams by default. You can preview this using [Mermaid Live Editor](https://mermaid.live/edit).


##  Workflow
1. Load and clean the dataset
2. Engineer features like occupancy rate and vehicle weight
3. Implement two pricing models:
   - Baseline (linear with occupancy)
   - Demand-based (weighted score)
4. Visualize price trends using Bokeh
5. Simulate real-time pricing using Pathway’s `replay_csv()`
6. Display real-time output using Panel

##  Repository Contents
- `dynamic_parking_pricing.ipynb`: Complete notebook
- `dataset.csv`: Sample dataset
- `README.md`: This file
- `star1.png`, `star2.png`: Screenshots of starred repos

##  How to Run
1. Open the notebook in Google Colab
2. Upload your dataset
3. Run all cells
4. View Bokeh and Pathway visualizations

##  Contact
**Name:** Nadeem Mohammad Qureshi  
**Email:** nadeemrock1467@gmail.com  
