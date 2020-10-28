Creating an App to Gather Tweets
================================

We'll be gathering tweets automatically with Twitter's API \(Application Programming Interface\); this will allow us to automate searches and return tweets in a more compressed, efficient format. 

Developer Access
----------------


To do this, you have to first set up a **Developer App** associated with your Twitter account. Twitter has recently implemented a more involved review process to apply for a Developer access, so this could take time.

Make sure to review the [Developer Terms](https://developer.twitter.com/en/developer-terms/policy). 
**A few highlights**:

- Your account has a `rate limit` to the number of requests you can process in a given time frame; if you go over, you may be throttled or (in extreme cases) suspended.
- There are more regulations on posting/editing content than there are on reading/scraping information
- You must respect people's privacy: when reading/scraping information, only allow information to be gathered from public accounts
- If you store Twitter Content offline, you have to make sure it's up to date with current status
    1. If something is deleted or made private after you collect it, you have to remove it.
    2. If a geotag is removed, you must also remove it
- When dealing with geodata, you can't separate geodata from tweets to (e.g.) track where an individual has been
    1. Dealing with geodata in the aggregate is allowed (e.g., how many people in X City are tweeting about Y)


**To Get Developer Access**

1. Create/Have a Twitter Account
1. Go to [https://developer.twitter.com/](https://developer.twitter.com/)
1. Choose "Apply for a Developer Account" 
1. Choose the option that best fits your needs (probably "Doing Academic Research" or "Student") and follow the prompts

Setting up an App
-----------------

Currently, twitter is in early access for v2 of its API and developer tools. There are some exciting things coming, but we'll be talking only about functionality in the current live version \(1.1\).

Because of this, we'll be creating a **Standalone App**, not a **Project** in the Developer Portal.

1. Select "Create App"
2. Select a unique name
3. At the API keys screen, copy and securely record these two values. The first one "Api Key" is your API Consumer Key. The second one "API Secret Key" is your API Consumer Secret Key.
4. The default settings for the app should be fine for our purposes.
5. Under "Authentication Tokens" find "Access Token and Secret" and click "Generate". Securely save these two values somewhere.

**Whatever you do, keep all four of these values secret and safe!**

**Do not accidentally distribute them in code, or leave them written down in a public place!**

**These codes can be used by nefarious individuals to have complete control of your Twitter account and cause you immense sadness.**