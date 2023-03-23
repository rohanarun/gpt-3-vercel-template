
Check this youtube video for the full tutorial and demo: https://www.youtube.com/watch?v=NGlfGRpkd0Q

## Get Started

1) Click use this template, and create a repository.
2) Setup a new project in vercel, and import this repo.
3) Set up environment variables by copying the variables below and editing them.
4) Deploy your application and give Vercel a moment to complete the deployment process.
5) Visit your web app in your web browser, and share it to your friends. 🥳
6) Paste in new custom widgets in the public directory as .html files.
6) Use Project Atlas to generate new custom UI designs, and paste them into the public directory for instant deploys.🥳

## Setting up Environment Variables

You can customize your application by using environment variables. Here are all available variables and the usages:

```env
# Client side

# The app logo url.
APP_LOGO=""
# The name of the app.
APP_NAME=""
# Summary your app's behavoir and show the users how to use it.
APP_SUMMARY=""
# Example input that shows user how to use the app.
EXAMPLE_INPUT=""

# Server side

# Required, the API key got from OpenAI (https://platform.openai.com/account/api-keys)
OPENAI_API_KEY=""
# Optional, the agent server of OpenAI API. Use this when the offical OpenAI API server is unreachable.
OPENAI_API_BASE_URL=""
# Optional, the system message helps set the behavior of the assistant. (Learn more from https://platform.openai.com/docs/guides/chat/introduction)
SYSTEM_MESSAGE=""
# Optional, the message template to wrap the user inputs, the `{{input}}` string in the template will be replaced by user inputs.
MESSAGE_TEMPLATE=""
```

You can edit the example file located in the root directory of this project named `.env.example`. Once you have made the necessary changes, you can then copy and paste the entire content of the file into the "Environment Variables" input field on the Vercel console.


### Generating custom widgets
1) Use this phrase with Project Atlas in Cheat Layer to generate custom front end UIs: 

```
generate a website with a professional looking form that contains 1 input. It submits an object {input: value} to /api/request. The result is available in the data variable as a text string. Print the result in a div. Do not use sendAjax and use fetch. Make it look fancy.

```
2) Create a new .html file in the /public directory, like test.html. Open the HTML file Cheat Layer downloads and copy/paste the HTML from that. 
3) Click commit changes, and wait on vercel dashboard for the auto-deploy to test the new version!


### Embedd the wiget
1) Take the URL of the widget, and put it inside this code:
```
<iframe src="WIDGET_URL" width="100%"></iframe>
```
