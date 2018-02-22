# Modern CSS lunch-n-learn

These are the "pre-reqs" for the lunch-n-learn
* [This repo](https://github.com/chrisstahl/modern-css) (the one you're reading this in now) - I created a small repo with some startup files so that we can get up and running quickly. Please fork the repo to your own account before cloning.
* [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) - This isn't a **requirement** but there are some great tools for viewing layout in Firefox Developer Edition that just aren't available or as easy to use in Chrome or Edge. If you don't want to use this, but do want to use the browser-sync module, you'll need to make a change to the package.json file so that you point to your browser of choice.
* [Visual Studio Code](https://code.visualstudio.com/) - Again, not a requirement but it has [emmet](https://emmet.io/) which makes creating multiple DOM elements easy. I'll give you some code snippets as we go.
* [NodeJS](https://nodejs.org/en/) - Still not a requirement. However, it means you can use browser-sync so that you see your changes as soon as you save your file instead of having to refresh the page.

## browser-sync
To wire up browser-sync, in your terminal or command prompt navigate to where you cloned your repo. (e.g. /Users/yourAccountName/Documents/modern-css) \
Type\
`npm install`\
So long as you aren't having proxy issues, it should download all of your node modules (browser-sync has a few dependencies).\
Then type\
`npm start`\
This should launch your browser and show you a file structure! \
Open **01 - Setup** and click **test.html**

You should see:\
![Hello, World!](https://s3-us-west-2.amazonaws.com/s.cdpn.io/269209/hello_world.png)
