
# ChatBot-Gemini Web App
This is official repository of ChatBot-gemini web App
using geminiPro api,LLM(large Language Change Model) and streamlit

Official deployment:https://chatbot-gemini-v1-akshat.onrender.com/




## Tech Stack

**Client:** Python,Geminiai-pro,streamlit

**Server:** streamlit,render.com


## Output
![Screenshot 2024-02-09 020518](https://github.com/akshats1/ChatBot_GeminiPro/assets/6964294/47c88fc0-f33c-4ba7-9939-cc722fd9248c)


## Demo

https://chatbot-gemini-v1-akshat.onrender.com/


## Deployment

To deploy this project run
```bash
  pip install google-generativeai

```


```bash
  streamlit run app.py
```
```bash
  pip install requirements.txt
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`GOOGLE_API_KEY`
Configure it with following code

GOOGLE_API_KEY=userdata.get('GOOGLE_API_KEY')

genai.configure(api_key=GOOGLE_API_KEY)







