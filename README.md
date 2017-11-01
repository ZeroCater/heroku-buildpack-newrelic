# heroku-buildpack-newrelic
Buildpack to send deploy notifications to New Relic

## Requirements

This buildpack requires the `requests` library. Please add it to the `requirements.txt` file of your project.

You should also add the following two variables to Heroku env variables:

- `NEW_RELIC_APP_ID`: You can find this in the url of the app on newrelic's website.
- `NEW_RELIC_API_KEY`: This is account wide, you can find it in newrelic's account settings.
