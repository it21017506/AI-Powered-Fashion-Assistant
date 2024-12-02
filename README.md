# AI-Powered Fashion Assistant

An innovative project that leverages Artificial Intelligence to recommend clothing and accessories based on user preferences, current fashion trends, and weather conditions. This assistant combines machine learning with a React-based frontend to deliver a personalized and interactive experience for users.

---

## Key Features

### 1. Personalized Recommendations
- Users can input preferences such as style, favorite colors, and occasions.
- The assistant suggests clothing and accessories tailored to their specific input.

### 2. Weather-Aware Suggestions
- Integrates a live weather data API to provide outfit recommendations suitable for current weather conditions.

### 3. Trend Analysis
- Uses machine learning to analyze trending styles on platforms like Instagram and Pinterest.
- Includes popular trends in recommendations to ensure relevance.

### 4. Virtual Try-On (Optional Advanced Feature)
- Allows users to upload photos and virtually try on outfits for a more engaging experience.

---

## Technologies

### Frontend
- **React**: For creating an interactive and responsive user interface.

### Backend
- **Node.js with Express**: For building RESTful APIs and handling server-side logic.

### Database
- **MongoDB**: To store user preferences and recommendation data.

### AI/ML
- **Convolutional Neural Networks (CNNs)**: For image analysis and style matching.
- **Datasets**: Uses datasets like **DeepFashion** and **Fashion-MNIST** for training the model.
- **Libraries**: TensorFlow, PyTorch for implementing machine learning algorithms.

### APIs
1. **OpenWeatherMap API**: To fetch live weather data.
2. **Social Media Trends**: Scrapes publicly available social media data using Python tools for trend analysis.

---

## Installation Guide

### Prerequisites
- Node.js (v18.x or later)
- Python (v3.10 or later)
- MongoDB (local or cloud instance)
- OpenWeatherMap API key

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/it21017506/AI-Powered-Fashion-Assistant.git
   cd AI-Powered-Fashion-Assistant
