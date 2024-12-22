# Fetal Health Prediction Project

The **Fetal Health Prediction Project** is an innovative machine learning application designed to predict fetal health outcomes based on key medical parameters. This project addresses the pressing need for accurate, automated health monitoring tools during pregnancy, aiming to assist healthcare professionals in making timely and informed decisions.

## Key Features
1. **Advanced Machine Learning Models**: Utilized supervised learning techniques to categorize fetal health into three categories—Normal, Suspect, and Pathological.
2. **Data Preprocessing**: Employed robust preprocessing techniques to handle missing values, standardize features, and ensure data quality.
3. **Interactive Frontend**: Built a user-friendly interface using **Streamlit** to provide seamless interaction for healthcare professionals and end-users.
4. **Scalable Containerization**: Dockerized the entire application, ensuring it runs consistently across various environments without dependency issues.
5. **Cloud Deployment**: Deployed the Dockerized application on **DigitalOcean**, offering high availability, scalability, and robust performance.


## Project URL


- **Streamlit Framework**: [Streamlit App](https://fetalhealthpredictions-qdbtjznyny7yiihajb7hzo.streamlit.app/)
- **Project Video**: [Project Demo](https://drive.google.com/file/d/1h-g_TDYRGYXTqCnfyU7ui0VPGSgDMcyq/view?usp=sharing)
- **API Framework**: [FastAPI Service](http://134.122.119.149:8002/)
- **DAGSHUB**: [MLflow](https://dagshub.com/HariniMurugan-2003/Fetal_health_Fall24.mlflow/#/experiments/0)


## Project Workflow
1. **Data Input**: Users upload clinical datasets containing features like heart rate, uterine contractions, and fetal movement.
2. **Feature Engineering**: The application preprocesses the data and extracts meaningful features.
3. **Prediction**: Trained machine learning models predict fetal health categories with high accuracy.
4. **Results Visualization**: Displays predictions and insights in an interactive, easy-to-interpret dashboard.

## Challenges and Solutions
- **Challenge**: Ensuring the model's interpretability for healthcare professionals.  
  **Solution**: Integrated feature importance plots and confidence scores in the Streamlit dashboard.
- **Challenge**: Maintaining application portability and scalability.  
  **Solution**: Containerized the app using Docker and deployed it on a scalable cloud platform.

## Outcomes
- **Improved Accuracy**: Achieved a high predictive accuracy through optimized models.
- **Accessible Platform**: Streamlit’s intuitive UI made it accessible to non-technical users, particularly healthcare professionals.
- **Reliability**: Docker and DigitalOcean ensured consistent performance and deployment across various environments.

This project demonstrates the potential of integrating machine learning, containerization, and cloud hosting to develop reliable, accessible tools for critical healthcare needs.

