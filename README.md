# 4_ReebootBMSITM
# Faculty Hackathon- Lady Logicians

# Project Title: KrishiConnect: A Digital Platform for Direct Farmer-Buyer Engagement
KrishiConnect is a web based app designed to eliminate the middle layer in the agricultural supply chain. It enables farmers to list their crops and produce along with relevant details such as quantity, quality, expected price, and harvest date. On the other end, buyers can search for produce by category, location, or pricing, and directly initiate contact or place orders. The application will be able to help farmers set optimal prices by analyzing market trends, location, and crop attributes using AI-Driven Price Prediction module.

# Project Type
Software-dominant

# Problem Statement
Farmers face reduced profitability and market inefficiencies due to dependency on intermediaries in the agri-supply chain. The absence of a unified digital marketplace limits direct farmer–buyer transactions and data-driven decision-making. Our solution provides a mobile-first platform integrating real-time geolocation-based market access and AI-powered price prediction models using historical commodity datasets, enabling farmers to list produce, reach buyers directly, and set optimal selling prices based on predictive analytics.

# Proposed Solution (High-level)
A module in mobile/web platform:
   Direct Market Access (Marketplace)
   - Farmer uploads crop listing with images and details
   - Buyers browse listings, contact farmers directly
   - In-app chat (Language specific) / price negotiation
   - Location-based buyer suggestions
   - Order status & mail notifications
   - AI-Driven Price Prediction- Suggests a fair market price range based on crop type, quality, quantity,       location, and seasonality, using machine learning models trained on historical price datasets.

# Tech Stack 
- Frontend: React (web)
- Backend: Node.js (Express) / Python (FastAPI)
- Database: Firebase Realtime DB
- Image Storage: Firebase Storage
- Model: TensorFlow / PyTorch (image classifier)
- Deployment: Amazon Web Services
- Language Translation- Natural Language Processing
- Mail Notification API- SendGrid (by Twilio)
- Location based API- Google Maps Geocoding
- Machine Learning- Scikit-learn/ XGBoost for price prediction, trained on historical Agmarknet/APMC price   data

# Dataset
Government Sources
- Agmarknet (Directorate of Marketing & Inspection, Govt. of India)
- data.gov.in
Research / Open Datasets
- Kaggle: Indian Agriculture Dataset
- FAO (Food and Agriculture Organization)




