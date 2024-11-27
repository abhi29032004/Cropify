<img src="templates/Screenshot 2024-04-07 151553.png">



# Cropify

Cropify is a web application designed to empower farmers with intelligent decision-making tools to enhance their farming practices and promote sustainability in the agricultural sector. Leveraging machine learning models, Cropify offers farmers insights and recommendations tailored to their specific needs and conditions.

## Features

- **Machine Learning Models:**
  - Naive Bayes: Utilized for predictive analytics and classification tasks, such as crop disease detection and risk assessment.
  - Random Forest: Employed for predictive modeling and decision-making processes, aiding in crop yield forecasting and optimal resource allocation.
  - LightGBM: Utilized for efficient gradient boosting, enabling accurate predictions and insights into soil health and nutrient management.
  - CNN (Convolutional Neural Network): Applied for image recognition and analysis, assisting in crop pest identification and monitoring.

- **Crop Recommendation:** Utilizing machine learning algorithms, Cropify recommends suitable crops based on factors such as soil type, climate conditions, and historical data.

- **Yield Prediction:** Predicts crop yields based on various parameters such as weather patterns, soil quality, and agricultural practices, helping farmers plan their harvest and optimize resources.

- **Fertilizer Recommendation:** Provides personalized recommendations for fertilizer usage based on soil nutrient analysis, crop type, and growth stage, promoting efficient nutrient management and reducing waste.

- **Leaf Disease Prediction:** Detects and predicts crop diseases by analyzing images of leaves, enabling early detection and intervention to prevent widespread crop damage.

## Technologies Used

- **Frontend:** Built with React.js, providing a responsive and interactive user interface for seamless navigation and engagement.

- **Backend:** Backend functionalities are supported by Python-based frameworks for machine learning model development, API integrations, and data processing.

- **Machine Learning Libraries:** Utilized popular libraries such as Scikit-learn, TensorFlow, and Keras for developing and deploying machine learning models.

## Installation

To run Cropify locally, follow these steps:

1. Clone the repository:

```
    git clone https://github.com/BRArjun/Cropify_ML_WebDev.git
```

2. Navigate to the project directory:

```
    cd Cropify_ML_WebDev
```

3. Install dependencies:

```
    npm install
```

4. Start the developmental server:

```
    npm start
```

5. Access Cropify in your web browser at `http://localhost:3000`.

## Contributing

We welcome contributions from the community to enhance Cropify's features, improve its performance, and expand its capabilities. To contribute, please fork the repository, make your changes, and submit a pull request with a detailed description of your modifications.

## License

Cropify is licensed under the MIT License.


# Project Organization
------------

    ├── README.md        
    |          
    ├── data
    │   ├── processed      
    │   └── raw            
    │
    ├── models   
    │   ├── crop_yield_model      
    │   ├── crop_est_model
    |   ├── fertilizer_rec_model
    |   └── leaf_disease_detect_model
    │
    ├── research          
    │
    ├── ML           
    │   ├── crop_yield        
    │   ├── crop_est
    |   ├── fertilizer_rec
    |   └── leaf_disease_detect
    |
    ├── requirements.txt   
    │
    ├── src                
    │   ├── Components                
    │   │
    │   ├── App.js           
    │   │    
    │   ├── Index.js       
    │
    ├── server.py
    |
    ├── json_files
    |
    └── data2.csv
