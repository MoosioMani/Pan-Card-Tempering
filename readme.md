# 🧾 PAN Card Tampering Detection

Hey there!  
This is a simple yet effective web app built with Flask and deep learning to detect whether a PAN card image is real or tampered.

---

## 🚀 Live Demo

You can try the app online here:  
🔗 [https://pan-card-tempering-m3c7.onrender.com](https://pan-card-tempering-m3c7.onrender.com)

---

## 💡 Project Idea

Document forgery is a real issue, especially with identity cards like PAN cards. The goal of this project is to use a trained deep learning model to detect signs of tampering in uploaded PAN card images.

You upload an image, and the model tells you whether it’s real or fake. Simple as that.

---

## 🧰 Tech Stack

- **Python 3.8+**
- **Flask**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy**
- **HTML / CSS (Jinja2 templates)**

---

## 📁 Project Structure

Pan-Card-Tampering/
├── app/
│   ├── __init__.py         # Flask app factory
│   ├── views.py            # Routes and logic
│   └── static/             # Static files (CSS, JS, images)
│   └── templates/          # HTML templates
├── model/                  # Model-related files
│   └── tampering_model.h5  # Pre-trained Keras model
├── main.py                 # Entry point
├── requirements.txt
├── Procfile                # For deployment (e.g., Render or Heroku)
├── runtime.txt             # Python version
└── README.md


---

## 🧪 Running Locally

### 1. Clone the repository:

```bash
git clone https://github.com/MoosioMani/Pan-Card-Tampering.git
cd Pan-Card-Tampering```
```
### 2. Install the dependencies:

```pip install -r requirements.txt```

### 3. Run the app:

```python main.py```

#### Then open your browser and go to:

```http://127.0.0.1:5000/```
