# 🍅 Leaf Disease Detection AI

A professional deep-learning dashboard for detecting leaf diseases and providing agricultural remedies.
This project uses a **MobileNetV2** Convolutional Neural Network (CNN) to achieve **91%+ accuracy**.

## 🚀 Features
- **Leaf Specialist:** Trained specifically on 10 different tomato disease classes (Bacterial Spot, Early Blight, Mosaic Virus, etc.).
- **Smart Remedies:** Provides instant, professional agricultural cure suggestions.
- **Real-Time Analysis:** Processes images in seconds using a pre-trained AI model.
- **User-Friendly:** Built with Streamlit for a clean, responsive web interface.

---

## 💻 How to Run This Project (Step-by-Step)


### **Step 1: Prerequisites**
Before you start, make sure you have these installed:
1. **Python:** [Download Python 3.10+](https://www.python.org/downloads/) (⚠️ **IMPORTANT:** Check the box *"Add Python to PATH"* during installation).
2. **Git:** [Download Git](https://git-scm.com/downloads) (Just click Next > Next > Finish).

---

### **Step 2: Download the Project**
Open your Command Prompt (cmd) or Terminal and run:


# 1. Download the code
git clone [https://github.com/Ayuxh12/Tomato-Disease-Detection.git](https://github.com/Ayuxh12/Tomato-Disease-Detection.git)

# 2. Go into the project folder
cd Tomato-Disease-Detection

Step 3: Setup the Environment

For Windows:
Bash
# 1. Create the environment
python -m venv venv
# 2. Activate the environment
.\venv\Scripts\activate

<!-- For Mac/Linux:
python3 -m venv venv
source venv/bin/activate -->


Step 4: Install Dependencies
pip install -r requirements.txt

Step 5: Run the App!
streamlit run app.py



📂 Project Structure

    app.py: The main dashboard website code.

    utils.py: The brain containing the remedies and AI logic.

    models/: Contains the pre-trained plant_disease_model.h5 (No training required!).

    requirements.txt: List of all libraries needed to run the project.

