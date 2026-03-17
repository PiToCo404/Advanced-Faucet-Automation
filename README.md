# Advanced-Faucet-Automation
BeeFaucet and ClaimFreeCoins faucet automation. Up to 38 faucets at once with proxy support 

# How to run:

Clone this repo
Install NodeJs from the official site

https://nodejs.org/en/download

Run setup.bat
Run start.bat
On first run choose 'y' to setup the base profile
Enable developer mode so ublock origin can work
Import the filter.txt on ublock origin "My Filters" page, apply changes
Open violentmonkey options, import the file scripts.zip, edit the BeeFaucet and ClaimFreeCoins userscript to insert your email in place of "CHANGE_ME" placeholder, the email must remain between double quotes. Then save the script
Click Rektcaptcha extension icon and enable auto open and auto solve
Close the browser window and press enter on the console to save changes

Run start.bat again, type n then enter, chopse how many faucets you wish to collect at once (default is 19)

# How it works

When running the script a chrome window will open every 30 seconds with a faucet and the claim will happen as long as you set your email correctly inside the userscript on violentmonkey

# Proxy mode

By default the script installs Foxyproxy extension on the base profile, if you want to run multiple instances of the program you can use static ISP residential proxies (http proxies works best)

Recommended proxy: https://proxy-cheap.com

# DISCLAIMER 

This program was made with educational purposes o only, use at your own will. I'm not responsible for misuse of this tool
