# 🤖 Streamlit GPT-2 Chatbot

A simple **AI chatbot built with Streamlit**, powered by **Hugging Face Transformers** and **GPT-2**.  
It provides concise answers for software engineering questions and demonstrates how to integrate language models into interactive web apps.

---

## 🚀 Features

- 🧠 **GPT-2 text generation** using Hugging Face pipeline  
- ⚙️ Adjustable model settings (temperature, top-p, repetition penalty)  
- 💬 **Persistent chat history** in Streamlit session state  
- ⚡ **Cached model loading** for faster performance  
- 🎨 Clean Streamlit chat UI with sidebar controls  

---

## 🧩 Requirements

Install the dependencies listed below:

```bash
pip install streamlit transformers torch accelerate
```

---

## 🧱 Project Structure

```
📦 streamlit-gpt2-chatbot
 ┣ 📜 app.py              # Main Streamlit app file
 ┣ 📜 requirements.txt    # Dependencies
 ┗ 📜 README.md           # Project documentation
```

---

## 🖥️ Usage

Run the chatbot locally:

```bash
streamlit run app.py
```

Then open your browser at **http://localhost:8501**

---

## ⚙️ Configuration

Adjust model generation parameters in the sidebar:

- **Max new tokens:** control response length  
- **Temperature:** adjust creativity (0.1–1.0)  
- **Top-p:** nucleus sampling for diversity  
- **Repetition penalty:** reduce repeated phrases  

---

## 📘 Example Question

> 🧑‍💻 *"Explain the difference between synchronous and asynchronous programming in Python."*

**🤖 GPT-2:**  
> Synchronous code runs line by line, blocking other operations until each step completes. Asynchronous code uses `async` and `await` to run multiple tasks concurrently, improving performance in I/O-heavy programs.

---

## 🧠 Notes

- GPT-2 is not instruction-tuned, so answers may vary in relevance.  
- For improved quality, try models like **microsoft/DialoGPT-medium** or **tiiuae/falcon-7b-instruct**.  
- The chatbot runs **fully locally** — no OpenAI API needed.

---

## 🏷️ Keywords

`streamlit`, `chatbot`, `gpt2`, `huggingface`, `transformers`, `ai`, `python`, `machine-learning`, `nlp`, `text-generation`

---

## 📄 License

This project is released under the **MIT License**.  
You are free to use, modify, and distribute it for educational or commercial purposes.

---

## 👨‍💻 Author

**Ojobor Jude Ikechukwu**  
AI & Software Developer | Virtual Assistant | Tech Innovator  
📍 Nigeria | 🌐 [GitHub Profile](https://github.com/judeik)  
✉️ **Email:** [judeojobor@gmail.com](mailto:judeojobor@gmail.com)  
💼 **LinkedIn:** [linkedin.com/in/ojoborjude](https://www.linkedin.com/in/ojobor-jude-ik-292b9612b/)

---

Made with ❤️ using Streamlit and Hugging Face Transformers.
