
## Crowd Monitoring App with alerts

A real-time crowd counting system using CSRNet that sends email alerts when crowd size exceeds a configurable threshold. The app visualizes crowd density with heatmaps and provides informative HTML email alerts with plots.

Features

Upload images (jpg, jpeg, png) to estimate crowd count.
Heatmap overlay showing crowd density on the image.
Sends HTML email alerts with heatmap and comparison plots.
Configurable crowd threshold for alerts.
Fully in-memory processing (no disk writes).
![WhatsApp Image 2026-01-10 at 10 48 58 AM](https://github.com/user-attachments/assets/efbce6b5-7a6f-422c-a148-cd4d5b5d0ee0)
![WhatsApp Image 2026-01-10 at 11 21 50 AM](https://github.com/user-attachments/assets/b551fa87-23d9-4a37-8eae-a721ba2ddb14)
![WhatsApp Image 2026-01-10 at 11 22 07 AM](https://github.com/user-attachments/assets/6b6b132d-3242-43f6-b1ea-04d0ca62c7d1)
![WhatsApp Image 2026-01-10 at 10 51 43 AM](https://github.com/user-attachments/assets/13c43501-5678-4a98-8133-f7912502aa98)
![WhatsApp Image 2026-01-10 at 10 51 59 AM](https://github.com/user-attachments/assets/328a06da-e738-4d2d-8cc3-c0090c13b02e)
![WhatsApp Image 2026-01-10 at 10 52 20 AM](https://github.com/user-attachments/assets/438379cc-013a-4659-949c-18183434d62e)
![WhatsApp Image 2026-01-10 at 11 16 10 AM](https://github.com/user-attachments/assets/a1fa70ff-99ad-427d-b051-380314935d81)
![WhatsApp Image 2026-01-10 at 10 54 39 AM](https://github.com/user-attachments/assets/fd050962-7089-4bd2-99e4-1fbf078ba5e0)





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


