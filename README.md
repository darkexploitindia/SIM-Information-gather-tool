# SIM-Information-gather-tool

install this tool in your kali linux

Step 1: Install python3-venv (if not already installed)

bash
sudo apt update

sudo apt install python3-venv


Step 2: Create the virtual environment

bash

cd ~/Desktop/telecom_project

python3 -m venv venv

Step 3: Activate the virtual environment

bash

source venv/bin/activate

Step 4: Install the packages

bash

pip install phonenumbers rich requests

python telecom_tracker.py


📋 API KEY SETUP GUIDE:
Google Maps API Key:
bash
1. Go to: https://console.cloud.google.com/
2. Create new project or select existing
3. Enable: Geocoding API, Maps Static API, Places API
4. Create credentials → API Key
5. Restrict key to your IP (optional)
6. Copy API Key and paste in tool
2. = OpenCellID API Key:
bash
1. Register at: https://www.opencellid.org/
2. Go to Dashboard → API Keys
3. Generate new API Key (free tier available)
4. Copy Key and paste in tool
3 = Facebook Graph API Token:
bash
1. Go to: https://developers.facebook.com/
2. Create new app
3. Get App ID and App Secret
4. Generate User Access Token with permissions:
   - public_profile
   - user_location (if available)
   - email (optional)
5. Note: Phone number lookup requires business verification
