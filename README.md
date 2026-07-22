# Portfolio

A collection highlights some of software projects I've worked on.

## Java101: Object-Oriented Programming:
**Type:** Java Coursework project
**Tech Stack:** Java  
**Summary:** Developed Java programs demonstrating strong understanding of object-oriented principles including classes, inheritance, polymorphism, and encapsulation. Implemented multiple problem-solving exercises and a coursework project, focusing on logic, structure, and efficient code design.     
**Status:** Completed  

https://github.com/Rassan1/Java101

---

## FlickFinder Movie API Project:
**Type:** REST API Development  
**Tech Stack:** Python, Django REST, SQLite  
**Summary:** Developed a movie database REST API as part of a startup-style project. Implemented routes for querying and filtering movie data, defining system requirements, and testing endpoints.    
**Status:** Completed  

https://github.com/Rassan1/theFlickFinderApp

---

## Cryptography Coursework:
**Type:** Coursework project  
**Tech:** Python, SageMath  
**Summary:** Implemented a block cipher, RSA decryption attack, and Shamir's Secret Sharing.  
**Status:** Completed  

https://github.com/Rassan1/Cryptography

---

## Music Catalogue Web App:
**Type:** Django + React coursework  
**Summary:** Built a full-stack web app for managing and browsing music albums with user/admin roles.  
**Tech:** Django REST Framework, React, PostgreSQL  
**Status:** Completed  

https://github.com/Rassan1/Music-Web-Application

---

## AI Image Classifier:
**Type:** Machine Learning coursework  
**Summary:** A Jupyter-notebook project that trains and evaluates models to classify **BreastMNIST** ultrasound images.  
Work includes model tuning, data augmentation, optimizer comparison, custom CNN design, metrics/plots, cross-validation, and fine-tuning **ResNet18**.  

https://github.com/Rassan1/AI-Image-classifier

**Tech used:**
- **Language/Runtime:** Python (Jupyter Notebook)
- **Core ML/DL:** PyTorch (`torch`), TorchVision (`torchvision.models.resnet18`)
- **Dataset:** **MedMNIST** — **BreastMNIST**
- **Metrics & CV:** scikit-learn (`precision/recall/F1/AUPR/ROC`, `KFold`)
- **Utils & Viz:** NumPy, Matplotlib, Seaborn, TQDM
- **Hardware:** CPU or CUDA GPU (auto-detect)    
**Status:** Completed    


## Road Collision Severity Prediction:
**Type:** Business Analytics & Data Visualisation coursework  
**Summary:** End-to-end data science pipeline predicting UK road collision severity (Fatal / Serious / Slight) using the official government STATS19 2024 dataset. Group work covered data cleaning, merging three tables (Collisions, Vehicles, Casualties), EDA, feature engineering, SMOTE for class imbalance, and preprocessing. Individual modelling work trained and evaluated a tuned Random Forest and Decision Tree classifier, with full evaluation including ROC/AUC curves, confusion matrices, precision-recall curves, and feature importance analysis.

https://github.com/Rassan1/Predicting-Road-Collision-Severity

**Tech used:**    
    
- **Language/Runtime:** Python (Jupyter Notebook, Google Colab)        
- **Data:** Pandas, NumPy        
- **Visualisation:** Matplotlib, Seaborn        
- **ML:** scikit-learn (Random Forest, Decision Tree, RandomizedSearchCV, StratifiedKFold), imbalanced-learn (SMOTE)                
- **Dataset:** UK DfT — STATS19 Road Casualty Statistics 2024                
- **Status:** Completed            


## Social Hub — Cross-Residence Student Community Platform:
**Type:** Final Year Dissertation Project (Full-Stack Web Application)        
**Summary:** Designed, built, and evaluated a full-stack prototype web platform to connect students across different private student accommodation providers (PBSA) through cross-residence event discovery, AI-powered recommendations, and real-time group chat. Addresses a documented gap in existing platforms — no current system combines cross-residence interaction, institutional identity verification, and personalised event recommendation in the PBSA context. Evaluated with 3 real University of Surrey students from 3 different accommodation providers: 100% task success rate, no assistance required, average post-task score of 4.71/5 across 8 dimensions.  

https://github.com/Rassan1/SocialHubProject

**Tech used:**        
- **Frontend:** React 18.2, React Router 6, Axios        
- **Backend:** Python 3.12, Django 5.0.1, Django REST Framework 3.14        
- **Database:** PostgreSQL 16        
- **Cache:** Redis 7 (typing indicators), Django LocMemCache (recommendations)        
- **Auth:** JWT via SimpleJWT — stateless, token blacklisting on logout        
- **AI / Recommendations:** scikit-learn (TF-IDF vectorisation + cosine similarity), NumPy        
- **Containerisation:** Docker, Docker Compose — single `docker-compose up --build` deployment        
- **Deployment:** Nginx (frontend proxy), ngrok (external evaluation access)      
**Status:** Completed          
