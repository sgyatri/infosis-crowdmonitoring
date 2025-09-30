
Crowd Monitoring App with alerts

A real-time crowd counting system using CSRNet that sends email alerts when crowd size exceeds a configurable threshold. The app visualizes crowd density with heatmaps and provides informative HTML email alerts with plots.

Features

Upload images (jpg, jpeg, png) to estimate crowd count.
Heatmap overlay showing crowd density on the image.
Sends HTML email alerts with heatmap and comparison plots.
Configurable crowd threshold for alerts.
Fully in-memory processing (no disk writes).

<img width="1256" height="583" alt="image" src="https://github.com/user-attachments/assets/4389860b-af8b-420e-9f55-c0f0fd5f80f3" />
<img width="1261" height="556" alt="image" src="https://github.com/user-attachments/assets/588520ea-91b0-4943-8743-625f80f34a85" />

Installation
cd CrowdMonitoringApp
pip install -r requirements.txt
streamlit run src/app.py
