# InsightAgent-AI-Powered-Deep-Research-Assistant

An intelligent research assistant built with the Agno Agent framework, Together AI’s Qwen model, and Composio tools. InsightAgent streamlines complex research by generating tailored research questions, sourcing answers from multiple web engines, and compiling structured, professional-grade reports—automatically delivered to Google Docs.

🚀 Features
🧠 AI-Driven Question Generation
Automatically generates 5 tailored yes/no research questions based on your topic and selected domain

Focuses on clarity and specificity for actionable research outcomes

🔍 Multi-Source Web Research
Integrates Tavily Search and Perplexity AI for comprehensive, multi-perspective insights

Combines search results into coherent summaries

📄 Executive-Level Report Generation
Compiles findings into a McKinsey-style structured report

Includes executive summary, key findings, and conclusion

Automatically exported to Google Docs for easy sharing

💻 Streamlit-Based UI
Intuitive interface with clear step-by-step workflow

Real-time research progress tracking

Expandable sections to explore source-level insights

⚙️ How to Run
1. Clone the Repository

2. Install Dependencies

pip install -r requirements.txt

3. Connect Composio Integrations

composio add googledocs
composio add perplexityai

4. Configure API Keys
Get your Together AI API key from Together AI

Get your Composio API key from Composio

Add them to a .env file or enter them directly in the sidebar interface

5. Launch the App

streamlit run ai_powered_deep_research_agent.py

🧪 How to Use
Enter API keys via the sidebar.

Input a research topic and target domain.

Click “Generate Research Questions” to produce domain-specific yes/no questions.

Click “Start Research” to begin multi-engine data collection.

After results are summarized, click “Compile Final Report.”

Access your formatted report in both the app and Google Docs.

🔍 Example Use Cases
Academic Research: Literature scans and topic exploration

Market Intelligence: Competitor research and industry trends

Policy Briefing: Policy history, stakeholder mapping, and impact analysis

Tech Evaluation: Review of emerging technologies and adoption readiness

🛠️ Tech Stack
Component	Purpose
Agno Framework	Agent orchestration and workflows
Together AI (Qwen)	LLM-based language understanding
Composio	Integration with Google Docs, search engines
Streamlit	User interface and frontend logic

📦 Dependencies
agno
composio_agno
streamlit
python-dotenv

