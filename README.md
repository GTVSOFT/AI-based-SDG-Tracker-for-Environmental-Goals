AI-based SDG Tracker for Environmental Goals
📌 Overview

This project demonstrates how Artificial Intelligence can be applied to monitor and evaluate progress toward environmental Sustainable Development Goals (SDGs) using synthetic geospatial and environmental data.
It uses a composite scoring method derived from multiple environmental indicators, enabling actionable insights for policymakers, researchers, and NGOs.
📊 Features

    Synthetic Dataset of 250+ geolocated points.

    Environmental indicators:

        CO₂ emissions per capita (t/year)

        Forest cover (%)

        Water quality index (0–100)

        Renewable energy share (%)

        Waste recycling rate (%)

    Composite SDG Score calculation.

    Framework for AI/ML-based prediction and classification of SDG progress.

    Easily adaptable to real datasets for real-world deployment.

🗂 Dataset

The dataset includes 250 synthetic locations with environmental metrics.
Download Dataset: synthetic_sdg_tracker_dataset.xlsx
id	latitude	longitude	co2_emissions_t_per_capita	forest_cover_percent	water_quality_index	renewable_energy_percent	waste_recycling_percent	sdg_composite_score
1	-3.92	21.88	9.54	68.12	82.33	50.12	35.76	58.42
...	...	...	...	...	...	...	...	...
🛠 Installation & Usage
1️⃣ Clone the Repository

git clone https://github.com/GTVSOFT/AI-based-SDG-Tracker-for-Environmental-Goals.git
cd AI-based-SDG-Tracker-for-Environmental-Goals

2️⃣ Install Dependencies

pip install pandas numpy scikit-learn matplotlib

3️⃣ Run the Script

python sdg_tracker.py

📈 Methodology

    Data Generation: Synthetic dataset with 5 environmental indicators.

    Composite Scoring: Weighted average approach to compute an SDG progress score (0–100).

    AI/ML Potential: The dataset can be fed into machine learning models to classify or predict SDG achievement levels.

    Visualization: Maps, charts, and time series plots can be created for in-depth analysis.

📂 Repository Structure

AI-based-SDG-Tracker-for-Environmental-Goals/
│-- data/
│   └── synthetic_sdg_tracker_dataset.xlsx
│-- sdg_tracker.py
│-- README.md
│-- requirements.txt

📜 License

This project is released under the MIT License.
👤 Author

Name: Amos Meremu Dogiye
GitHub: https://github.com/GTVSOFT
