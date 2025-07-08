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
