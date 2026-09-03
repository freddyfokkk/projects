# Data Analytics Portfolio 📊

Welcome to my data science portfolio. This repository contains end-to-end data analytics and predictive modeling projects, each accompanied by business summaries or project progress updates designed to showcase critical thinking, structural problem-solving, and data-driven solutions to real-world business challenges.

---

## 🚀 Featured Projects

### 1. Stock Trade Data Analysis

*   *Core Objective:* Analyzed historical stock market data to identify trading patterns, evaluate financial risks, and develop predictive models.
*   *Tech Stack:* Python, Pandas, Matplotlib, Scikit-Learn
*   *Key Deliverable:* [View Jupyter Notebook](Stock_Trade_Data_Analysis.ipynb) | [View Executive Summary](Stock_Trade_Data_Analysis.pdf)
*   *Summary:* This project explores financial market trends by analyzing stock trade data. Through exploratory data analysis and predictive modeling, it uncovers key insights into market volatility and trading behaviors, finalising in an executive presentation for financial stakeholders.

### 2. DataCo Supply Chain Analytics & Predictive Modelling
*   **Core Objective:** Cleaned and integrated an e-commerce supply chain dataset of 180,000+ orders to identify key drivers behind late deliveries, order cancellations, and payment risks.
*   **Tech Stack:** Python, Pandas, Scikit-Learn (Random Forest Classification).
*   **Key Deliverable:** [View Jupyter Notebook](./Final_DataCo_project.ipynb) | [View Executive Summary](./Fok%20Koe%20Kian%20Freddy_DataCo.pdf)
*   **Summary:** This project addresses supply chain inefficiencies and financial leakage by analyzing over 180,000 e-commerce transactions to identify the core operational drivers of late deliveries, order cancellations, and payment risks. By training a Random Forest classification model on a targeted subset of approximately 32,800 orders, the analysis successfully isolates high-risk delivery routes and customer behaviors to flag delivery delays before they occur. Ultimately, these predictive insights are translated into concrete mitigation strategies and an executive recommendation deck designed to protect profit margins, optimize inventory movement, and improve customer retention.

### 3. New York Yellow Taxi Performance Analysis
*   **Core Objective:** Investigated urban transit efficiency, trip durations, and pricing behaviors using historical NYC yellow cab trip data.
*   **Tech Stack:** Python, Pandas, Matplotlib, Seaborn.
*   **Key Deliverable:** [View Jupyter Notebook](./Yellow%20Taxi.ipynb) | [View Executive Summary](./Automatidata_Executive_Summary.pdf)
*   **Summary:** This ongoing project investigates urban transit efficiency and revenue optimization by conducting deep exploratory data analysisProject progress update for teammates and stakeholders. Phase one focuses on cleaning raw data to isolate high-traffic bottlenecks, peak operational hours, and fare pricing behaviors across different city zones. These foundational visual insights establish the baseline metrics necessary to build upcoming predictive models aimed at reducing driver downtime and maximizing fleet profitability.

### 4. CCPP Energy Output Prediction
*   **Core Objective:** Developed a regression model to predict the net hourly electrical energy output (PE) of a Combined Cycle Power Plant based on ambient environmental variables.
*   **Tech Stack:** Python, Scikit-Learn (Regression Models), Seaborn.
*   **Key Deliverable:** [View Jupyter Notebook](./CCPP_Energy_Output_Prediction.ipynb) | [View Executive Summary](./CCPP_Executive_Summary.pdf)
*   **Summary:** This project addresses power plant operational volatility by utilizing machine learning regression models to accurately forecast net hourly electrical energy output based on ambient conditions. The resulting model allows grid operators to optimize thermodynamic efficiency and strategically plan maintenance schedules to minimize costly downtime. Ultimately, this approach bridges the gap between raw plant sensor metrics and high-level revenue and grid management.

### 5. AI-Driven ESG Fuel Emission Prediction & Sustainable Logistics
- **Core Objective:** Developed a predictive model to forecast fuel emissions and optimize logistics, driving ESG (Environmental, Social, and Governance) initiatives and sustainable supply chain operations.
- **Tech Stack:** Python, Pandas, Scikit-Learn, Matplotlib.
- **Key Deliverable:** [View Jupyter Notebook](./%235%20AI_Driven_ESG_Fuel_Emission_Prediction.ipynb) | [View Executive Summary](./%235%20Sustainable%20Logistics%20Optimisation.pdf)
- **Summary:** This project focuses on minimizing the carbon footprint of supply chain operations through machine learning. By accurately predicting fuel emissions based on transit variables, the model provides actionable insights to optimize routing and logistics. The findings are translated into a strategic executive presentation aimed at helping stakeholders balance operational efficiency with sustainability goals.
---

### 6. AI-Powered Maritime Fuel & Emissions Optimization
* **Core Objective:** Developed a machine learning model to predict maritime fuel consumption and optimize emissions, supporting sustainable shipping and logistics operations.
* **Tech Stack:** Python, Pandas, Scikit-Learn, Matplotlib.
* **Key Deliverable:** [View Jupyter Notebook](06%20AI_Powered_Maritime_Fuel_&_Emissions_Optimisation.ipynb) | [View Executive Summary](06%20Maritime_AI_Fuel_Emissions_Optimization.pdf)
* **Project Lifecycle & Methodology:**
  * **Business Challenge:** Reducing the high carbon footprint and volatile fuel costs associated with global maritime shipping.
  * **Stakeholder / Operational Painpoint:** Fleet managers and ESG officers struggle with unpredictable fuel consumption and lack actionable data to optimize voyage efficiency.
  * **Data & Requirements:** Historical voyage logs, transit variables (speed, draft, distance, weather conditions), and recorded fuel emissions metrics.
  * **AI/ML Approaches Consideration:** Evaluated various regression techniques (e.g., Random Forest, Gradient Boosting) to accurately map non-linear relationships between complex transit variables and fuel burn.
  * **Model & Technical Feasibility:** Successfully trained and validated a predictive regression model using Scikit-Learn, demonstrating strong accuracy and reliability in forecasting fuel usage per voyage.
  * **Business Findings:** The model identified specific optimal cruising speeds and routing conditions that drastically minimize fuel consumption without causing critical delivery delays.
  * **Recommended Intervention:** Deploy dynamic, AI-driven speed and route optimization recommendations directly to fleet operators prior to dispatch.
  * **Expected Business Value:** Significant reduction in annual fuel expenditures, improved regulatory compliance, and measurable advancement toward corporate ESG sustainability goals.
  * **Implementation Considerations:** Requires integrating the predictive model into existing maritime dispatch workflows and establishing a feedback loop with live operational data.

## 7. AI Delivery & Value Realization - Predictive Supply Chain & Sales Forecasting Framework

- *Core Objective:* Develop an end-to-end data pipeline using Python and T-SQL for machine learning and predictive modeling. The pipeline will focus on three key areas: late delivery risk, estimated time of delivery, and sales forecasting. The ultimate goal is to optimize inventory and operational efficiency. Additionally, the task includes establishing metrics and building a dashboard to track simulated ROI, fulfillment efficiency, and risk mitigation outcomes, creating project documentation (kickoff, workflow timeline, executive presentation), and documenting how the solution will scale within a cloud ecosystem with continuous data ingestion and automated reporting for a global logistics network.

- *Tech Stack:* Python, Pandas, Scikit-Learn, Matplotlib.
- *Key Deliverable:* [View Jupyter Notebook](07%20AI_Delivery_%26_Value_Realization_Portfolio_Project.ipynb) | [View Executive Presentation](07%20AI_Delivery_Value_Realization.pdf)
- *Summary:* This project outlines an end-to-end data pipeline for machine learning and predictive modeling focused on optimizing inventory and operational efficiency within a global logistics network. It addresses three key areas: late delivery risk, estimated time of delivery, and sales forecasting.
- The pipeline began with **Data Ingestion and Initial Exploration**, where a synthetic Coca-Cola supply chain dataset was loaded and analyzed for structure, quality, and features. This was followed by **Data Preprocessing and Feature Engineering**, which involved extracting time-based features and one-hot encoding categorical variables to prepare the data for modeling.
-  **Predictive Model Development** included:
-   **Sales Forecasting**: A RandomForestRegressor was trained to predict 'Sales_Volume', evaluated using MSE and R2, and a MAPE of 129.37% was calculated for accuracy assessment.
-   **Late Delivery Risk**: A RandomForestClassifier was developed to predict the likelihood of late delivery (Shipping_Delay_Days > 0), achieving an Accuracy of 0.78, Precision of 0.79, Recall of 0.98, and F1-Score of 0.88.
-   **Estimated Time of Delivery (ETA)**: A RandomForestRegressor was trained to predict 'Shipping_Delay_Days', yielding an MSE of 1.52 and an R2 of -0.05, indicating challenges in predicting exact delay days with the current features.

- A **Value Realization Dashboard** was established to track simulated ROI, fulfillment efficiency, and risk mitigation. Key metrics included a Fulfillment Efficiency (Precision for On-time) of 2.37%, Risk Mitigation (Recall for Late Deliveries) of 98.35%, and a Simulated ROI Value of $67,300.00 from risk mitigation efforts.

- **Cloud & Architecture Alignment** provided a conceptual cloud-based framework for scalable and automated continuous data ingestion, model execution, and reporting, leveraging services for data lakes, data warehouses, ML platforms, and BI tools.

- Finally, **Delivery & Governance Artifacts** were outlined, including templates for a Project Kickoff Document, Workflow Timeline, and Executive Presentation, to ensure agile execution and cross-functional alignment. The project demonstrates a comprehensive approach from data to deployment strategy, with clear documentation for stakeholders.
  
## 🛠️ Main Repository Structure

*   `Stock_Trade_Data_Analysis.ipynb`- Data exploration, time series analysis, and predictive modeling for stock trades.
*   `Stock_Trade_Data_Analysis.pdf` - Executive presentation summarizing the findings of the stock trade analysis.
*   `Final_DataCo_project.ipynb` - Data cleaning, feature engineering, and predictive modeling for the supply chain project.
*   `Fok Koe Kian Freddy_DataCo.pdf` - Formal 27-slide executive recommendation deck for DataCo Supply Chain Analytics & Predictive Modelling. 
*   `Yellow Taxi.ipynb` - Exploratory data analysis (EDA) and visualization codebase for taxi trip trends
*   `Automatidata_Executive_Summary.pdf` - Written a project progress updates and breakdown of analytics findings for New York Yellow Taxi Performance Analysis
*   `CCPP_Energy_Output_Prediction.ipynb` - Regression modeling for power plant energy output
*   `CCPP_Executive_Summary.pdf` - A 3 page executive summary outlining business context and objective, final model evaluation and business implications.
*   `#5 AI_Driven_ESG_Fuel_Emission_Prediction.ipynb` - Data exploration, feature engineering, and machine learning models for forecasting fuel emissions.
*   `#5 Sustainable Logistics Optimisation.pdf` - Executive presentation detailing AI findings and strategic recommendations for sustainable supply chain operations.
*   `06 AI_Powered_Maritime_Fuel_&_Emissions_Optimisation.ipynb` - Predictive modeling and optimization algorithms for maritime fuel efficiency and emissions reduction.
* `06 Maritime_AI_Fuel_Emissions_Optimization.pdf` - Executive summary outlining AI-driven strategies for sustainable maritime logistics.

---

## 📬 Connect With Me
*   **LinkedIn:** [(https://www.linkedin.com/in/freddy-fok-7074575/)]
*   **Email:** [freddyfok@gmail.com]
