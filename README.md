# Add-to-home-screen
Add to Home Screen (install prompt), makes it easy for users to install the PWA on their mobile or desktop device. After the user accepts the prompt, your PWA will be added to their launcher, and it will run like any other installed app.


In this project I will be showing a custom button the user to click and add the website/ webapp to the user's home screen.
In order to show the Add to Home Screen dialog, you need to:  
1. Listen for the beforeinstallprompt event 
2. Notify the user your app can be installed with a button or other element that will generate a user gesture event. 
3. Show the prompt by calling prompt() on the saved beforeinstallprompt event.


We can also check if user open the PWA form home screen icon by media query
@media all and (display-mode: standalone) {
/*custom style if the pwa is open form home screen icon*/
button {background: #ddd;}
}



:: I had succesfully compiled the project after lots of struggle and scratching tons of website but none of them taught me to achive the Install prompt on custom button click. Everyone tells how default mini info bar could be display no one teaches to show the prompt on cuttom button click.
