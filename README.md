# RainFall-Prediction

Deployment steps:

We have used ngrok for deployment. ngrok is a cross-platform application that enables developers to expose a local development server to the Internet with minimal effort.
Deployment step
Download code from github - https://github.com/yarradedeepya/RainFall-Prediction/blob/main/Rainfall-Prediction5502.ipynb
Create an account with ngrok and save the auth token associated with your account. 
Install Nginx and open command prompt with administrator permission.
add authtoken to ngrok configuration using below command.
        ngrok config add-authtoken TOKEN
Run the app.py file and then run the below command in command prompt
ngrok http 5000
It will output the url of the hosted site, go to the url and use it.
