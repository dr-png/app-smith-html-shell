# Instructions:

## AppSmith app URL:

1. Select appsmith workspace
1. Select your app
1. Press "Edit"
1. In the top right corner press "Share"
1. In the popup modal toggle "Make application public"
1. In the popup modal go to "Embed" tab
1. Copy "Embed URL"

## Add the URL to the HTML:

1. Just replace the `APP_SMITH_URL` [here](./index.html#L10)

## Update index HTML file on the server:

1. Take the [html file](./index.html) with the updated link
1. Replace the index.html file on your server
   - Located at `/www/wwwroot/YOUR_DOMAIN/index.html`

## Make sure the AppSmith app's latest version is deployed:
1. Select appsmith workspace
1. Select your app
1. Press "Edit"
2. Press "Deploy" in the top right corner
