# Cruise0-Demo
A demonstration of an SPA that supports sign in and sign out. 
This is an extremely ugly Java script Single Page Application (SPA).

It displays a web page and a log in button, clicking the login button invokes Auth0' new usiveral login, offering login and sign up options. You can sign in with username and password, Google or LinkedIn. 
It also implements Auth0's account linking extension, but I have not got that working as well as I would like. 
I would have liked to add a Flow that prevents the user from logging in until their email is verified and shows a message advising the user of this. Unfortunately my ability to write JS is pretty bad and I can't figure out how to change the content displayed by an SPA to do this, so while the Flow works the UI does not support it. 

*Deployment*
1. Download the files to your local machine.
2. Create an Auth0 SPA JS Application and enable social login
3. Intall the AcountLink extension
3. Populate auth_config.json with your Auth0 Domain and Client ID
4. In the root directory of your application run <npm install express> and <npm install -D nodemon>
5. To run the application - type <npm run dev>

*You may then weep at the travesty of the thing I have made, but had a lot of fun doing*
