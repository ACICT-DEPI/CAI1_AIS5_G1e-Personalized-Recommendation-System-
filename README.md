# Films Recommender System 

 This is a simple content-based recommender system for films created for the DEPI project. The application is built using Streamlit and deployed on Azure App Service.

# Features
* Content-Based Filtering: Recommends movies and shows based on user preferences and past interactions.
* Natural Language Interaction: Uses GPT-3 to allow users to interact naturally with the system, asking for recommendations in conversational form.
* Movie Information and Trailers: Provides detailed information on recommended content, including descriptions, ratings, and trailers.
* Streamlit Interface: A simple, easy-to-use interface built with Streamlit for seamless interaction.
# Dataset
The recommendation system is based on datasets from various movie and TV show platforms such as:

* Netflix
* Disney+
Data is cleaned, preprocessed, and concatenated into a unified format for more efficient recommendation processing.

# Installation
To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Amirtarek1/Films_RecommenderSystem_GPT3-main.git
   cd Films_RecommenderSystem_GPT3-main
   
2. **Install dependencies**: Ensure you have Python 3.7+ installed, then install the required packages by running:
   ```bash
   pip install -r requirements.txt

3. **Run the application**: Start the Streamlit app by running:
   ```bash
   streamlit run app.py


> **Important hint**:  
> When downloading the folder, ensure the `.pkl` file is fully downloaded (391 MB). If the file size is incorrect, please download it again.


# Usage
* After launching the app, users can input their preferences or simply ask for recommendations in natural language.
* The system will return a list of movies or shows tailored to the user, along with trailers and other relevant information.
  
# Project Structure
* app.py: Main file to run the Streamlit application.
* data/: Folder containing the preprocessed dataset.
* models/: Contains machine learning models and GPT-3 integration for enhanced recommendations.
* requirements.txt: A list of Python libraries required to run the project.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
