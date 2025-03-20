Accident Analysis Using PySpark

Overview

This project analyzes traffic accident data using PySpark. It explores patterns based on time, vehicle type, junction conditions, urban vs. rural trends, and district-level accident trends.

🚀 Key Analyses

📅 Temporal Accident Patterns

Question: What are the most accident-prone months, days, and time slots? Is there a pattern between weekdays and weekends?

Analysis:

Time-series analysis to detect accident peaks.

Comparing accident rates between weekdays and weekends.

Visualizing accidents across different time slots (morning, afternoon, evening, night).

🚙 Vehicle Type and Casualties

Question: Which vehicle types are involved in the most severe accidents? Do certain vehicles correlate with higher casualty numbers?

Analysis:

Grouping accidents by vehicle type to compare severity levels.

Identifying whether motorcycles, trucks, or cars contribute more casualties.

Exploring casualty trends for commercial vs. personal vehicles.

🚦 Junction Control and Accidents

Question: Does the presence or absence of junction control (e.g., traffic signals, roundabouts) impact accident frequency and severity?

Analysis:

Comparing accident rates at controlled vs. uncontrolled intersections.

Identifying the most dangerous junction types.

Analyzing the effect of traffic signals on accident reduction.

🚗 Multi-Vehicle Collisions

Question: What percentage of accidents involve multiple vehicles? How does severity change as the number of vehicles increases?

Analysis:

Grouping accidents by the number of vehicles involved.

Identifying whether multi-vehicle crashes are more severe.

Comparing single-vehicle vs. multi-vehicle accident trends.

🌆 Rural vs. Urban Accident Trends

Question: Are urban areas more accident-prone than rural areas? How does accident severity differ?

Analysis:

Comparing accident frequency in urban vs. rural settings.

Identifying rural-specific risk factors (e.g., lack of lighting, sharp turns).

Using spatial analysis to detect accident concentration.

🏙️ District-Level Accident Trends

Question: Which local authority districts report the highest number of accidents? Are certain regions more accident-prone due to weather, traffic, or road types?

Analysis:

Ranking districts by total accident count.

Analyzing district-wise weather impact on accident severity.

Identifying high-risk road types in different districts.

🛠️ Technologies Used

Python (PySpark, Pandas)

Apache Spark

Data Visualization Tools

📂 Dataset

The dataset includes accident records with fields such as date, time, severity, vehicle type, road conditions, and geographic location.

🚀 How to Run

Install PySpark: <pip install pyspark>

Load the dataset.

Run the provided PySpark scripts for analysis.

📜 License

This project is open-source and available for further modifications.
