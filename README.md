# GenAi-cold_email_generator
GenAi-cold_email_generator is an innovative tool that leverages the power of AI to generate personalized cold emails based on job descriptions and resumes. By utilizing LLM (Large Language Model) technology and the Langchain Chat Groq class, this project aims to streamline the process of crafting effective cold emails for job applications.
Features

Generates tailored cold emails using AI
Analyzes job descriptions to extract key requirements
Incorporates relevant skills from the provided resume
Utilizes LLM model for natural language generation
Implements Langchain Chat Groq class for enhanced interaction

How It Works

The system takes in a job description and a resume as input.
It analyzes the job description to identify key requirements and desired skills.
The resume is parsed to extract relevant skills and experiences.
Using the LLM model and Langchain Chat Groq class, the system generates a personalized cold email.
The generated email highlights the applicant's relevant skills and experiences that match the job requirements.

# Installation
    git clone https://github.com/officialhemant51/GenAi-cold_email_generator.git
    cd GenAi-cold_email_generator
    pip install -r requirements.txt

# Usage
    from cold_email_generator import ColdEmailGenerator
    
    generator = ColdEmailGenerator()
    job_description = "Your job description here..."
    resume = "Your resume content here..."
    
    cold_email = generator.generate_email(job_description, resume)
    print(cold_email)
    
# Requirements
    Requirements
    
    Python 3.7+
    LangChain
    Groq API key (for Chat Groq class)

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

# Acknowledgments

LangChain for providing the Chat Groq class
Groq for their LLM API

# Disclaimer
This tool is designed to assist in creating cold emails and should be used responsibly. Always review and personalize the generated emails before sending them to potential employers.
