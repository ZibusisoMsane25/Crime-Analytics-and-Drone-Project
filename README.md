# A Machine Learning Solution for Data-driven Crime Analytics in South Africa

## Developer Information
Name: Msane Z.N  
Student Number: 22415488  
Institution: Mangosuthu University of Technology (MUT)  
Module: Technical Programming II 
Lecturer: Ms. Msane Z.N  

---

## Project Overview
Crime in South Africa continues to pose major social and economic challenges.  
This project uses machine learning and data analytics to analyze, classify, and forecast crime incidents based on data from the South African Police Service (SAPS) and the World Bank Global Indicators.

The project also includes a Drone System Design and Simulation, showing how drones can assist with crime monitoring, surveillance, and data collection.

The main notebook is structured into two key parts:
1. Machine Learning Crime Analytics Project
2. Drone System Design and Simulation

---

## Project Objectives
1. To classify crime hotspots across South Africa using machine learning models.  
2. To forecast future crime trends using time-series models.  
3. To demonstrate drone technology and a simulation that shows how drones can map and monitor grid-based areas efficiently.

---

## Key Tasks
1. Problem Definition  
2. Data Acquisition and Justification  
3. Data Preparation and Cleaning  
4. Exploratory Data Analysis (EDA)  
5. Feature Engineering  
6. Classification of Crime Hotspots  
7. Forecasting Crime Trends Over Time  
8. Model Evaluation and Comparison  
9. Drone System Design and Simulation  
10. Final Conclusion and Recommendations  

---

## Datasets Used
1. **Crime Stats of South Africa (2011–2023)**  
   Source: [Kaggle Dataset — Crime Stats of South Africa](https://www.kaggle.com/datasets/harutyunagababyan/crime-stats-of-south-africa-2011-2023)  
   - Contains crime incidents by year, category, and province.  
   - Used for hotspot classification and trend forecasting.  

2. **World Bank Global Indicator Data**  
   Source: [Kaggle Dataset — World Bank Global Indicator Data](https://www.kaggle.com/datasets/vijayveersingh/world-banks-global-indicator-data)  
   - Includes population, education, GDP, and unemployment statistics.  
   - Supports socio-economic correlation analysis.  

---

## Machine Learning Implementation
The following techniques and models were applied in this project:

### Classification Models
- Logistic Regression  
- Random Forest Classifier  

**Evaluation Metrics**
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

### Forecasting Models
- ARIMA (Auto-Regressive Integrated Moving Average)  
- Prophet (Facebook’s time series forecasting model)  

**Forecast Horizons**
- 1 month (short-term prediction)  
- 2 months (medium-term planning)  
- 4 months (strategic forecasting)

---

## Drone System and Simulation
The Drone section includes both theoretical explanation and a Python simulation.

### Drone Components
- Frame  
- Motors and Propellers  
- Flight Controller  
- GPS Module  
- Sensors and Camera  
- Battery and Power Distribution  
- Transmitter and Receiver  

### Simulation Overview
A Python-based simulation was developed to generate waypoints in a 10x10 grid, representing drone movement using a lawnmower pattern — commonly used for area mapping and surveillance.  
The simulation demonstrates how drones plan paths efficiently to cover entire zones, similar to real-world applications in crime monitoring and mapping.

---

## Tools and Libraries Used
- Python 3  
- pandas – data handling  
- numpy – numerical operations  
- matplotlib and seaborn – visualizations  
- scikit-learn – machine learning  
- statsmodels – ARIMA forecasting  
- prophet – advanced time series forecasting  
- streamlit – dashboard development  
- Jupyter / Google Colab – notebook execution  

---

## Streamlit Dashboard
A Streamlit dashboard was designed with multiple tabs:

1. Home Tab – Overview, project purpose, and key tasks.  
2. EDA Tab – Allows manual dataset upload and visualization.  
3. Model Results Tab – Displays accuracy, precision, recall, and F1 scores.  
4. Settings Tab – Enables users to switch between light and dark themes.  

---

## Model Performance Summary

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|-----------|-----------|---------|-----------|
| Logistic Regression | ~78% | ~80% | ~75% | ~77% |
| Random Forest | ~89% | ~90% | ~88% | ~89% |

### Forecasting Summary

| Model | Forecast Horizon | Observation |
|-------|------------------|--------------|
| ARIMA | 1–4 months | Predicts gradual stability with slight decline |
| Prophet | 1–4 months | Shows mild fluctuations but consistent patterns |

---

## Limitations
- Datasets are aggregated yearly — monthly or provincial data would improve accuracy.  
- External social or political events not factored into the models.  
- Drone simulation is conceptual and could be expanded to include obstacle detection and real-time tracking.

---

## Future Improvements
- Introduce real-time data integration from SAPS APIs.  
- Enhance AI-based hotspot prediction with socio-economic variables.  
- Develop interactive drone flight controllers in simulation.  
- Deploy a fully functional web-based dashboard for public and policy use.  

---

## Conclusion
This project successfully applied machine learning and data analytics to crime data and introduced drone-based solutions for smart surveillance.  
The models performed well and provided actionable insights for crime prevention and policy planning.  
The drone simulation showcased how technology and analytics can combine to support a safer and more efficient society.

---

## Developed By
Name: Msane Z.N  
Student Number: 22415488  
Institution: Mangosuthu University of Technology (MUT)  
Project: A Machine Learning Solution for Data-driven Crime Analytics in South Africa  
Dashboard: Streamlit Crime Analytics Dashboard  
Year: 2025  

*“Data is the new weapon in the fight against crime — and technology is our ally.”*
