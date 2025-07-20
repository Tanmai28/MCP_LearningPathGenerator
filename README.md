# MCP_LearningPathGenerator
AI-powered app that generates personalized learning paths from YouTube, Drive, and Notion based on your goals.

---

# 🚀 Learning Path Generator with Model Context Protocol (MCP)

MCP Learning Path Generator is an AI-powered Streamlit web application that helps you create personalized, goal-driven learning paths using the latest Model Context Protocol (MCP) technology. Seamlessly integrating with YouTube, Google Drive, and Notion, this tool curates high-quality resources and organizes them into actionable steps—empowering you to master any topic efficiently.

---

## Features

- 🎯 Generate personalized learning paths based on your goals
- 🎥 Integration with YouTube for curated video content
- 📁 Google Drive integration for document storage
- 📝 Notion integration for note-taking and organization
- 🚀 Real-time progress tracking and feedback
- 🎨 User-friendly Streamlit interface

---

## Prerequisites

- Python 3.10+
- Google AI Studio API Key
- Pipedream URLs for integrations (YouTube and either Drive or Notion)

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd mcp-learning-path-demo-main
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Configuration

Before running the application, you'll need to set up:

1. **Google API Key** (from Google AI Studio)
2. **Pipedream URLs** for:
   - YouTube (required)
   - Google Drive or Notion (choose one as your secondary tool)

---

## Running the Application

To start the application, run:
```bash
streamlit run app.py
```
The application will be available at [http://localhost:8501](http://localhost:8501) by default.

---

## Usage

1. Enter your Google AI Studio API key and Pipedream URLs in the sidebar.
2. Select your preferred secondary tool (Drive or Notion).
3. Enter your learning goal (e.g., "I want to learn python basics in 3 days").
4. Click **"Generate Learning Path"** to create your personalized learning plan.
5. Follow the progress and review your generated learning path in the main area.

---

## Project Structure

- `app.py` - Main Streamlit application and UI logic
- `utils.py` - Utility functions and helper methods (including agent logic)
- `prompt.py` - Prompt template for the agent
- `requirements.txt` - Project dependencies

---

## How It Works

1. **User Input:** You provide your learning goal and integration details.
2. **Agent Setup:** The app configures an AI agent with YouTube and your chosen secondary tool (Drive/Notion).
3. **Learning Path Generation:** The agent curates a step-by-step learning path using YouTube content and organizes resources in your selected tool.
4. **Progress Tracking:** The app provides real-time feedback as your learning path is generated.

---

## Troubleshooting

- Ensure all API keys and URLs are correct and active.
- If you encounter errors, check the Streamlit logs for details.
- For issues with integrations, verify your Pipedream workflows are set up and accessible.

---
<img width="940" height="459" alt="image" src="https://github.com/user-attachments/assets/9674ad31-2e3e-4dcd-bed6-818e5cca505f" />
