# 🐦 Bird Range Prediction Web App

This is a lightweight web application that allows users to predict **bird presence**, **location**, and the **best time to observe birds** based on machine learning models trained on real birdwatching data from the Hambantota District.

The app serves as a frontend to three Flask APIs powered by trained Random Forest models, helping users answer:

- **Will I see this bird?**
- **Where can I see it?**
- **When is the best time to go birdwatching?**

## 🚀 Features

- 🔍 **Bird Presence Prediction**  
  Predicts if a bird is likely to be present at a specific location, time, and date.

- 📍 **Birdwatching Location Prediction**  
  Suggests the most likely locations to see a given bird based on time and season.

- 🕒 **Best Time Prediction**  
  Recommends the ideal month and hour to observe a specific bird at a location.

- 🌐 **Simple HTML Interface**  
  Enter query details and get natural-language predictions directly in your browser.

## ✅ Example Usage
Input:

Bird: Blue-tailed Bee-eater

Location: Bundala NP General

Date: 2025-04-04

Time: Morning

Prediction Type: Presence

Output:

"The Blue-tailed Bee-eater is likely to be present at Bundala NP General on Friday, 4/2025 in the morning."

## 📚 Acknowledgments
Dataset collected from eBird.org

