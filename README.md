# 🌿 Water Footprint Analyzer

**Water Footprint Analyzer** is an AI-powered mobile application that enables users to assess the environmental impact of agricultural products based on their **Green**, **Blue**, and **Grey** water footprints. Designed with a focus on accessibility, sustainability, and data accuracy, this app helps raise awareness about water consumption and supports eco-conscious decision-making among consumers.

> 📌 Submitted for the **Smart India Hackathon 2025**, under Problem Statement ID **1689**:  
> *"Use of Digital Technology to calculate Water Footprints for different Agricultural Products."*

---

## 📱 Key Features

- **Real-time Object Detection**  
  Leverages TensorFlow Lite to classify agricultural products via the device camera.

- **Offline Product Search**  
  Supports quick, offline access to water footprint data using a preloaded dataset.

- **Multi-Language Interface**  
  Offers localized content in 8 Indian languages: Tamil, Hindi, Telugu, Bengali, Kannada, Malayalam, Marathi, and English.

- **Power BI Analytics Integration**  
  Visualizes insights like comparative water consumption and user interaction metrics.

- **Questionnaire-based Customization**  
  Calculates water footprint by incorporating user inputs on packaging, transportation, and processing.

---

## 📊 Water Footprint Metrics

| Component| Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| Green    | Rainwater used during cultivation                                           |
| Blue     | Surface and groundwater used in irrigation                                  |
| Grey     | Freshwater required to dilute pollutants to meet water quality standards    |
| Total    | Sum of all three categories in liters per kilogram (L/kg)                   |

---

## 🛠️ Technology Stack

| Domain            | Technology Used                      |
|------------------ |--------------------------------------|
| Mobile Framework  | React Native (Expo)                  |
| Backend Services  | Node.js (data processing)            |
| ML Integration    | TensorFlow Lite (MobileNet Model)    |
| Data Management   | Local JSON (offline access)          |
| Visualization     | Power BI Embedded Analytics          |
| Localization      | Manual translation (no APIs used)    |

---

## 📁 Project Structure


---

## 🚀 Getting Started

### Prerequisites
- Node.js ≥ 14.x
- npm ≥ 6.x
- Expo CLI: `npm install -g expo-cli`

### Installation

git clone https://github.com/PragadheeshM/water-footprint-analyzer.git
cd water-footprint-analyzer
npm install
expo start
Scan the QR code using the Expo Go app (iOS/Android) to launch the application

###🎯 Use Case & Impact
Educates users on the hidden water costs of everyday food products.

Helps consumers make responsible choices based on environmental impact.

Supports UN Sustainable Development Goal 6: Clean Water & Sanitation.

Scalable for use in government sustainability programs, schools, and retail eco-labeling.

###🔍 Sample Dataset Entry
json
{
  "product": "Apple",
  "green": 700,
  "blue": 150,
  "grey": 50,
  "total": 900
}
Each entry denotes water usage in liters per kilogram (L/kg).

###🌐 Languages Supported
🇬🇧 English (default)

🇮🇳 Tamil

🇮🇳 Hindi

🇮🇳 Telugu

🇮🇳 Bengali

🇮🇳 Kannada

🇮🇳 Malayalam

🇮🇳 Marathi

###🧠 AI Model Integration
Model: MobileNet (custom-trained on agricultural products)

Inference: TFLite model integrated using React Native plugins

Process: Detects object → Classifies label → Queries dataset

###📊 Embedded Analytics (Power BI)
Visual dashboards include:

Water consumption breakdown (by color)

Product-wise comparison

User interaction trends

Analytics can be customized based on organizational or government needs.
--
🧑‍💻 Authors
Pragadheesh – AI & App Developer

Churchill L. – Backend & Data Processing

Prasanth KR. – Design & Visualization

Developed by Final Year B.Tech AI & DS students at M. Kumarasamy College of Engineering


--
CSR sustainability programs

Governmental awareness campaigns

Smart village/smart city digital initiatives
--
📬 Contact & Collaboration
For demo access, integration support, or academic/industry collaboration:

📧 Email: pragadheeshpragadheesh75@gmail.com
🔗 LinkedIn: www.linkedin.com/in/pragadheesh-m-500218253
📁 GitHub: https://github.com/PragadheeshM


