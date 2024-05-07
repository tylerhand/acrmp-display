# ACRMP Display

[![Netlify Status](https://api.netlify.com/api/v1/badges/969c0a76-7481-4a16-b7dc-695b351f646e/deploy-status)](https://app.netlify.com/sites/astounding-jelly-162c60/deploys)

This is hosted at [https://acrmp-display.tylerhand.com](https://acrmp-display.tylerhand.com)

Feel free to make changes to this repository to edit the display in the resource room. Submit a pull request to the main branch with any changes.

***
## Instructions
***

The display in the resource room is simply this webpage. There is a javascript function in the <head> that 
makes the page reload itself every two hours. To change this interval, see the comment below the function in 
the <script> tags and change the number in the function accordingly. The charts/quotes are daily settlement 
prices from TradingView (as are the widgets) - for shorter timeframes, TradingView requires a subscription 
(different from the ones for their regular service).


To add this to a new smart TV, you need to install a kiosk app that allows you to display a webpage. 


This repository is located at [github.com/tylerhand/acrmp-display](https://github.com/tylerhand/acrmp-display)

***
## Notes for Current TVs (as of when I left)
***

**Amazon Fire TV:** For this one, I installed a free kiosk app called ClickSimply. It does not appear to be 
currently maintained, however, it does the job. 


To display the page, just select the app from the homepage. It looks like this:


<img src="clicksimply-logo.jpg" alt="ClickSimply Logo" width="50"/>


**Google TV:** As of leaving, this has not been set up yet. Just send a link to this page to IT, and they'll know what to do.