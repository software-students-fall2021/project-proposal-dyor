# DYOR

## What and why?

DYOR is a NOT-A-FINANCIAL-APP Financial App, with there being no transactions involved in the app. Instead, DYOR is a service that seeks to enable investment in the Crypto and Equity markets. The Crypto market has become increasingly dangerous (with the manipulation of prices by notable personalities, “false” signal groups that are in truth Pump-and-Dumps, and sh*t coins), and there have been several casualties to this danger (members of this group included with regards to DOGE). DYOR seeks to make portfolio management and investment research easier for users of the Web-App, through the maintenance of a “Paper Portfolio” wherein users input the details for their present open positions so that they may keep track of the same, and the therein Profit/Loss with dynamic graphs (TradingView API) through a convenient Web-App as opposed to manual calculations as would be the case for hardware wallets, and without the inconvenience of multiple factor authentication (requiring a picture, OTP, password, captcha) only usable on verified devices as would be the case for a reputable exchange application. Beyond that, users would be provided with an alternate “Practice Portofolio” wherein they would be provided false dollars so that they make paper-trades and avoid financial losses as they learn. This enables a certain ease for investment maintenance, and alternate eases are to come in the form of more accessible research.

Specifically, it is certain that discourse of Crypto is not done in Financial Papers like the WSJ and ET, and is instead done through Social Media, a grasp of which can be a time consuming task. Accordingly, we seek to generate a heat-map/bubble-map of Cryptocurrencies corresponding to social media traffic (Twitter and Facebook, API access permitting) and a sentiment analysis of social media posts corresponding to Cryptocurrencies in the user’s portfolio so that the user may become aware of where it is the larger market declares itself to be proceeding and respond accordingly.

Furthermore, we would also wish to aggregate news on Cryptocurrencies relevant to the user’s portfolio so that he is saved the effort of having to research for himself, though it remains to be seen if as much is technically feasible.

Lastly, we would seek to add the feature of Price Prediction for a short period of time into the future based on Technical Indicators, employing some relevant model of Machine Learning.

## For whom?

This web application is primarily aimed towards someone who wants to enter the investment world. However it is not restricted to newbies, rather, it can be used by any person new or experienced to do real world analysis before investing their money. There would be a wide array of stocks and crypto available on the app so, people from all trading backgrounds will find it useful (if not life changing given the right rocket to the moon),.

## How?

Features to complete:
* An authentication system that allows user to log in using their:
  * Facebook
  *  Twitter
  *  Email and password
* Allow user to add Stock and Crypto to their Wallet (along with other details such as: buying price, volume, date of purchase etc.) and display their cumulative profit/loss thus far through Graphs (line-charts, and candlestick graphs)
* NFA, (NOT-FINANCIAL-ADVICE) will be our unique selling point. This feature will allow users to get a short term price prediction based on technical indicators through a Machine Learning model. 
* Display WordCloud of frequently appearing hashtags along with the crypto/stock on the user’s wallet (Twitter API)
* An interactive Heat-Map/Bubble-Map to show stocks and cryptocurrencies that are currently trending on Social Media.
* A Sentiment Analysis system that would allow users to get a general overview of the sentiments surrounding the investments in their portfolio - this can be done using a sentiment analysis implementation with Twitter and/or Facebook APIs to get real time data input.

### Future Prospects
* Will also allow user to have a fake in-app currency which can be used for Paper Trading.
* A News Aggrerator is also under consideration which would allow the user to see smartly picked news on the user dashboard relevant to the user’s wallet.

## Scope

This proposal will require a full on implementation of a web app including a User login system, a backend that would store the user’s portfolio details. Furthermore, the sentiment analysis system will also be using multiple APIs to gather and analyse data for the user at the backend. Similarly, the price prediction system will also be handled using a highly efficient Machine Learning model. The user portfolio will be graphed in real time (subject to constraints in API usage).

##### Worked on by *Hanzalla (hu297), Sashank (ss13163), Umair (sus221), Abdullah (ajc957)*
