# TABLE & GRAPH EXPLANATION TOOL ✨

> **An AI-Powered Multimodal Data Interpretation Application**
> 
> **Institution:** Brainware University  
> **Department:** Cyber Science and Technology  
> **Project Supervisor:** Mr. Samudranil Maity  
> **Developer:** Samrat Sarkar  

---

## 📖 Project Overview

In an increasingly data-driven world, extracting meaningful insights from complex data visualizations and dense tabular formats remains a significant challenge for individuals without specialized analytical expertise. 

The **Table & Graph Explanation Tool** is a web-based, AI-powered application designed to democratize data comprehension. By leveraging Google's state-of-the-art **Gemini 2.5 Flash** multimodal Vision-Language Model, this tool allows users to upload images of charts, graphs, or structured tables and instantly receive clear, conversational, and context-aware natural language explanations of the underlying data.

## ✨ Key Features

* **Multimodal AI Analysis:** Processes spatial and visual data directly from images (PNG, JPEG, WEBP).
* **Zero-Shot Reasoning:** Automatically identifies axes, trends, anomalies, and highest/lowest data points without pre-configuration.
* **Secure API Handling:** API keys are entered directly by the user on the client side and are never stored on a backend server, ensuring maximum security.
* **Modern UI/UX:** Features a responsive, "glassmorphism" dark-mode interface with dynamic typing animations and clear Markdown rendering for analytical output.
* **Single-File Architecture:** The entire application is built into a single, lightweight `.html` file containing all structural HTML, CSS styling, and JavaScript logic.

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Artificial Intelligence:** Google Gemini API (Gemini 2.5 Flash Model)
* **Data Handling:** JavaScript `FileReader` API (Base64 encoding)

---

## 🚀 How to Run the Project

Since this project utilizes a single-file architecture without a dedicated backend database, running it is incredibly straightforward.

1.  **Download** the `index.html` file to your local machine.
2.  **Open** the file using any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
3.  **Enter your Gemini API Key** in the designated secure input field.
4.  **Upload** an image of a chart or table using the drag-and-drop zone.
5.  Click **"Analyze Data ✨"** and wait a few seconds for the AI to generate your plain-text explanation.

---

## 🔑 How to Generate a Gemini API Key

To use this tool, you must supply your own Google Gemini API key. Follow these steps to generate one for free:

1.  **Navigate to Google AI Studio:** Go to [https://aistudio.google.com/](https://aistudio.google.com/) in your web browser.
2.  **Sign In:** Log in using your standard Google/Gmail account.
3.  **Access the API Section:** Once logged in, look for the **"Get API key"** option on the left-hand navigation menu and click it.
4.  **Create the Key:** Click the **"Create API key"** button. You will be prompted to create the key in a new project or an existing Google Cloud project. Selecting "Create API key in a new project" is the easiest method.
5.  **Copy the Key:** A pop-up window will display a long string of characters. This is your API key. Copy this string.
6.  **Paste & Use:** Return to the Table & Graph Explanation Tool and paste this key into the API Key input field.

⚠️ **Security Note:** Treat your API key like a password. Never hard-code it into public GitHub repositories or share it openly on the internet. 

---

## 📜 License & Acknowledgements

This project was developed as an academic endeavor under the guidance of Mr. Samudranil Maity at Brainware University. The core AI functionality is powered by Google's generative AI models.