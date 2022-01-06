# Spotify-Track-Tour

You can check out the **web app** here: https://rohhenry.github.io/spotify-web/

Or the **demo** here: tba


## Source Code:
This repo is where I put my links

The **frontend code** can be found here: https://github.com/rohhenry/spotify-web

The **backend code** can be found here: https://github.com/rohhenry/Spotify-Track-Tour-Server


## About:

**Traditional recommendation algorithms _rely heavily on collaborative filtering_** 

(spotify uses a hybrid approach but still depends on filtering heavily), 

**Although this is safe, it is not good for _expanding your taste_ or _exploration_.**

Collaborative filter approaches also struggle with cold starts (new users and new tracks).

I put together this recommendation algorithm to tackle this. 

It is made using:

- **polynomial feature transformation of spotify's provided features**
- **ridge regression for labeling prediction**
- **thompson / epsilon-greedy sampling for prediction choice**

The best part is the models individual weights are displayed and the hyperparemeters are tunable (customization not developed yet at this time).

You will need a spotify premium account to use.

For better performance clone this repo and run this app locally, you will need the relevant api keys though.

## Tech Used:

Frontend: javascript, react, material-ui,

Backend: python, flask, heroku

Database: google firestore

Other Tools: spotify api, sklearn, numpy, pandas

## Languages Used:

javascript / python

## Todo List

- hyperparameter tuning
