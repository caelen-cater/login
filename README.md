# Login
Easy prebuilt login system using Cirrus API

## Setup
Get an API key for Cirrus API, learn how to get one [here](https://api.cirrus.center/docs/hc/articles/3/14/11/api-keys)
Now that you have your API key, put it in /auth/index.php and replace "API_KEY" with your actual API key

## Settings
You can change where the form will redirect to after a successful login. You can change the location in /auth/callback/index.php

## Cookies
The login form will store the token in a cookie called 'auth', I reccomend you add a cookie popup on your main site to comply with GDPR
