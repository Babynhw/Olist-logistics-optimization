🚀 Olist Logistics Optimization: Uncovering the Root Causes of Delivery Delays
Data Source: [Brazilian E-Commerce Public Dataset by Olist]- Link: [(https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?resource=download)]
--------------------------------------------------------------------------------------------------------------------------------------------------
📌 Project Overview
This project performs an in-depth diagnostic analysis of the logistics and delivery network for Olist, the largest department store in Brazilian marketplaces. By analyzing over 110,000+ orders, the objective is to move beyond superficial metrics (like overall On-Time Delivery rate) to identify the true bottlenecks in the supply chain, evaluate geographic inequalities, and propose data-driven fulfillment strategies.
--------------------------------------------------------------------------------------------------------------------------------------------------
🎯 Business Objectives
Assess Real Performance: Evaluate true delivery speeds versus estimated delivery dates (EDD) to uncover forecasting biases.

Geographic Diagnostics: Map the "FTL (Full Truckload) Trap" and measure the impact of inter-state vs. intra-state distances on lead times.

Seller Accountability: Quantify how seller preparation time (Handling Time) impacts the overall delivery pipeline.

Strategic Recommendations: Develop actionable strategies (e.g., Regional Fulfillment, SLA updates) to reduce costs and improve customer satisfaction.
--------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Tech Stack & Tools
Language: Python 3

Data Manipulation: pandas, numpy (Vectorized haversine distance calculations)

Data Visualization: matplotlib, seaborn, plotly (Interactive Bubble Maps)

Geospatial Analysis: folium (Heatmaps, Marker Clusters)
--------------------------------------------------------------------------------------------------------------------------------------------------
📊 Core Analytical Framework (7 Stages)
Executive Summary: Macro-level view of revenue and order volume.

OTD & Reliability Analysis: Identifying the 4.2% extreme late deliveries and 59.5% early deliveries.

Speed Analysis: Measuring distribution skewness and peak-season vulnerabilities.

Geographic Analysis: Using Pareto principle to pinpoint 3 specific states causing the majority of delays.

Seller Performance: Isolating the top sellers causing fulfillment bottlenecks.

Root Cause Analysis: Quantifying the exact impact of Geography, Product Type (Bulky vs. Standard), and Seller Behavior.

Strategic Recommendations: Proposing the shift to Fulfillment by Olist (FBO) and Dynamic ETA.
--------------------------------------------------------------------------------------------------------------------------------------------------
💡 Key Insights Discovered
🎭 The EDD Bias (The "Safe Promise" Paradox): Olist achieves a 92.1% On-Time Delivery rate primarily because the Estimated Delivery Date is set 11.4 days longer than the actual delivery time. This over-caution sacrifices competitive advantage in speed.

🩸 The Prep-Time Bottleneck: Seller handling time accounts for 23.3% of the entire delivery journey. Without strict SLA enforcement on packaging, optimizing the Last-Mile delivery is ineffective.

🗺️ The 2x Geographic Penalty: Inter-state shipping takes nearly double the time (~13.8 days) compared to intra-state shipping (~5.2 days). The delays are concentrated regionally (North/Northeast) due to infrastructure limits, not nationwide failure.

📦 Bulky Cargo Latency: Oversized products experience a 13.6% higher latency, proving that standard parcel networks cannot efficiently handle large items without a dedicated LTL (Less-than-truckload) strategy.
--------------------------------------------------------------------------------------------------------------------------------------------------
🚀 Proposed Action Plan
Short-term: Enforce a strict 24-48h dispatch SLA for the top 10 sellers with the highest handling times. Implement Fixed Window Departures to break the "Wait for Full Truck" trap in remote postal nodes.

Long-term: Transition heavily delayed regions into a Regional Fulfillment (Satellite Warehouse) model to convert Inter-state operations into Intra-state deliveries, effectively cutting lead times by 60%.
--------------------------------------------------------------------------------------------------------------------------------------------------
🤝 Contact
Author: [Trần Cao Quỳnh Như]
Email: [trancaoquynhnhucmg@gmail.com]
