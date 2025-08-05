# 💻 LaptopWorld – Laptop Price Prediction Web App

LaptopWorld is a Flask-based web application that predicts the price of a laptop based on user-selected hardware and brand specifications.<br> 
It's powered by a trained machine learning model and offers a smooth, interactive experience to estimate prices based on multiple parameters like RAM, weight, CPU, GPU, and more.

---

## 🧠 Features

• Predict laptop prices with high accuracy using a trained ML model (`joblib`)<br>
• User inputs include:<br>
  &emsp;- RAM<br>
  &emsp;- Weight<br>
  &emsp;- Screen type (Touchscreen/IPS)<br>
  &emsp;- Brand (Company)<br>
  &emsp;- Laptop Type (Gaming, Notebook, etc.)<br>
  &emsp;- Operating System<br>
  &emsp;- CPU & GPU brands<br>
• Clean and simple UI built using Flask and Jinja templates<br>

---

## 🛠 Tech Stack

- **Python**
- **Flask** – Web framework
- **HTML + CSS** – Frontend
- **SQLite** *(optional, if you later add user data storage)*
- **scikit-learn** – For training the model
- **Joblib** – For saving/loading the model
- **Pandas** – *(currently unused, can be removed unless needed later)*

---

## 📁 Project Structure
```bash
├── models/
│ └── laptop_model.lb     # Pre-trained ML model (joblib format)
├── templates/
│ ├── home.html           # Homepage with form
│ ├── project.html        # Project info/about page
│ └── output.html         # Result display page
├── app.py                # Main Flask app
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

```

---

## 📦 Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/your-username/laptopworld.git
cd laptopworld
```
2. **Create and activate a virtual environment**
```bash
 python -m venv venv
 source venv/bin/activate      # On Windows: venv\Scripts\activate
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
4. Run the Flask app
```bash
python app.py
```
5. Open your browser and navigate to:
```bash
http://127.0.0.1:5000/
```
