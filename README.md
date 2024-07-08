# Cloudburst Detection System

The Cloudburst Detection System is an innovative Android app designed to predict and mitigate the impact of cloudbursts using machine learning models and real-time weather data. This app aims to save lives and protect property by providing accurate and timely cloudburst predictions.

## Key Features

- **Real-Time Data Integration**: Integrates real-time weather data from the OpenMeteo API to provide users with up-to-the-minute information, critical for cloudburst prediction.
- **Machine Learning Models**: Utilizes advanced machine learning models trained on meteorological datasets to enhance the accuracy of cloudburst predictions.
- **User-Centric Design**: Features a user-friendly interface tailored for mobile devices, with functionalities such as push notifications and location-based alerts to enhance user engagement.
- **Ease of Accessibility**: Easily accessible with a single tap on a smartphone, making it convenient for users to check weather updates on the go.

## Model Selection

### 1. Random Forest Classifier
- **Accuracy**: 91.756%
- **Benefits**:
  - Strong at capturing non-linear patterns in meteorological data.
  - Robust performance even with noisy data.

### 2. Gradient Boosting Classifier
- **Accuracy**: 89.134%
- **Benefits**:
  - Effective in handling class imbalance, crucial for rare cloudburst events.
  - Provides valuable insights into the importance of meteorological parameters.

### 3. Convolutional Neural Network (CNN)
- **Accuracy**: 82.542%
- **Benefits**:
  - Specialized in handling spatial meteorological data, such as grid-based information.
  - Automatically learns hierarchical features, accommodating diverse scales.

### 4. Linear Regression
- **Benefits**:
  - Simple and interpretable model for understanding linear relationships.
  - Offers insights into the significance of individual meteorological parameters.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
