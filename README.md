# 🤖 Personal ChatBot

Welcome to the **Personal ChatBot** – a simple AI-powered assistant built to answer personal and customized questions about **Sanka Naga Sai Harshini**! 🎓💬

This project uses **Logistic Regression** and **TF-IDF** for intent classification and is deployed with **Streamlit** for a modern interactive chat experience.

🌐 **Live Demo**: [Click here to try it out!](https://personal-chatbot-sjbdrbq6vmgxaqsphtwaha.streamlit.app/)

---

## 🔍 Features

* ✅ Intent Detection with **TF-IDF + Logistic Regression**
* 💬 Interactive Chat UI using **Streamlit**
* 🧠 Trained on personalized intents
* ♻️ Easy to extend with new questions and responses
* 🌍 Fully deployed and publicly accessible

---

## 📁 Project Structure

`personal-chatbot/` folder:

* `app.py`
* `intents.json`
* `requirements.txt`
* `.gitignore`
* `README.md`

---

## ⚙️ Installation Guide

### Requirements

* Python 3.8 or above
* Streamlit
* scikit-learn
* numpy
* pandas

### Run Locally

1. Clone the repository:

```
git clone https://github.com/Perumalla05/personal-chatbot.git
cd personal-chatbot
```

2. (Optional) Create and activate a virtual environment:

```
python -m venv venv
venv\Scripts\activate
```

3. Install required packages:

```
pip install -r requirements.txt
```

4. Run the chatbot:

```
streamlit run app.py
```

---

## 💡 How It Works

1. Loads intent data from `intents.json`
2. Converts user input into vector format using **TfidfVectorizer**
3. Predicts the intent tag using **Logistic Regression**
4. Chooses a random response from the predefined responses

---

## 🗣️ Example Questions

Some questions the chatbot can answer:

* What is your name?
* Where are you from?
* What are your hobbies?
* What is your favorite food?
* What languages do you speak?

You can modify or add your own questions and responses in the `intents.json` file.

---

## 🚀 Future Enhancements

* Add text preprocessing (lemmatization, stemming, stopword removal)
* Add speech-to-text and text-to-speech
* Store conversation history
* Integrate advanced NLP models like spaCy or Transformers

---

## 🙋‍♀️ About the Developer

👩‍💻 Developed by **Sanka Naga Sai Harshini**
🎓 BSc (Computers), 3rd Year Student
🏫 BV Raju College
📍 Bhimavaram, West Godavari, Andhra Pradesh, India

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

## 📌 Quick Git Commands (after editing README)

```
git add README.md
git commit -m "Updated README with my personal chatbot details"
git push
```
