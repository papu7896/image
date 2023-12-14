# AI Image Generation App

This is a Streamlit app for generating images using OpenAI's DALL-E and Huggingface Diffusers. The app allows users to input text prompts, and AI models generate corresponding images.

## Getting Started

### Prerequisites

- Python 3.x
- Install required libraries by running: `pip install streamlit openai diffusers torch`

### Configuration

1. Obtain an API key from OpenAI and set it as an environment variable. You can find more information on obtaining an API key [here](https://beta.openai.com/signup/).

    ```bash
    export OPENAI_API_KEY=your_api_key
    ```

2. Create a virtual environment (optional but recommended).

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required packages.

    ```bash
    pip install -r requirements.txt
    ```

### Usage

Run the Streamlit app using the following command:

```bash
streamlit run app.py
