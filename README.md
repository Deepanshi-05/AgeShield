# AgeShield
The rapid expansion of social media platforms has led to the growing problem of underage users accessing age-restricted content. While governments and organizations attempt to enforce legal age limits, many users bypass these restrictions using VPNs and false declarations.
# [Project Name]

**[Project Name]** is an AI-powered solution that verifies users' age and detects VPN usage to enforce online age restrictions. This project ensures safer online access by preventing underage users from accessing age-restricted platforms.

## Features

- **Facial Age Verification**: Uses advanced machine learning models to estimate the user's age from a photo.
- **VPN Detection**: Identifies VPN usage based on IP address analysis.
- **Secure Backend**: Handles user data and model predictions securely.
- **User-Friendly Frontend**: Allows users to upload images and receive real-time feedback.

## Project Architecture

![Architecture Diagram](#)

1. **Frontend**: User interface for submitting photos and receiving results.
2. **Backend**: Processes requests and integrates with machine learning models.
3. **ML Models**: Pre-trained models for age estimation.
4. **VPN Detection Module**: Identifies VPN or proxy usage using IP-based analysis.

## Technologies Used

- **Frontend**: React.js / HTML, CSS, JavaScript
- **Backend**: Flask / Django
- **Machine Learning**: TensorFlow / PyTorch
- **VPN Detection**: MaxMind GeoIP API
- **Database**: SQLite / MongoDB (optional)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2.python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

3.Install dependencies:
  pip install -r requirements.txt

4.Run the application:
 python app.py




