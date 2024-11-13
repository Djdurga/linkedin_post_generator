# Linkedin Post Genetor

<img width="946" alt="Screenshot 2024-11-13 at 6 24 04 PM" src="https://github.com/user-attachments/assets/d7396993-86d5-49d4-8107-2eb7b52b1b3d">


<img width="1152" alt="Screenshot 2024-11-13 at 6 51 43 PM" src="https://github.com/user-attachments/assets/e7e18851-b93c-44c9-b887-066e6360fd98">



## Setup

To get started, follow these steps:

1. **Obtain an API Key**  
   - Visit [Groq Console](https://console.groq.com/keys) to create an API key.
   - Update the `.env` file by setting the value of `GROQ_API_KEY` with the API key you created:
     ```env
     GROQ_API_KEY=your_api_key_here
     ```

2. **Install Dependencies**  
   - Run the following command to install the necessary dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Streamlit App**  
   - Start the Streamlit application by running:
     ```bash
     streamlit run main.py
     ```

## Additional Information

- Make sure you have Python and Streamlit installed on your system.
- Check the `requirements.txt` file for the specific versions of each package needed.

