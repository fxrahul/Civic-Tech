Developing better Civic Services through Crowdsourcing: The Twitter Case Study

To run the given python code on twitter case study. Follow the below steps:

1. Run the given cell chunks in the jupyter notebook or google colab. All the cells have comments within it to understand the code.
2. For running the first cell, you will need a service access token for OAuthHandler API to work. You can do so by opening an account on https://apps.twitter.com/app/new
3. This website will ask you to create an application. Fill the required details in it and hit 'Create Application'.
4. After creating Twitter Application click on the tab that says Keys and Access Tokens, then you have to give access to your Twitter Account to use this Application. To do this, click the Create my Access Token button.
5. Once you get the consumer token, consumer secret and access token, access token secret, Copy those keys to the first cell in OAuthHandler and set_access_token function respectively.
6. Run the first chunk for at least an hour or two to get the huge chunk of twitter data. This tweet data will get saved to the 'tweetDB.csv' file.
7. Stop this running chunk after a while and then start executing below chunks one by one.
8. In classifier section, you have to give the path of your saved tweetDB.csv to evaluate your coherence score measure.