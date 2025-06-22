# CP Hactiv8 Rice Production Analysis in Sumatera - AI-Powered Insight
AI-Assisted Analysis of Rice Production, Harvest, and Climate Factors in Sumatera

📖 Project Overview

This project explores the relationship between rice production, harvest area, and climatic factors (rainfall, humidity, and temperature) across various provinces in the Sumatera region of Indonesia. With the integration of Large Language Models (LLM), data exploration becomes more intuitive and interactive using natural language prompts.

🗂️ Raw Dataset

File Name: Data_Tanaman_Padi_Sumatera_version_1.csv

Rows: 224 entries

Columns:

- Provinsi - Province name

- Tahun - Year

- Produksi - Rice production (in tons)

- Luas Panen - Harvest area (in hectares)

- Curah hujan - Annual rainfall (mm)

- Kelembapan - Humidity (%)

- Suhu rata-rata - Average annual temperature (°C)

Dataset Link (https://www.kaggle.com/datasets/ardikasatria/datasettanamanpadisumatera)

💡 Insights & Findings

Here are some insights derived from the dataset using AI analysis:

1. Rice production shows an overall increasing trend across Sumatera, with yearly fluctuations likely influenced by climate.

2. Rainfall and production exhibit a positive correlation, suggesting rainfall impacts yield.

3. Average temperature is slightly increasing, possibly reflecting long-term climate changes.

4. Sumatera Utara and Sumatera Barat are among the top-performing provinces in terms of average rice production.


🤖 AI Support Explanation

The project integrates a Large Language Model (LLM) via LangChain and Replicate to assist with:

📊 Data analysis using natural language commands

🧠 Correlation analysis between climate and agriculture

🖌️ Automated visualizations and summaries

Model Configuration

parameters = {
    "top_k": 3,
    "top_p": 0.95,
    "max_tokens": 1024,
    "temperature": 0.4,
    "repetition_penalty": 1.15
}

This configuration helps ensure logical, data-focused, and non-repetitive outputs.


💬 Example Prompts

Prompt || Description

Create a line chart of total rice production per year across all provinces || National trend of rice production

Which province has the highest average rice production? || Identify top producing provinces

Analyze the correlation between rainfall, humidity, temperature, and rice production || Climate influence analysis

Group the average rainfall, humidity, and temperature by province || Regional weather profile

Is there a linear relationship between harvest area and rice production? || Harvest efficiency evaluation


Built with LangChain, Replicate, and Pandas for seamless AI-driven data exploration.

Feel free to fork this project or submit pull requests to enhance its capabilities!
