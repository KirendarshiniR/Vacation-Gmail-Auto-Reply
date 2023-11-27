# Auto Reply Gmail Bot using Node.js 
```bash
#Description

Description
-This is a repository for Auto_reply_gmail_api_app App Developed using Node.js and Google APIs.
-This app  is able to respond to emails sent to your Gmail mailbox while you’re out on a vacation.
```
```bash
# Features

 Features
- Node.js clusters support.
- Checks for new emails in a given Gmail ID.
- Sends replies to emails that have no prior replies.
- Adds a label to the email and moves the email to the label.
- This app checks above steps every 45 to 120 in b/w sec  random time interval. 
```
```bash
# Libraries  

 Libraries  
-1.googleapis:This package is imported from the googleapis module and provides the necessary functionality to interact
   with various Google APIs, including the Gmail API.
-2.OAuth2:The OAuth2 class from the google.auth module is used to authenticate the application and obtain an access
   token for making requests to the Gmail API. It handles token refresh and retrying requests if necessary. 
```
```bash
# Getting Started

 Getting Started

First Thing to do go to Google Cloud Console and set up the OAuth 2.0 authentication for
your application, follow these steps:

6. In the "Authorized redirect URIs" field, enter the redirect URI where you want to receive the authorization
   code. For this code, you can use "https://developers.google.com/oauthplayground".
8. Click on the "Create" button to create the OAuth client ID. You will see a modal displaying the client ID
   and client secret. Copy the values of the client ID and client secret.
   and client secret. Copy the values of the client ID and client secret. and also enable gmail api 
9. Now, open the OAuth 2.0 Playground (https://developers.google.com/oauthplayground).
10.In the OAuth 2.0 Playground, click on the settings icon (gear icon) on the top right corner. In the
   "OAuth 2.0 configuration" section, enter the client ID and client secret obtained in the previous step.
   Replace REDIRECT_URI with the redirect URI value.
   Replace REFRESH_TOKEN with the refresh token value.
17.Save the credentials.js file.
```

The easiest way to get started is to clone the repository:
```bash
# Get the latest snapshot
@@ -73,8 +70,8 @@ npm start

<h3> <a href = "https://github.com/Sahil-Sayyad/Auto_reply_gmail_api_app"> CODE</a> </h3><br>

```bash
#note on areas where your code can be improved.

note on areas where your code can be improved.
1.Error handling: The code currently logs any errors that occur during the execution but does not
  handle them in a more robust manner.
2.Code efficiency: The code could be optimized to handle larger volumes of emails more efficiently.
@@ -85,5 +82,5 @@ npm start
  These are some areas where the code can be improved, but overall, it provides implementation of
  auto-reply functionality using the Gmail API.
5.Time Monitoring: The code currently use randominterval function to generate seconds and in this code can be improved by adding cron jobs package to schedule email tasks 
```

