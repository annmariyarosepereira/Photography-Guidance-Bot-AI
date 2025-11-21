Photography Guidance Bot – AI Desktop Assistant
📌 Overview

The Photography Guidance Bot is an AI-powered desktop application built using Python and Tkinter that helps photographers capture better images by providing:

Real-time weather-based suggestions

Image enhancement tools

RGB histogram analysis

Clean full-screen login system

Interactive dashboard UI

This project integrates Artificial Intelligence, API integration, and image processing, and was developed as part of INT-428 (AI Essentials) CA-3 Skill-Based Project.
(Refer to full project report inside /project_report/CSE428CA3.pdf) 

CSE428CA3 (1)

🎯 Features
✔ 1. Full-Screen Login System

Professional login window with username/password fields.
(See page 10 of the project report) 

CSE428CA3 (1)

✔ 2. Real-Time Weather-Based Photography Tips

Using OpenWeatherMap API, the bot provides tips on:

ISO settings

Shutter speed

Aperture

Lighting conditions

Weather popup appears automatically on the dashboard.
(Shown in pages 11–12) 

CSE428CA3 (1)

✔ 3. Image Upload & Enhancement Tools

Users can upload an image and apply:

Brightness adjustment

Contrast improvement

Sharpness enhancement

(Demonstrated in pages 13–14) 

CSE428CA3 (1)

✔ 4. RGB Histogram Visualization

Displays Red, Green, Blue intensities using matplotlib.
Helps photographers analyze exposure & light distribution.

(See page 15 screenshot) 

CSE428CA3 (1)

✔ 5. Smart Photography Tips Module

Based on:

Weather data

Image analysis

Composition rules

Exposure settings

🧱 Architecture

According to the CA3 project report:

1. Interface Layer (Frontend)

Handles GUI:

Login page

Dashboard

Image viewer

Tips panel

Weather popup
(Pages 4–5) 

CSE428CA3 (1)

2. Styling Layer

Tkinter theme consistency:

Colors

Layouts

Fonts

Popup design
(Pages 5–6) 

CSE428CA3 (1)

3. Logic Layer

Implements:

Image processing

Histogram generation

Weather API fetching
(Pages 6–7) 

CSE428CA3 (1)

4. Data Layer

Uses OpenWeatherMap API to fetch real-time weather.
(Page 7–8) 

CSE428CA3 (1)
