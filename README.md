# 📧 Cold Mail Generator

A tool designed to streamline outreach for service companies by generating personalized cold emails for potential clients. Built with **Groq**, **LangChain**, and **Streamlit**, this app simplifies the process of crafting tailored emails by automatically extracting job listings from a company’s careers page and suggesting relevant portfolio links based on the job description. 

---

## ✨ Project Overview

This project addresses the challenge of creating effective cold emails by personalizing outreach to potential clients, like large companies in need of software development expertise. It leverages **Groq** for job listing extraction, **LangChain** for language processing, and **Streamlit** for a user-friendly interface. Additionally, the app connects to a **vector database** to recommend portfolio links relevant to the job listings, ensuring each email is customized to the recipient's needs.

### 🚀 Scenario

Consider the following example:  
Nike is searching for a **Principal Software Engineer** and is investing significant time and resources into recruitment, onboarding, and training. **Atliq**, a software development firm, could provide dedicated engineering support to fill this gap. Using the Cold Mail Generator, **Mohan**, a business development executive at Atliq, can quickly generate a personalized cold email to Nike, showcasing Atliq's relevant experience and expertise.

![Example Scenario](imgs/img.png)

---

## 🛠️ Key Components

### 1. **Groq API**  
   - Extracts job listings from a target company's careers page, providing structured data on available positions.

### 2. **LangChain**  
   - Processes and generates natural language responses, turning data into compelling cold email content tailored to each job description.

### 3. **Vector Database**  
   - Maintains and retrieves relevant portfolio links based on job descriptions, adding personalized examples to each email.

### 4. **Streamlit Interface**  
   - Provides an intuitive, user-friendly app interface where users can input URLs, configure settings, and view generated emails.

---

## 📐 Architecture Diagram

![Architecture Diagram](imgs/architecture.png)

---

## 🧩 Set-Up Guide

To get started with the Cold Mail Generator:

1. **Obtain an API Key**  
   - Register for an API key on [Groq’s website](https://console.groq.com/keys).
   - Update the `.env` file located in the `app` directory with your new API key:
     ```plaintext
     GROQ_API_KEY=your_api_key_here
     ```

2. **Install Dependencies**  
   Run the following command to install necessary libraries:
   ```bash
   pip install -r requirements.txt
3. **Launch the app**
    Start the app using Streamlit:
    ```bash
    streamlit run app/main.py
# 🔒 License & Terms
This software is licensed under the MIT License. Commercial use of this software is prohibited without prior written permission from the author. Attribution must be given in all copies or substantial portions of the software.

Note: For further usage or commercial inquiries, please contact the author.
# 📞 Contact & Support
For more details or support, please reach out to aayonsworld@gmail.com.

---

