# Smart India Hackathon Workshop
# Date: 08|09|2025
## Register Number: 212224100057
## Name: SRILAKSHMI.B.H
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
1. AI-Powered Crop Recommendation
   1.Personalized crop suggestions based on.
   
     -Soil health data (pH, nutrients, moisture).
   
     -Local weather forecast (rainfall, temperature).

     -Historical yield data and crop rotation cycles.
   
   2.ML models predict best crop choice, sowing window, and yield estimate.

3. Smart Advisory System

   -Fertilizer & Irrigation Guidance → dosage & timing alerts via SMS/IVR/app.
   
   -Pest & Disease Forecasting → early warnings using satellite + predictive ML.
   
   -Harvest & Storage Tips → reduce post-harvest losses.

4. Multi-Channel Farmer Support

   -Mobile App (lightweight, multilingual, voice-enabled).
   
   -SMS & IVR Service → inclusive for non-smartphone users.

## Technical Approach
1.System Architecture

  * Data Layer
    
      -Weather APIs (IMD, OpenWeather, ISRO satellite data).
    
      -Government soil health card database or IoT soil sensors.
    
      -Market price APIs / mandi data.
    
  * Processing & AI Layer
    
      -ML models for crop selection, yield prediction, pest/disease forecasting.
    
      -Rule-based engine for simple advisories (fertilizer dosage, irrigation reminders).
    
      -NLP models for voice queries in regional languages.

## Technology Stack

  1.Backend: Python (FastAPI / Django) + Node.js for microservices.
  
  2.AI/ML: TensorFlow / PyTorch, scikit-learn, pretrained agri-disease models.
  
  3.Database: PostgreSQL + TimescaleDB (for time-series weather data).
  
  4.Cloud & IoT: AWS / Azure / NIC cloud; optional low-cost soil sensors (LoRa, Arduino).
  
  5.Frontend: React Native for mobile app (Android/iOS); SMS gateway (Twilio / Gupshup).

## Feasibility and Viability

1.TECHNICAL FEASIBILITY

2.OPERATIONAL FEASIBILITY

3.ECONOMIC FEASIBILITY

## Impact and Benefits

<img width="1536" height="1024" alt="impacts" src="https://github.com/user-attachments/assets/eb7e3336-1e6c-48fb-9f0b-21d0e8150e40" />


## Research and References

1.AI-Driven Crop Disease Detection & Smart Irrigation (Fuzzy Logic + IoT)

2.AI-Powered Web Advisory for Small Farmers (No IoT)

3.NICRA (National Innovations in Climate Resilient Agriculture)
