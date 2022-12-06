# RainFall-Prediction

Deployment steps:

<br>We have used ngrok for deployment. ngrok is a cross-platform application that enables developers to expose a local development server to the Internet with minimal effort.<br>
<br>Deployment step
<br>Download code from github - https://github.com/yarradedeepya/RainFall-Prediction/blob/main/Rainfall-Prediction5502.ipynb
<br>Create an account with ngrok and save the auth token associated with your account. 
<br>Install Nginx and open command prompt with administrator permission.
<br>add authtoken to ngrok configuration using below command.
<br>        ngrok config add-authtoken TOKEN
<br>Run the app.py file and then run the below command in command prompt
<br>ngrok http 5000
<br>It will output the url of the hosted site, go to the url and use it.
