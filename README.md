# Vision Assist Final Project

AI-Powered Solution for Assisting Visually Impaired Individuals  

---

## Problem Statement  

Visually impaired individuals often face challenges in perceiving and interacting with their surroundings. They encounter difficulties in understanding their environment, reading visual content, and performing tasks that rely on sight. This project aims to develop an AI-powered solution that can assist visually impaired individuals by leveraging Generative AI to provide the following key functionalities:  

- **Real-time scene understanding**  
- **Text-to-speech conversion for reading visual content**  
- **Object and obstacle detection for safe navigation**  
- **Personalized assistance for daily tasks**  

The solution is designed to be intelligent, adaptable, and user-friendly, ensuring it enhances the independence and safety of visually impaired individuals.  

---

## Task  

The task is to develop an AI-powered application using Streamlit that provides assistive functionalities through image analysis. The application will allow users to upload an image, and the system will implement at least two of the following features:  

### Features  

1. **Real-Time Scene Understanding**  
   Generate descriptive textual output that interprets the content of the uploaded image, enabling users to understand the scene effectively.  

2. **Text-to-Speech Conversion for Visual Content**  
   Extract text from the uploaded image using Optical Character Recognition (OCR) techniques and convert it into audible speech for seamless content accessibility.  

3. **Object and Obstacle Detection for Safe Navigation**  
   Identify objects or obstacles within the image and highlight them, offering insights to enhance user safety and situational awareness.  

4. **Personalized Assistance for Daily Tasks**  
   Provide task-specific guidance based on the uploaded image, such as recognizing items, reading labels, or offering context-specific information to assist with daily activities.  

---

## Implementation Requirements  

- **Langchain**: For integrating AI capabilities.  
- **Streamlit**: For building the web application.  
- **Google Generative AI**: For generative tasks such as scene understanding and text-to-speech conversion.  
- **YOLO**: For object detection and obstacle identification.  

---

## Technologies Used  

- **Streamlit**: A framework for building interactive web applications quickly and easily.  
- **Langchain**: A framework for building AI applications that integrate language models and generative AI functionalities.  
- **Google Generative AI**: A set of AI models for generating text, speech, and other forms of data.  

---

## Installation  

### Prerequisites  

- Python 3.11 or compatible version  
- Virtual environment support (`venv` module)  
- Git installed (optional for cloning)  

### Steps  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/vision-assist-final-project.git
   cd vision-assist-final-project

2. Create and activate a virtual environment:
   ```bash
   python -m venv new_env
   new_env\Scripts\activate

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Install PyTorch and TorchVision:
   ```bash
   pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

5. Download the YOLO model for object detection.


### Usage
1. Activate the virtual environment:
   new_env\Scripts\activate
   
2. Run the application:
   streamlit run app.py

3. Open the provided URL in your browser to access the app.

### Conclusion
This project is aimed at making a meaningful impact by helping visually impaired individuals gain better control and understanding of their surroundings. By leveraging AI technologies such as generative models, image recognition, and OCR, we can create an intuitive, accessible application that empowers users to navigate their world more independently.

### License
This project is licensed under the MIT License. See the LICENSE file for details.
  Save this content in a file named `README.md` in the root directory of your project. Let me know if you need further assistance!

