# Tweeter - CLI Python Twitter Client


## Dependencies
   Tweeter uses the following packages:

   tweepy: for handling Twitter API calls

   simplecrypt: for encrypting API credentials on the user's system

   pytest: for testing classes

   setup.py automatically attempts to install these packages if 
   you do not already have them.

## Install and Documentation
   After installing dependencies, run install.sh to install Tweeter. For bash:

   $ sh install.sh

   To create new HTML documentation, run:
   
   $ sh docs.sh

## Tweeter App

   Tweeter lets you save your credentials for multiple Twitter accounts by 
   creating a Tweeter user. You can choose to use a password (which will
   encrypt your API credentials) or not. If you do not use a password, your
   credentials will be saved in plaintext in a .csv file. Tweeter allows
   you to save multiple credential files under any usernames you like.
   These files are saved in /profiles
   
   The Tweeter username does not have to be your Twitter username, it's just
   a way to save the credentials to your system.

   To launch Tweeter, run:
   
   $ tweeter

   To launch Tweeter for a specific Tweeter username, run:
   
   $ tweeter [USERNAME]

   If Tweeter can't find your user file, it will create one.

   Tweeter authenticates your Twitter using one of two methods:
   
   1). Manually entering your consumer key, consumer secret, access token
       and access token secret generate from apps.twitter.com
   
   2). Manually entering your consumer key and consumer secret, and then 
       following a link to get a verification pin to verify the account.

   To get your consumer key and consumer secret:
   1. Go to apps.twitter.com and sign in
   2. Click "Create New App"
   3. Fill in the required fields and click "Create your Twitter Application"

   To get your consumer key and consumer secret:
   
   4. From the "Keys and Access Tokens" site, scroll down to Your Access Tokens
   5. Click "Create my Access Tokens" under Token Actions
   6. This will generate an "Access Token" and "Access Token Secret"




