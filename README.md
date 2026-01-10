
## Crowd Monitoring App with alerts

A real-time crowd counting system using CSRNet that sends email alerts when crowd size exceeds a configurable threshold. The app visualizes crowd density with heatmaps and provides informative HTML email alerts with plots.

Features

Upload images (jpg, jpeg, png) to estimate crowd count.
Heatmap overlay showing crowd density on the image.
Sends HTML email alerts with heatmap and comparison plots.
Configurable crowd threshold for alerts.
Fully in-memory processing (no disk writes).

![WhatsApp Image 2026-01-10 at 10 48 58 AM](https://github.com/user-attachments/assets/6eebd836-70f7![WhatsApp Image 2026-01-10 at 10 51 43 AM](https://github.com/user-attachments/assets/f22d3daf-0a77-4c11-b749-cc7a0042df08)
-4133-8241-f4b12c816d91)
![WhatsApp Image 2026-01-10 at 10 51 59 AM](https://github.com/user-attachments/assets/eeaf3bdb-70a7-43da-95cd-27ff78125165)

![WhatsApp Image 2026-01-10 at 10 52 20 AM](https://github.com/user-attachments/assets/be622335-13a1-49e5-bfae-f5d7d86e7632)

![WhatsApp Image 2026-01-10 at 10 54 39 AM](https://github.com/user-attachments/assets/01e5a122-4013-4024-a9f8-cb1a8226dc61)
![WhatsApp Image 2026-01-10 at 11 11 08 AM](https://github.com/user-attachments/assets/7f5c0d39-f95b-40c6-9a35-ff170aa5459f)
![WhatsApp Image 2026-01-10 at 11 11 29 AM](https://github.com/user-attachments/assets/e48158e5-aca5-416a-9f49-dfb0834af130)


## INSTALLATIONS 

git clone https://github.com/sgyatri/infosis-crowdmonitoring.git

cd infosis-crowdmonitoring

pip install -r requirements.txt

streamlit run src/app.py

## ENVIRONMENT VARIABLES 

Create a .env file in the root folder with your Gmail credentials:

SMTP_USER=your_email@gmail.com

SMTP_PASS=your_app_password

ALERT_RECIPIENT=recipient_email@gmail.com


## Model Weights

- Place `csrnet_train.pth` inside the `csrnet_model/` folder.  
- This repo does **not include the trained model** due to file size limits.


