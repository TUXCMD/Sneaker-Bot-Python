# Sneaker-Bot-Python

This bot is used to buy the latest sneakers of the german Nike website (https://www.nike.com/de/de_de/).

List of possible parameters:

<b>--username (required)</b>
* Username for login

<b>--password (required)</b>
* Password for login

<b>--url (required)</b>
* URL for desired shoe

<b>--shoe-size (required)</b>
* Shoe size (e.g. EU 40, EU 42)

<b>--login-time</b>
* If given, the bot will pause until a specific time before it logs in (can be any datetime format)

<b>--release-time</b>
* If given, the bot will pause until a specific time before it purchase the sneaker (can be any datetime format)

<b>--screenshot-path</b>
* If given, the bot will take a screenshot of the page after purchasing and save it at the given file path (may be useful for debugging)

<b>--html-path</b>
* If given, the bot will take the page source after purchasing and save it at the given file path (may be useful for debugging)

<b>--page-load-timeout</b>
* This is used to limit the page load time (in seconds), which can be useful when the page is still loading, but the UI is nevertheless useable (e.g. 4)

<b>--driver-type</b>
* Should be 'firefox' or 'chrome'

<b>--headless</b>
* This will run the driver in headless mode, which should make the bot quicker

<b>--select-payment</b>
* If you already have your payment options pre-saved on your Nike account, DO NOT use this. If for some reason you don't have it pre-saved (even though it will cost the bot more time) the bot will select the first payment option it finds.

<b>--purchase</b>
* If this argument is given, the bot WILL attempt to purchase the shoe so USE WITH CAUTION!

<b>--num-retries</b>
* If the bot fails for some reason, it will retry any number of times or until successful
    
 
