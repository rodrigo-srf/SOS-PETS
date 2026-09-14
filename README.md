# 🐾 S.O.S Pets — AI-Powered Animal Adoption Assistant

S.O.S Pets is an AI-assisted application designed to help NGOs, animal rescuers and individuals create clear, engaging adoption content from pet information and uploaded images.

The project combines **Python, Streamlit, Amazon Bedrock and AWS** in an end-to-end workflow that collects adoption details, maintains conversational context and generates human-centered content for social media and adoption listings.

## Why this project matters

Animal rescuers often need to create many adoption posts quickly and consistently. S.O.S Pets explores how generative AI can reduce that manual effort while keeping the interaction friendly, structured and useful.

## Key features

- Conversational AI workflow for collecting adoption information
- Pet image upload and multimodal interaction flow
- Context-aware conversation history
- Adoption copy generation for social media
- Authentication middleware
- Safety-oriented handling for wildlife-related cases
- AWS integration through Amazon Bedrock
- Streamlit-based user interface

## Tech stack

- **Language:** Python
- **Frontend / App framework:** Streamlit
- **Generative AI:** Amazon Bedrock
- **AWS SDK:** Boto3
- **Cloud:** AWS EC2
- **Data / document utilities:** Pandas, PyPDF2
- **Version control:** Git / GitHub

## Architecture

```text
User
  │
  ▼
Streamlit UI
  │
  ├── Authentication middleware
  │
  ├── Conversation state / user inputs
  │
  ▼
Python application layer
  │
  ├── Prompt construction
  ├── Context handling
  ├── File / data utilities
  │
  ▼
Amazon Bedrock Runtime
  │
  ▼
Generated adoption assistance
```

The AWS client is created through Boto3 and is designed to use the IAM role associated with the runtime environment when deployed on EC2.

## Repository structure

```text
SOS-PETS/
├── app.py                 # Main Streamlit application
├── functions.py           # Bedrock integration and application utilities
├── auth_middleware.py     # Authentication middleware
├── requirements.txt       # Python dependencies
├── .env.example           # Local environment configuration example
└── images/                # Project assets and screenshots
```

## Running locally

### Requirements

- Python 3.8+
- AWS credentials or an AWS profile with access to the required Bedrock resources
- Amazon Bedrock access enabled in the selected AWS region

### Setup

```bash
git clone https://github.com/rodrigo-srf/SOS-PETS.git
cd SOS-PETS

python -m venv .venv
```

Linux / macOS:

```bash
source .venv/bin/activate
```

Windows:

```powershell
.venv\Scripts\activate
```

Install dependencies and start the app:

```bash
pip install -r requirements.txt
streamlit run app.py
```

For local development, copy `.env.example` to `.env.local` and adjust the AWS profile if needed. Do not commit local credential or environment files.

## Engineering highlights

This project demonstrates practical experience with:

- Python application development
- LLM / generative AI integration
- AWS service integration with Boto3
- Prompt and conversational-context design
- Authentication middleware
- File and structured-data processing
- Cloud-oriented application architecture

## Academic context

The project was developed as part of an Artificial Intelligence training program connected to **Escola da Nuvem / AWS re/Start**.

## Team

- [Rodrigo Serafim](https://github.com/rodrigo-srf)
- [Dayane Stefhany](https://github.com/daystefhany)
- [Brandon Lee](https://github.com/Devbrandlee)
- [Beatriz Lima](https://github.com/beadlim)
- [Gabriel Carmo](https://github.com/gabriel-souzacarmo)
- [Jonas Oliveira](https://github.com/jonasoliveira011)

## License

MIT License

---

**Portfolio focus:** Python · Generative AI · AWS · Streamlit · Cloud Integration
