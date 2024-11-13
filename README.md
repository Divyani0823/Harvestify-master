
---

# **GreenTech Hub 🌱**  
### A cutting-edge ML & DL powered platform for precision farming: Crop recommendations, Fertilizer suggestions, and Disease identification.
---

## **💡 MOTIVATION**  
Agriculture is a critical pillar of economic growth, especially in countries like India, where a significant portion of the population relies on farming for their livelihood. With the rise of technology, AI, and ML are becoming indispensable tools for enhancing farming practices. Through **AgriTech Insights**, we aim to:

- Simplify farming processes for farmers by providing actionable insights through technology.
- Integrate Machine Learning and Deep Learning into agriculture to help farmers make informed decisions and optimize their resources.
- Offer a comprehensive platform with three key applications:
  1. **Crop Recommendation**: Helping farmers choose the right crop based on soil data.
  2. **Fertilizer Recommendation**: Guiding farmers on which fertilizers to use based on soil and crop needs.
  3. **Plant Disease Detection**: Identifying plant diseases and suggesting remedies via image analysis.

---

## **📊 DATA SOURCES**  
The data used in this project comes from reliable, open-source platforms:
- **[Crop Recommendation Dataset](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset)** - A custom-built dataset that helps predict the best crops for different soil types.
- **[Fertilizer Suggestion Dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv)** - A handpicked dataset for recommending fertilizers based on soil composition.
- **[Disease Detection Dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)** - A comprehensive dataset to train models for plant disease classification.

---

## **🔨 TECHNOLOGIES USED**  
This project is powered by the following technologies:

- **Programming Languages**: Python, HTML, CSS, JavaScript
- **Frameworks & Libraries**: Flask, Bootstrap, NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow, PyTorch
- **Deployment**: Heroku for live hosting, Git for version control

---

## **🚀 DEPLOYMENT**  
The platform is live and deployed on [Heroku](https://www.heroku.com/), where users can access the website and experience the functionalities in real-time.  

**Live Website**: [AgriTech Insights](https://harvestify.herokuapp.com/)  
Note: The website may load slowly if the server is inactive. Please be patient.

---

## **🖥️ HOW IT WORKS**

### **Crop Recommendation System**  
- **Inputs**: Soil nutrient values (N, P, K), city, and state.
- **Functionality**: Based on the given data, this model predicts the most suitable crops to grow in the user's area.
  
### **Fertilizer Suggestion System**  
- **Inputs**: Soil composition and crop type.
- **Functionality**: Based on the input data, this tool identifies which nutrients are deficient or in excess, recommending specific fertilizers to balance soil quality.

### **Disease Detection System**  
- **Inputs**: A clear image of the plant's diseased leaf.
- **Functionality**: This system identifies the plant type, diagnoses the disease, and offers suggestions for curing it.
- **Supported Crops**:
  - Apple
  - Blueberry
  - Cherry
  - Corn
  - Grape
  - Pepper
  - Orange
  - Peach
  - Potato
  - Soybean
  - Strawberry
  - Tomato
  - Squash
  - Raspberry

---

## **🔧 HOW TO RUN LOCALLY**  

### **Prerequisites**:
- **Git**: [Download Git](https://git-scm.com/download)
- **Python**: Install Anaconda/Miniconda from [here](https://www.anaconda.com/).
  
### **Steps**:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AgriTech-Insights.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AgriTech-Insights
   ```
3. Set up your environment:
   ```bash
   conda create -n agriTech python=3.8
   conda activate agriTech
   pip install -r requirements.txt
   ```
4. Run the project:
   ```bash
   python app.py
   ```
5. Open your browser and visit [localhost:5000](http://localhost:5000) to use the platform locally.

---

## **📽️ DEMO**  
- **Crop Recommendation System**  
  ![Crop Recommendation Demo](https://media.giphy.com/media/90JbjdAa5nDq3TJh5u/giphy.gif)

- **Fertilizer Suggestion System**  
  ![Fertilizer Suggestion Demo](https://media.giphy.com/media/FLftUXMFo8N2bBjAXq/giphy.gif)

- **Disease Detection System**  
  ![Disease Detection Demo](https://media.giphy.com/media/NnMwEp2tGZdfnJbyjr/giphy.gif)

---

## **📈 FUTURE IMPROVEMENTS**  
While this project has shown great promise, there are areas for further enhancement:
- **Improve UI/UX**: A more polished front-end interface for a seamless user experience.
- **Enhance Dataset**: Incorporating more comprehensive datasets to improve prediction accuracy.
- **Expand Crop & Disease Database**: Including more crops and diseases for wider use cases.
- **Make Code Modular**: Refactor the code for better scalability and reusability.

---

## **👨‍💻 CONTRIBUTING**  
We welcome contributions to improve and expand the platform. Please follow the guidelines in the [CONTRIBUTING.md](https://github.com/yourusername/AgriTech-Insights/blob/main/CONTRIBUTING.md) file to submit pull requests and suggestions.

---

## **🔑 CREDITS**  
This project draws inspiration from the [Recommendation System for Farming](https://github.com/7NNS7/Recommendation-System-for-Farming) repository. It serves as an extended version with added functionalities for fertilizer suggestions and disease detection.

---

## **📞 CONTACT**  
For questions, contributions, or collaboration inquiries, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/yourname) or email at yourname@example.com.

---

## **📝 LICENSE**  
This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](https://github.com/yourusername/AgriTech-Insights/blob/main/LICENSE) file for more information.

---

### **Let's make farming smarter with AI! 🌾**  

---

In this updated README, I’ve changed the project name, restructured the content for clarity, and added extra details and explanations to enhance the user experience. Feel free to replace the placeholders (e.g., links, your name) with your actual information.
