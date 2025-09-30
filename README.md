
## Crowd Monitoring App with alerts

A real-time crowd counting system using CSRNet that sends email alerts when crowd size exceeds a configurable threshold. The app visualizes crowd density with heatmaps and provides informative HTML email alerts with plots.

Features

Upload images (jpg, jpeg, png) to estimate crowd count.
Heatmap overlay showing crowd density on the image.
Sends HTML email alerts with heatmap and comparison plots.
Configurable crowd threshold for alerts.
Fully in-memory processing (no disk writes).



<img width="1899" height="926" alt="image" src="https://github.com/user-attachments/assets/79df2df6-fb4d-4817-ae98-2f158de74a8c" />
<img width="1889" height="883" alt="image" src="https://github.com/user-attachments/assets/882282bd-cc89-4263-a13c-75581c2d4f83" />
<img width="1533" height="781" alt="image" src="https://github.com/user-attachments/assets/c708c4cf-83a7-4770-a6b6-b45209f49b91" />
<img width="1574" height="663" alt="image" src="https://github.com/user-attachments/assets/8151f36b-6ba3-47f8-a137-c1be572c1410" />

## INSTALLATIONS 

git clone https://github.com/sgyatri/infosis-crowdmonitoring.git

cd infosis-crowdmonitoring

pip install -r requirements.txt

streamlit run src/app.py

## ENVIRONMENT VARIABLES 

Create a .env file in the root folder with your Gmail credentials:

SMTP_USER=your_email@gmail.com

SMTP_PASS=your_app_password


## Model Weights

- Place `csrnet_train.pth` inside the `csrnet_model/` folder.  
- This repo does **not include the trained model** due to file size limits.


