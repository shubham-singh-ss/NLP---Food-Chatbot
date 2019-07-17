# NLP---Food-Chatbot

To deploy the project

1. Open terminal and clone this repository. After cloning, change your directory to the cloned folder.
2. Run <strong>pip install -r requirements.txt</strong>
3. Go to https://developers.zomato.com/api and generate an API.
4. Now, in terminal, type <strong>make train-nlu</strong>
5. After that, run <strong>make train-core</strong>
6. Now, run <strong>make action-server</strong>
7. Now open a new terminal window, and type ngrok http 5002, and copy forwarding link
8. Paste that link in endpoints.yml. as -> url = "forwarding link/webhook"
