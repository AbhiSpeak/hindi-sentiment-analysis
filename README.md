## **HindiEmo**

### **Overview:**
This project is focused on predicting emotions (like 'angry', 'happy', 'neutral', and 'sad') from Hindi textual data. By processing and analyzing vast datasets containing text snippets in Hindi, a machine learning model was trained to understand and categorize the underlying emotion.

### **Features:**

1. **Data Collection and Preprocessing**:
   - Extracted textual data from multiple directories.
   - Organized data into distinct emotion categories for model training.

2. **Data Visualization**:
   - Word clouds for each emotion category.
   - Custom set of Hindi stopwords to enhance word cloud accuracy.

3. **Model Training and Evaluation**:
   - Utilized `CountVectorizer` and `TfidfVectorizer` for text vectorization.
   - Trained a Multinomial Naive Bayes classifier for emotion prediction.
   - Iteratively evaluated and optimized model accuracy.

4. **Web Application**:
   - Developed a user-friendly Streamlit web app.
   - Real-time emotion prediction from user-inputted Hindi text.

5. **Model Deployment**:
   - Models saved using the `pickle` library for efficient deployment and potential further refinements.

### **Technologies Used:**

- **Python Libraries**: pandas, numpy, matplotlib, sklearn, nltk, and pickle.
- **Visualization Tools**: WordCloud for generating word clouds.
- **Web Framework**: Streamlit for building the interactive web application.
- **Modeling**: Multinomial Naive Bayes for classification.

### **Usage of Technologies for Features**:

1. **pandas and numpy**: Extensively used for data manipulation and analysis.
   
2. **matplotlib and WordCloud**: Leveraged for data visualization, especially for generating emotion-specific word clouds.
   
3. **sklearn**: The backbone for machine learning tasks, from data splitting, vectorization, to model training and evaluation.
   
4. **nltk**: Provided additional tools for natural language processing tasks.
   
5. **pickle**: Allowed for efficient saving and loading of trained models, ensuring smooth deployment and transferability.
   
6. **Streamlit**: Facilitated the creation of a web interface, enabling users to predict emotions in real-time.

