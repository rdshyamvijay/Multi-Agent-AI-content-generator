Multi-Agent AI Content Generator

Overview

This project is a multi-agent AI system built using CrewAI that automates the process of researching, writing, and editing articles. The system consists of three AI agents that work together:
	1.	Planner Agent - Conducts research and organizes structured information.
	2.	Writer Agent - Uses the planner’s research to create a well-structured article.
	3.	Editor Agent - Reviews and refines the article for clarity, coherence, and accuracy.

This system is designed to streamline content creation using advanced AI models.

Technologies Used
	•	CrewAI
	•	LangChain Community
	•	OpenAI API
	•	Python

Installation
	1.	Clone the repository:
git clone https://github.com/YOUR_USERNAME/Multi-Agent-AI-content-generator.git
	2.	Navigate into the project directory:
cd Multi-Agent-AI-content-generator
	3.	Install required dependencies:
pip install -r requirements.txt
	4.	Set up the environment variables:
Create a .env file in the root directory and add your API keys as follows:

OPENAI_API_KEY=your_openai_api_key_here
SERPER_API_KEY=your_serper_api_key_here

Replace your_openai_api_key_here and your_serper_api_key_here with your actual API keys.

How It Works
	1.	The Planner Agent gathers information on a given topic and creates an outline.
	2.	The Writer Agent converts the structured information into a well-written article.
	3.	The Editor Agent reviews and refines the article to ensure it meets quality standards.
	4.	The final article is generated and ready for publication.

Running the Project
	1.	Open the Jupyter Notebook environment:
jupyter notebook
	2.	Open L2_research_write_article.ipynb and run the notebook.
	3.	The agents will collaborate to generate a research-based article.

Contributing

If you’d like to contribute, feel free to fork the repository, submit issues, or make pull requests to improve the project. Any contributions to enhance the AI agents or optimize the workflow are welcome!
