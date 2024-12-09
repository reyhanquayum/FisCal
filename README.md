# FisCal: Budget tracker calendar with fiscal analysis
[![CI/CD](https://github.com/software-students-fall2024/5-final-theonepiece/actions/workflows/CI-CD.yml/badge.svg)](https://github.com/software-students-fall2024/5-final-theonepiece/actions/workflows/CI-CD.yml)
## Description
FisCal is a budget-tracking calendar app with AI integration that helps users manage their personal spending. Users can manually input expenses by adding events to a calendar, specifying the date, time, title (e.g., what they spent money on), and the amount spent. The app aggregates data to display daily, weekly, and monthly spending summaries and employs AI to analyze spending habits and provide personalized advice.

## Deployment
The app is live and can be accessed at: [http://67.207.91.193:5000/](http://67.207.91.193:5000/)

## Gallery

<img src="https://github.com/user-attachments/assets/260e2fc6-753e-424c-9168-11bd00eec4bd" alt="67 207 91 193_5000_user_login(iPhone 14 Pro Max)" width="300">
<img src="https://github.com/user-attachments/assets/8af52d33-493c-4034-b009-5e011b3d4b9f" alt="67 207 91 193_5000_calendar(iPhone 14 Pro Max)" width="300">
<img src="https://github.com/user-attachments/assets/d5f6d589-83ca-46f2-8a4d-1e4070b59439" alt="67 207 91 193_5000_analytics(iPhone 14 Pro Max)" width="300">
<img src="https://github.com/user-attachments/assets/ddb84d64-566a-461c-a6f5-59d0be263686" alt="67 207 91 193_5000_ai(iPhone 14 Pro Max)" width="300">
<img src="https://github.com/user-attachments/assets/2fa77422-333e-481e-9db0-bbd4ed13b594" alt="67 207 91 193_5000_user_search-events_entertainment(iPhone 14 Pro Max)" width="300">
<img src="https://github.com/user-attachments/assets/f847be0b-8324-4286-8640-06b37cb318cb" alt="67 207 91 193_5000_calendar(iPhone 14 Pro Max) (1)" width="300">


## Docker Image

[![Docker Image Version](https://img.shields.io/docker/v/aesuran/theonepiece)](https://hub.docker.com/r/aesuran/theonepiece)
[![Docker Pulls](https://img.shields.io/docker/pulls/aesuran/theonepiece)](https://hub.docker.com/r/aesuran/theonepiece)

The images for the web-app and MongoDB subsystem are deployed on Docker Hub at this [link](https://hub.docker.com/r/aesuran/theonepiece).

## Team Members
|Reyhan Abdul Quayum|Rashed Alneyadi|Sia Chen|Chloe Han|
|:--:|:--:|:--:|:--:|
|<a href='https://github.com/reyhanquayum'><img src='https://avatars.githubusercontent.com/u/115737572?v=4' width='40px'/></a>|<a href='https://github.com/brshood'><img src='https://avatars.githubusercontent.com/u/133962779?v=4' width='40px'/></a>|<a href='https://github.com/MambiChen'><img src='https://avatars.githubusercontent.com/u/122314736?v=4' width='40px'/></a>|<a href='https://github.com/jh7316'><img src='https://avatars.githubusercontent.com/u/95545960?s=88&v=4' width='40px'/></a>|

## Setup Instructions

Instructions for setting up the app manually on your local machine.

### Prerequisites
* Docker Desktop

### Installation
1. Clone the repo:
```bash
git clone https://github.com/software-students-fall2024/5-final-theonepiece.git
cd 5-final-theonepiece
```
2. If using Docker Desktop application, start Docker Desktop if you haven't already
3. Add a .env file on the root directory, in the format shown in the example.env file and the actual contents  will be delivered to graders via discord
4. Build and start the containers with Docker Compose
```bash
docker-compose down
docker-compose build
docker-compose up
```

5. Access the Web App.

    You should be able to locally access web-app running on http://127.0.0.1:5000/

6. Sign up using by inputting your custom info and proceed to log in and use the app
  

## Thank you!
