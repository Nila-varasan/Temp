![image](https://github.com/user-attachments/assets/eccb0be8-ccb6-4042-8f20-5eba54639d03)![image](https://github.com/user-attachments/assets/2d4669eb-8c02-4a93-bd7d-4fda5b6d7430)
![final_image](https://github.com/user-attachments/assets/3fc6ddf1-bb99-4351-a363-88d967bd2e03)

<p align="center">
  👉 <a href="https://yourwebsiteurl.com" target="_blank">Click here to view the website</a>
</p>

--- 
# AI Integration
- As part of our project, AI plays a huge role. It is resposible for many tasks, automation few things. AI has helped our website to standout compared to all other websites
<p align="center">
  <img src="https://img.shields.io/badge/gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="gemini"/>
  <img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white" alt="openai"/>
  <img src="https://img.shields.io/badge/anthropic-000000?style=for-the-badge&logo=anthropic&logoColor=white" alt="anthropic"/>
  <img src="https://img.shields.io/badge/browser--use-5A5A5A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="browser-use"/>
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="python"/>
</p>

### 🚀 AI-Powered Website Navigation ChatBot
This chatbot helps users navigate the website more efficiently. You no longer need to waste time searching for a specific part of the application — just tell the bot what you want to do, and it will handle the task for you. Tasks can range from general to highly specific.
- Logging in or signing up
- Asking which companies have visited the campus
- Checking how many problems you've solved — even more specifically, how many medium-level problems
All these or done by the bot, which navigates and fullfill the Query.
> 🛠 Built using the open-source project: **web-ui**

> Web-Ui **REPO:** `https://github.com/browser-use/web-ui`, have used the API from the open-source project for the web-based-bot part of our project

<details> <summary><strong>Click to Expand Full Description Of BOT</strong></summary> <br>
  
This bot leverages a browser UI-based method to automate and perform these tasks.
  
1. **Information Seeking:**
- Ask the bot to summarize statistics or graphs from the placement or any other page.
- Request a summary of any specific page on the site.
- Search for a specific problem (e.g., Two Sum), and the bot will:
  - Check if it has been solved
  - If not, extract and provide relevant resources
2. **Site Navigation:**
- Direct the bot to move across different pages.
- Ask it to go to a specific page or section.
- Be context-specific: request the bot to jump to a relevant section within an application page.
3. **Configuration & Operations** Command the bot to perform operations like:
- Signing in
- Signing up (you can provide your email and password)
- Applying to a recently posted company

</details>

#### Demo Of Web-Based Bot:

1. **PROMPT-1:** (_Simple_)
```
1.) open a tab, and in that open these URL: http://localhost:5174
2.) Click sign-up button
3.) Then click sign-up using google, and know when a new window pop-up. 
4.) In the text field type "01nilavarasan@gmail.com" and click the submit button
```
- **Execution Of Above PROMPT:**

https://github.com/user-attachments/assets/bb21e530-232d-423e-9f1a-1667dee727fa

2. **PROMPT-2** (_Complex_)
```
1.) open a tab, and in that open these URL: http://localhost:5174
2.) Know click the sign-in button, and in that page click the sign-method where we use camera sign-in.
3.) Know in that portal , wait till a human face appear in the screen. If appeared then wait 5 seconds. And then click capture button.
4.) Know a new page will be loaded, then click companies button present in the sidebar.
```
- **Execution Of Above PROMPT:**

![f705c3a0-d7b1-4bc7-adf2-cd721b7a50af](https://github.com/user-attachments/assets/47b3c22f-be35-4bf6-9e38-a5590067dea6)

- In the similar way we can ask the Bot some query, and the bot executes the query by travelling/traversing/using , by interacting with the browser elements(scrool, click, read, write etc).
> As of know these bot is not integrated with the Main Website, but the bot works completely fine. Asking any query the bot fullfills it, just the integration of this browser-ui-model-API, need to be configured with the Bot in our application. And also the below pipe-line flow also need to be finished using langchain, the flow of prompt from the BOT. 
**_BOT IN PROGRESS_**

### 🤖 AI-Powered General ChatBot

<p align="center">
<img src="https://img.shields.io/badge/pinecone-0EAD69?style=for-the-badge&logo=pinecone&logoColor=white" />
<img src="https://img.shields.io/badge/huggingface-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/langchain-000000?style=for-the-badge&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/langsmith-000000?style=for-the-badge&logo=langchain&logoColor=white" />
</p>

1. This chatbot functions like any general-purpose assistant, capable of handling a wide range of user queries. It supports both general knowledge questions and personalized queries based on user-specific data.
- Users can ask questions on a variety of topics, including:
  - **Learning topics:** “What is Big Data?”, “Explain the Two-Sum problem”, “What is the time complexity of this approach?”
  - **Problem-solving guidance:** Debugging, Concept explanations, Strategy recommendations

![Screenshot 2025-05-18 213617](https://github.com/user-attachments/assets/7c5069bf-40e8-4212-b345-558c0f7d9cb1)
![image](https://github.com/user-attachments/assets/9faa607b-9f27-4972-9eb1-74776c8b55bb)

https://github.com/user-attachments/assets/daa612dc-ffdd-430f-b5c5-8f68fec2f720



> This Part works completely fine, integrated with Gemini-API.
2. Also since the bot is powered by RAG, where to the RAG some of the data are also feed like. Like stats/data of the placement/company of all the years, also it has aceess to some of the data of the user. Not all data are shared to the RAG, since some data are sensitive. So only some of the neccesary features of the company/stats/current-uer are stored in the vector-DB, using this data the specific-user can ask questions like
- "How many company have came this year with more then 12-lLPA", "How many jobs is posted by Google this year".
- "How much problems i have solved in medium level", "How much companies i have applied", "How many companys i am elgibile , but have not applied".

A spereate vector-DB is present for each user, so the bot can answer based on that Specific-User. -----> All this are done using RAG, and the pipeline is log/streamlined through langsmith. The data are automatailally updated in the RAG, when ever there is update in data of the user/company/placement. <--- ALl this pipiline are monitored using langsmith. 
> This part is **IN-PROGRESS NOT FINISHED**, have finished the pipeline. Just need to intergrate the pipeline with the backend, then with frontend.

### 🧑‍💻AI-BOT specifically For DSA-PROBLEMS:
![image](https://github.com/user-attachments/assets/62c154b1-5d9b-41ee-8b31-08c07395d3b4)
> **IN PROGRESS NOT COMPLETED**
---
# The Making Of 🛠️


<h3 align="center">
   ⚡⚡⚡ The Technology's Used ⚡⚡⚡
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" />
  <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/langchain-000000?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/huggingface-FFD21F?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/pinecone-0EAD69?style=for-the-badge&logo=pinecone&logoColor=white" />
  <img src="https://img.shields.io/badge/vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/apache%20mllib-F87000?style=for-the-badge&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/opencv-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/lucide--react-000000?style=for-the-badge&logo=lucide&logoColor=white" />
  <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/langsmith-000000?style=for-the-badge&logo=langchain&logoColor=white" />
</p>

---

### 🖥️ Frontend
<p align="center">
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/lucide--react-000000?style=for-the-badge&logo=lucide&logoColor=white" alt="lucide-react" />
</p>

- Built using **React**, with most components styled using **Tailwind CSS** and **Lucide React** And some components are also styled with **Bootstrap**.
- Developed in **TypeScript** for type safety.
- **State Management** is handled using **Redux** and **Context Provider Hook** – ensuring reloads occur only when necessary.
- **Routing** across pages is implemented using **react-router-dom**.

---

### 🗄️ Databases

<p align="center">
  <img src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
</p>

We have chosen to use **NoSQL databases** due to their scalability, speed, and ease of structuring data. This approach aligns well with the dynamic and rapidly growing nature of our application.
- **MongoDB:**  Stores all core data related to users, problems, companies, and other essential components of the website. NoSQL structure makes the data more scalable and easier to manage as the application grows.
- **Firebase:** Used for **user authentication**. Supports secure and seamless sign-in methods, including: Google, Microsoft, Phone Number. Enhances both **security** and **user experience** during the authentication process.

#### Overall MongoDb databases && Collections Present
![image](https://github.com/user-attachments/assets/c0e48a8b-5a5d-41ff-859d-82ad2037b680)
#### Database Used In Each Page
![image](https://github.com/user-attachments/assets/83fa53f3-3621-4fe3-87cc-5d1af1e49947)

#### MongoDB Structure: Company
![image](https://github.com/user-attachments/assets/243a2cb1-246d-42ea-8ca6-2744e1248d5b)
#### MongoDB Structure: Blogs
![image](https://github.com/user-attachments/assets/50957a8f-45f7-4d35-878e-7cecdd502e40)
#### Planned MongoDB Structure: User
![image](https://github.com/user-attachments/assets/74e4e5ca-7604-4782-8f08-c7f51fc97b78)
#### Firebase Structure: Authentication
![image](https://github.com/user-attachments/assets/fceaa4e5-3504-454f-9097-64135b6bd35c)

---

### 🛠️ Backend
<p align="center">
  <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
  <img src="https://img.shields.io/badge/apache%20mllib-F87000?style=for-the-badge&logo=apachespark&logoColor=white" alt="MLlib" />
  <img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
</p>


- **Node.js Server**  
  Used **Node.js** to fetch and serve data related to users, companies, blogs, placements, and more from **MongoDB**. All frontend components retrieve their data via this server.  
  ➤ Server runs on: `http://localhost:5000`

We have also used Express.js to handle routing and middleware for the Node.js server, ensuring efficient communication between the frontend and backend services.

- **Python Flask for Chatbots**  
  Integrated all chatbots on the website using **Python Flask**. These bots are powered by **Gemini** and **OpenAI APIs**, and are seamlessly connected to the front end via Flask routes.  
  ➤ Chatbot server runs on: `http://localhost:5002`

- **Python Flask for Face Recognition**  
  Implemented a face recognition module using **OpenCV**, **MLlib**, and **PCA**, with a dedicated Flask server. Images are sent to this server, processed, and authenticated based on facial recognition results.  
  ➤ Face recognition server runs on: `http://localhost:5001`

---

### Camera Authentication Mechanism
![image](https://github.com/user-attachments/assets/fc8491f5-5198-44a4-8af5-f5c388118d0c)
### Mathematical Working Of Camera Authentication

<p align="center">
<img src="https://img.shields.io/badge/apache%20mllib-F87000?style=for-the-badge&logo=apachespark&logoColor=white" />
<img src="https://img.shields.io/badge/opencv-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
</p>

![image](https://github.com/user-attachments/assets/963c40f6-e74d-4aa5-b85a-27823f41b107)

# 🚀 Setup Instructions

### 📦 Prerequisites
- Make sure you have the following installed: `vite`, `python >= 3.10`, `pip`
- Clone the repository: `git clone https://github.com/maciekt07/TodoApp.git`
- Navigate to the project directory: `cd TodoApp`
* Install the dependencies:
  ```bash
  npm install
  pip install -r requirements.txt
  ```
- Configure your **Gemini**, **OpenAI**, and **HuggingFace** API keys in the `.env` file located at: `\Code_Bot\Code_Bot\.env`
---
### 🖥️ Start the Frontend
- Start the development server: `npm run dev`
---
### ⚙️ Start the Servers
#### 1. Node.js Server (Runs on `http://localhost:5000`)
```bash
cd src
node server.js
```
#### 2. Face Recognition Server (Runs on `http://localhost:5001`)
```bash
cd frontend
cd backend
python app.py
```
#### 3. Bots Integration Server (Runs on `http://localhost:5002`)
```bash
cd Code_Bot
cd Code_Bot
python app.py
```
---

# 🧩 Problem vs Solution

## ❗ The Problem
During the intense placement phase, we realized the need for a **personal assistant/guide** to navigate us through the journey. Self-study and self-improvement are powerful—but **staying organized and motivated** on our own path proved challenging. We needed a platform that could help us:

- Structure our preparation
- Track our progress
- Push us in the right direction
- Offer guidance without switching across multiple platforms

---



## 🚀 The Solution

We present **PlacementPrep** – your **intelligent placement companion**.

✨ **What it offers:**
- A centralized platform designed to act as your **personal assistant**
- AI-powered guidance to **keep you on track**
- Tools to **monitor your growth** and stay motivated
   
### 🔐 Secured Login Features:
- **Multiple Authentication Methods**: Google, Microsoft, Phone Number.
- **Domain-Based Email Restriction**: Helps segregate users based on institution or department. Ensures only authorized domains can register or log in.
- **Novel Face-Based Sign-In**: Powered by **Principal Component Analysis (PCA)**, **OpenCV** for facial recognition, Integrated with **Big Data tools**: Apache Hadoop, MLlib (Machine Learning Library in Apache Spark).
<p align="center">
  <img src="https://github.com/user-attachments/assets/0325f451-be32-4bf9-809f-95183be8fb9f" alt="Screenshot 1" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fc30ff06-fd75-45c6-8dbf-1553e5057e8e" alt="Screenshot 2" />
</p>

### 🎯 Personalized Dashboard
- A unique and personalized dashboard tailored for each user, based on their activity across the platform. It provides a comprehensive overview including:
- Summary of Scores **Problems Solved**, **Competition Score**, **Resume Score**.
- Overview of the user activity like **Upcoming Events**, **Company Applications**, **Upcoming Interviews**, **Latest Job Openings**, **Learning Progress**, **Your Timeline**, **Skill Assessment Dashboard**
<p align="center"> <img src="https://github.com/user-attachments/assets/e5811939-81fd-4ae5-9b96-7ded509a1a9a" alt="Screenshot 1" /> </p>
<p align="center"> <img src="https://github.com/user-attachments/assets/01300f35-3e56-443c-a276-31269efe30da" alt="Screenshot 2" /> </p>
<p align="center"> <img src="https://github.com/user-attachments/assets/d0990073-6c79-41a2-9fc5-59318a6deb6a" alt="Screenshot 3" /> </p>

### 🧠 Problem Section
- **Problem Tracking** Keeps track of problems you've **solved** and **favorited**, Shows your **progress across difficulties, tags, and levels** (analyzed using AI). Your personalized problem dashboard evolves with you
- **AI-Powered Recommendations And Daily Challenge** Suggests problems based on your **previous solving patterns** and One new problem every day to sharpen your skills
- **Curated Problem Sets** Categorized by **Difficulty**, **Company**, **Topics**. 
- **Enhanced Learning Experience** Include: **Detailed blogs**, **Step-by-step solutions**, **AI assistance** for each problem
<p align="center"><img src="https://github.com/user-attachments/assets/991a7e47-a383-4474-a003-d459c74a7d26" alt="Screenshot 2025-05-17 193045" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a50c7214-4d21-4192-93d8-b5d9655bd9dd" alt="Screenshot 2025-05-17 201059" /></p>

## 🏢 Company Insights
- Explore detailed statistics and insights about companies that have visited your college. Gain valuable information to help with your preparation and applications.
- Filter & View Company Stats: Filter data based on **Year**, **Department**, **Gender**/
- View a list of companies that visited your college.
- Company-Specific Insights: In-depth stats and performance history of a **specific company**. **Jobs posted**, **Problems**, **Tips & Tricks** by the company.
- Search to explore specific companies. Get a **detailed overview** of company data to prepare better.
<p align="center"><img src="https://github.com/user-attachments/assets/78aa23b2-e4ef-436f-9199-505e3dad0604" alt="Screenshot 1" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/393ad7b5-e0ab-49ad-a5eb-aad92aa776af" alt="Screenshot 2" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/2e45186f-d2ea-4241-96a5-dc8b3226a290" alt="Screenshot 3" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/7f4f703b-ec74-4d6e-b9b6-038b0cbdcf1c" alt="Screenshot 4" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/5dba288c-fb0f-4061-b5d8-6043fc50126e" alt="Screenshot 5" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/6593519b-7619-431b-9fe3-fc9a102bda9b" alt="Screenshot 6" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/0cd5e263-33b2-48ec-9677-781be096f3a2" alt="Screenshot 7" /></p>
<p align="center"><img src="https://github.com/user-attachments/assets/3af83e35-fb7f-4c0b-9b96-a0e4c3e4a5c8" alt="Screenshot 8" /></p>


Make informed decisions and strategize your preparation with data-driven insights.

Stay informed and track your growth, all in one place.


With Solo Levelling, you are no longer alone in your preparation journey.  
Stay aligned, stay sharp, and **level up on your own terms** to become the best version of yourself.

> 🎯 **Level up. Track progress. Win placements.**

---

### ⚔️ Them vs Us

| **THEM**                                                                 | **US**                                                                                          |
|--------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------|
| Multiple scattered methods for placement preparation                     | ✅ **All-in-One** solution within a single platform                                              |
| Different websites serve different needs (e.g., LeetCode, LinkedIn)      | ✅ Centralized access to all tools—**track, grow, and stay focused**                            |
| Newer platforms introduce AI assistance                                  | ✅ AI support integrated **in your native language** for better personalization and accessibility |
| Lacks seamless organization and self-tracking                            | ✅ **Organized self-assistance** and progress tracking built-in                                 |

---
