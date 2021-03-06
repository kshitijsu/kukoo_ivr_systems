# **Kookoo IVR System using NodeJS**

## What is Kookoo?
KooKoo is an interface between your web application and the caller. It takes phone commands from you and executes them on your behalf to the caller. The best way to think of KooKoo is as just another web page in your application. Only difference is, the web page is accessible from the phone rather than the browser.

### How to run the code?
First clone the repository by running following command on your terminal :
``` sh
$ git clone https://github.com/kshitijsu/kookoo_ivr_systems.git
```
Now, download ngrok and configure it. Docs link is mentioned below:
https://ngrok.com/docs

Download node from https://nodejs.org/

Go to the folder and run the npm command to install all dependencies.
Use editor like VScode or Atom having inbuilt terminal
```sh 
$ npm install
```
When everything is correctly installed, run the command
```sh 
$ nodemon app.js
```
and run ngrok in background
```sh 
$ ngrok http 8080
```
Now go to kookoo.in and register with your email id 
Provide kookoo with the public URL generated by ngrok and save.

Call on the numbers shown in the kookoo dashboard.
Use the pin to access your application(Pin provided in the dashboard).
