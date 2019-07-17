# Add-to-home-screen
Add to Home Screen, sometimes referred to as the web app install prompt, makes it easy for users to install your Progressive Web App on their mobile or desktop device. After the user accepts the prompt, your PWA will be added to their launcher, and it will run like any other installed app. In order to show the Add to Home Screen dialog, you need to:  Listen for the beforeinstallprompt event Notify the user your app can be installed with a button or other element that will generate a user gesture event. Show the prompt by calling prompt() on the saved beforeinstallprompt event.
