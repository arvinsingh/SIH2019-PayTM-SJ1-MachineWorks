# ClusTMPay | Smart India Hackathon 2019 

<h1 align="center">
  <img src="resources/SIH_logo.png"/>
</h1>

## Technology Bucket
Software - Mobile App development

## Title
Problem Statement: SJ1 - Reduce the amount of push notifications require for e-commerce apps

## Organization
<img src="resources/paytm.jpg">

## Description
Developer would have to build a solution using Artificial Intelligence or some other mechanism to reduce the amount of push notifications sent by e-commerce apps. Currently push notifications are generally sent based on a fixed schedule or some trigger in most apps. This creates multiple notifications every week and irritates the user. The intent should be to only send notifications when the users intent is there to purchase a particular product. Sending push notifications or emails without any user intent to buy that category of product creates frustration to the user. So only when user has intention to buy something the notifications or emails should. The developer has to use a technical method to find that intent using big data and then send notifications or emails according to that method.

**PRESENTATION IN THE RESOURCES FOLDER**

## Organization
<img src="resources/layout.png">

## Installation
Clone the github repositor or type the command **git clone https://github.com/arvinsingh/SIH2019-PayTM-SJ1-MachineWorks** in the git bash.

## Executing or running the program
1) React Analysis Panel
- Install dependencies:
npm install

- Serve with hot reload at localhost:3000:
npm start

2) Create database PostgreSQL
name=clustmpay
username=robomx
password=robomx

3) Celery Job Scheduler to fetch Firebase data

- open terminal 1: 
	celery -A configurations beat --loglevel=info

- open terminal 2: 
	celery -A configurations worker -l info -E

4) Django Web server
virtualenv env -p python3
source env/bin/activate
pip install-r requirements.txt
python manage.py runserver

5) Android App
open Android Studio
Let it sync the gradle files
Click on Run button after connecting emulator/mobile

## Technology stack

- JDK 8
- Android SDK v24
- PostgreSQL
- Django v2.1.7
- ReactJS
- Celery v4.2.1
- Redis v3.2.0
- Python 3.6
- SciKit Learn v0.20.3
- Pandas v0.24.1
- NumPy v1.16.2
- Matplotlib v3.0.3
- Apache Cassandra v1.5.5

## API used

[Recombee](www.recombee.com)


## Team
  1) Mexson Fernandes (Leader)
  2) Sourabh Choubey
  3) Arvinder Pal Singh Bali
  4) Priya
  5) Ansh Varun
  6) Ajay Thakur
  7) Himanshu Chauhan (Mentor)
  

## Steps
	# Backend
		export GOOGLE_APPLICATION_CREDENTIALS = BASE_DIR + "firebase_key.json"
