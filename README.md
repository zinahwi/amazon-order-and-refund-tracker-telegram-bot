
<!---
============================================================================
                  CURSOR AI INSTRUCTIONS - DO NOT MODIFY
============================================================================
-->

<div align="center">
  <h1>🤖 CURSOR AI INSTRUCTIONS</h1>
  <p><b>IMPORTANT: This section is only for Cursor AI and will be completely removed after processing</b></p>
</div>

---

## AI Task: Complete README Transformation

Hello Cursor AI! Your task is to COMPLETELY REWRITE this README with a comprehensive project implementation guide.

### Critical Requirements:

1. **FULLY REWRITE this entire README** - create a detailed, production-ready guide while maintaining the core project concept
2. **Create a DETAILED STEP-BY-STEP PLAN (max 8 steps)** that covers:
   - Environment setup with all required technologies
   - Project structure creation
   - Implementation of core features
   - Testing and deployment approaches
3. **Tailor content to the user's profile:**
   - User's Experience Level: `Beginner`
   - User's Available Time: `A Few Days`
4. **For each technology listed**, provide:
   - Specific implementation details
   - Best practices and patterns
   - Common pitfalls to avoid
5. **Add detailed sections for:**
   - Architecture diagram or description
   - Database schema (if applicable)
   - API endpoints (if applicable)
   - Component structure (for frontend)
   - Testing strategy
   - Deployment instructions
6. **Provide code examples** for critical project parts
7. **REMOVE THESE INSTRUCTIONS COMPLETELY** after your rewrite

Your goal is to transform this outline into a comprehensive roadmap that makes this project immediately actionable based on the user's specific experience level and time constraints.

### ⚠️ CRITICAL FIRST STEP ⚠️

**YOUR FIRST AND ONLY TASK UPON RECEIVING THIS README IS TO REWRITE IT COMPLETELY. DO NOT START IMPLEMENTING THE PROJECT OR WRITING ANY CODE YET.**

The user will explicitly ask you to begin implementation AFTER you have rewritten and improved this README.

<!---
============================================================================
                 END OF CURSOR AI INSTRUCTIONS
============================================================================
-->


# Amazon Order and Refund Tracker Telegram Bot

## Project Overview
A Telegram chatbot that helps track and organize Amazon orders and refunds, utilizing machine learning for data inconsistencies and alert systems for notifications.


> **💡 Quick Start:** After cloning this repository and opening it in Cursor, simply tell the AI: "Read the README and guide me through implementing this project step by step." Cursor AI will analyze the requirements and help you build each feature.


## User Profile
- **Experience Level:** Beginner
- **Available Time to Complete:** A Few Days

## Technologies
- **Python**: Primary programming language for the bot's logic
- **Telethon**: Telegram API client for creating and interacting with the chatbot
- **TensorFlow**: Machine learning framework for handling data inconsistencies and conflicts
- **Google Sheets API**: Cloud-based spreadsheet storage for storing and updating order and refund data
- **OpenCV**: Image processing library for extracting data from refund screenshots


## Development Steps
### 1. Setup Telegram Bot and Google Sheets API
Create a new Telegram bot, set up a Google Cloud account, and enable the Google Sheets API

### 2. Design and Implement Data Extraction from Refund Screenshots
Use OpenCV to extract relevant data from refund screenshots, and implement a machine learning model to handle inconsistencies

### 3. Implement Alert System for Refund Notifications
Design and implement an alert system that notifies the user of new refunds and updates the Google Sheets database

### 4. Integrate Machine Learning Model for Data Inconsistencies
Train and integrate the machine learning model to handle data inconsistencies and conflicts

### 5. Implement User Interaction and Data Visualization
Design a user-friendly interface for the Telegram bot, and implement data visualization for the user to easily track orders and refunds

### 6. Test and Refine the Bot
Test the bot with sample data, refine the machine learning model, and ensure the bot works seamlessly with the Google Sheets API


## Main Features
Features will be added soon


## Sample Code
```python
// Example code snippet for extracting data from refund screenshot
import cv2
import tensorflow as tf

# Load refund screenshot image
img = cv2.imread('refund_screenshot.jpg')

# Preprocess image and extract relevant data
# ...
```


## Getting Started
Instructions will be added soon

## Resources
- [Telethon Documentation](https://docs.telethon.dev/en/latest/) (documentation)
- [TensorFlow Tutorial](https://www.tensorflow.org/tutorials) (tutorial)
- [Google Sheets API Documentation](https://developers.google.com/sheets/api) (documentation)
- [OpenCV Tutorial](https://docs.opencv.org/master/d9/d61/tutorial_py_kmeans.html) (tutorial)
- [Python for Beginners](https://www.w3schools.com/python/) (tutorial)


## AI Coding Prompts

Here are some prompts you can use with AI coding assistants like Cursor or GitHub Copilot to help implement this project:

### Prompt 1
```
Implement the refund screenshot processing logic in Python. Start by loading the 'refund_screenshot.jpg' image using OpenCV's `imread()` function and display it on the screen. Then, use TensorFlow's `tf.image` module to preprocess the image and extract relevant data. For example, you can use the `tf.image.resize()` function to resize the image to a consistent size and the `tf.image.rgb_to_grayscale()` function to convert the image to grayscale.
```

### Prompt 2
```
Develop the core functionality of the Amazon Order and Refund Tracker Telegram Bot in Python. Use Telethon's `TelegramClient` class to create a Telegram bot and define a command to handle refund-related messages. When a user sends a refund screenshot, use OpenCV and TensorFlow to extract relevant data and store it in a Google Sheets document. Implement a machine learning model using TensorFlow to handle data inconsistencies and conflicts.
```

### Prompt 3
```
Enhance the Amazon Order and Refund Tracker Telegram Bot by implementing advanced features in Python. Use TensorFlow's `tf.data` module to load and preprocess the data stored in Google Sheets. Then, use a machine learning model to predict potential issues with refunds and send notifications to users through the Telegram bot. You can also use OpenCV to perform optical character recognition (OCR) on the refund screenshot and extract specific information, such as the refund amount and reason.
```


Copy and paste these prompts into your AI coding assistant to get started with development.


---
*Generated by [CodeSpark](https://github.com/YOUR_USERNAME/codespark)*
