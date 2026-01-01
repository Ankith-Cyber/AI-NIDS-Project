AI-Powered Network Intrusion Detection System (NIDS)
📌 Project Overview
This project is an interactive web-based dashboard designed to detect potential cyberattacks in network traffic. Using the Random Forest machine learning algorithm, the system classifies network connections into two categories: Benign (safe) and Malicious (threats).

🚀 Features
Synthetic Data Generation: Mimics real-world network traffic logs based on the CIC-IDS2017 structure.

Real-Time Training: Users can adjust training parameters like the number of trees and data split size directly from the sidebar.

Performance Metrics: Displays accuracy scores and a confusion matrix to visualize how well the AI is performing.

Live Traffic Simulator: A manual testing interface where users can input packet details to see if the AI flags them as an attack.

🛠️ Technologies Used
Python: Core programming language.

Streamlit: For the interactive web dashboard.

Scikit-Learn: For the Random Forest machine learning model.

Pandas & NumPy: For data manipulation and synthetic log generation.

Seaborn & Matplotlib: For data visualization and confusion matrix plotting.

📋 How to Use
Install Requirements:

Bash

pip install streamlit pandas numpy scikit-learn seaborn matplotlib
Run the Application:

Bash

streamlit run app.py
Train the Model: Use the sidebar to set parameters and click "Train Model Now".

Test for Attacks: Scroll to the "Live Traffic Simulator" and enter custom values for flow duration and packet counts to test the AI's detection.

Why use Random Forest for NIDS?
The Random Forest algorithm is highly effective for network security because it builds multiple decision trees and merges them together to get a more accurate and stable prediction. It is particularly good at identifying patterns in complex network features like flow duration and packet length.