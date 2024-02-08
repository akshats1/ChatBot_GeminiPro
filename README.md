
# ChatBot-Gemini Web App
This is official repository of ChatBot-gemini web App
using geminiPro api,LLM(large Language Change Model) and streamlit

Official deployment:https://chatbot-gemini-v1-akshat.onrender.com/




## Tech Stack

**Client:** Python,Geminiai-pro,streamlit

**Server:** streamlit,render.com


## Output

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




## License
MIT License

Copyright (c) [2024] [Akshat]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.