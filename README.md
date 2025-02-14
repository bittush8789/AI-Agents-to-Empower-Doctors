# AI Agents to Empower Doctors

This Streamlit-based web application leverages AI agents to provide medical diagnosis and treatment recommendations. The application utilizes the LLama model to analyze patient symptoms and medical history and provide preliminary diagnosis and treatment.

## Features

- **User Inputs:** Capture patient information such as gender, age, symptoms, and medical history.
- **AI Agents:** 
  - **Medical Diagnostician:** Analyzes patient symptoms and medical history to provide a preliminary diagnosis.
  - **Treatment Advisor:** Recommends treatment plans based on the diagnosis provided.
- **Tools:** Uses web scraping and search tools to gather relevant information.
- **Generating Word Document:** Creates a Word document containing the diagnosis and treatment plan and provides a download link.
- **Streamlit Integration:** Interactive user interface to input data and obtain AI-generated recommendations.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

2. Install the required packages:
   ```bash
   pip install -r requirements.txt

3. Create a .env file and add the following environment variables:
    ```bash

   GROQ_API_KEY=<your_groq_api_key>
   SERPER_API_KEY=<your_serper_api_key>


Usage
1. Run the Streamlit app:

```bash
streamlit run app.py

2. Open your web browser and navigate to http://localhost:8501.

3. Enter the patient information:

Select gender
Enter ag
Enter symptoms
Enter medical history

4. Click the "Get Diagnosis and Treatment Plan" button.

5. Wait for the AI agents to analyze the information and generate the recommendations.

6. Download the Word document containing the diagnosis and treatment plan.

Hash node blog link : https://bittublog.hashnode.dev/ai-powered-healthcare-assistant-with-streamlit-and-crewai
