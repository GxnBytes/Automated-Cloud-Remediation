# AI-Powered Customer Support Chatbot on AWS

> 🌐 A cloud-based chatbot for real-time customer support using Amazon Lex, Lambda, Connect, DynamoDB, and SageMaker — built to automate and enhance the customer experience across web, mobile, and voice channels.

![Status](https://img.shields.io/badge/status-In%20Development-yellow)

---

## 🚀 Project Overview

This project builds an intelligent, multi-channel **customer support chatbot** on **Amazon Web Services (AWS)**. Using **AI and serverless technologies**, the bot can engage in natural conversation, respond to queries in real-time, and escalate to human agents when needed.

The chatbot leverages **Amazon Lex** for natural language understanding (NLU) and speech recognition (ASR), integrates with **AWS Lambda** for backend logic, supports voice interaction through **Amazon Connect**, and stores session data using **DynamoDB** and **S3**. It uses **Amazon SageMaker** for continuous improvement through machine learning, and **Amazon Cognito** for secure user authentication.

---

## 🎯 Objectives

- Deliver immediate, personalized customer support via chatbot
- Automate backend responses and data handling with serverless tools
- Support multi-channel interaction including web, mobile, and voice
- Continuously improve the chatbot using machine learning
- Practice cloud architecture using Infrastructure as Code principles

---

## 🛠️ Tools & AWS Services Used

| Service              | Purpose                                                                 |
|----------------------|-------------------------------------------------------------------------|
| **Amazon Lex**        | Natural Language Understanding (NLU) & Automatic Speech Recognition (ASR) |
| **AWS Lambda**        | Backend logic for handling user inputs and triggering responses         |
| **Amazon Connect**    | Enables voice-based support and call routing to human agents            |
| **Amazon DynamoDB**   | NoSQL database to store conversation logs, feedback, and session data   |
| **Amazon S3**         | Static content storage (e.g., images, PDFs used in bot responses)       |
| **Amazon SageMaker**  | Machine learning for ongoing chatbot training and improvement           |
| **Amazon Cognito**    | User authentication and access control                                  |

---

## 📁 Project Structure

```bash
aws-ai-chatbot/
├── terraform/ # Infrastructure as Code (if used)
├── lambda/ # Lambda functions
├── lex-bot-definition/ # Lex bot intents and slot definitions
├── connect-setup/ # Amazon Connect configs
├── s3-content/ # Static files for chatbot responses
├── README.md
└── .gitignore
```
## ✅ Outcome

- Hands-on experience with **AWS Lex, Lambda, Connect, DynamoDB, S3, SageMaker, and Cognito**
- Built a **real-world AI chatbot** with natural conversation capabilities
- Applied **Infrastructure as Code (IaC)** and AWS-native tools to create scalable, intelligent support systems
- Gained exposure to **AI, serverless architecture, and user authentication**
