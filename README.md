# ImmunoGuard-AI
ImmunoGuard AI – Rheumatoid Arthritis Flare Prediction System

Overview

ImmunoGuard AI is an intelligent healthcare system designed to forecast Rheumatoid Arthritis (RA) flares 24–72 hours in advance using wearable biometrics, environmental triggers, and patient-reported symptoms.

The platform combines machine learning, time-series analysis, and real-time environmental monitoring to provide users with early warnings and personalized preventive recommendations.

⸻

Live Deployment

🚀 Deployment Link:
ImmunoGuard AI Live Demo￼

⸻

System Architecture

1. Frontend Layer – User Interface & Data Acquisition

The frontend serves as the patient-facing interface and acts as the central interaction hub of the platform.

Tech Stack

* React.js
* Progressive Web App (PWA)

Core Features

* Real-Time Dashboard
    * Displays the live Flare Risk Index
    * Provides actionable preventive recommendations
* Symptom Logging
    * Enables users to manually record symptoms such as:
        * Pain
        * Joint stiffness
        * Fatigue
* Health Analytics
    * Visualizes:
        * Historical symptom trends
        * Medication adherence
        * Correlation between symptoms and environmental factors

⸻

2. Backend Layer – API Gateway

The backend acts as the central nervous system of the application, handling communication between the frontend, external APIs, and machine learning models.

Tech Stack

* Python Flask

Database

* SQLite (used for MVP development)

Core Features

* Authentication System
    * Secure user login
    * Session token validation
* Data Aggregation Pipeline
    * Collects JSON payloads from the frontend
    * Processes biometric and environmental data
    * Prepares structured data for ML inference

⸻

3. Intelligence Core – AI/ML Engine

The AI engine powers the predictive capabilities of ImmunoGuard using a multi-agent machine learning architecture.

Tech Stack

* Python
* Scikit-Learn
* XGBoost
* TensorFlow / Keras

Core Models

Temporal Agent (LSTM)

A Long Short-Term Memory (LSTM) neural network that analyzes sequential health data trends such as:

* Heart Rate Variability (HRV)
* Sleep fragmentation
* Resting heart rate changes

Environmental Agent (XGBoost)

An XGBoost-based prediction model that evaluates environmental flare triggers including:

* Air Quality Index (AQI)
* Humidity
* Temperature
* Barometric pressure

Decision Fusion Agent

Combines weighted outputs from specialized agents to generate the final:

* 1–10 Flare Risk Classifier

⸻

4. External Integrations Layer

The platform integrates external APIs to continuously stream real-world biometric and environmental data.

Wearable Integrations

* Google Fit API
* Fitbit API

Environmental APIs

* OpenWeatherMap API

AI Recommendation Engine

* OpenAI / Groq LLM Integration

The recommendation engine converts numerical flare risk scores into:

* Personalized preventive advice
* Plain-text health recommendations
* Early intervention guidance

⸻

Key Features

* Real-time RA flare prediction
* Personalized health recommendations
* Multi-agent AI architecture
* Wearable device integration
* Environmental risk analysis
* Historical health analytics
* Progressive Web App support
