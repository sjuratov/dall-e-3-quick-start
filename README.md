### Getting Started
- Create virtual environment

`python -m venv .venv`

- Activate virtual environment (on Windows)

`.venv\Scripts\activate.bat`

- Install Python libraries

`pip install -r requirements.txt`

- Create .env file with following variables. Use values appropriate to your environment

```
AZURE_OPENAI_ENDPOINT = "https://<REPLACE_ME>.openai.azure.com/"

AZURE_OPENAI_API_KEY = "<REPLACE_ME>"

AZURE_OPENAI_DALL_E_DEPLOYMENT = "<REPLACE_ME>"
```
