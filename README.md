# Smart Travel Alarm - Backend 🚀

## 📌 Overview
This repository contains the n8n workflow for the Smart Travel Alarm system.

## ⚙️ Functionality
- Receives user location
- Updates data in Supabase
- Calculates distance using OSRM API
- Triggers notification when near destination

## 🧰 Tech Used
- n8n (Automation)
- Supabase
- OSRM API
- ntfy

## 🧠 How it works
1. Webhook receives location  
2. Supabase stores data  
3. Distance calculated  
4. If condition met → alert triggered  
