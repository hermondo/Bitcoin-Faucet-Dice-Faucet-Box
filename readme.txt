FaucetDice
----------
FaucetDice is a bitcoin faucet script that is also a fully functional dice game. The user can cashout using faucetbox. 
Includes a faucet referral system built-in and reCaptcha for anti-bot. Just need to update the API keys in the 
two index.php files. 

This script uses PHP, faucetbox API, and reCaptcha for anti-bot protection. 

You will need to sign up with FaucetBox and Google's reCaptcha to obtain API Keys. 

1. Download the files in the repository
2. Set up a database on your webserver
3. Open up the index.php file in BOTH directories (facuetbox and faucetboxgame). 
   * Define your database login info one the first line of these two php files.
   ** Also insert your API Keys from Faucetbox and Google reCaptcha below under the custom parameters section
   *** This is where you can also set claim amounts, referral amounts and time between claims.
4. Import the SQL database file into your database using PHPmyAdmin or similar database manager.
5. The landing page for visitors should be index.php within the faucetbox directory
  


If you have found this script useful please consider buying me a pint ;)
BTC: 15SzRoBgemEN8EoQ7Qvx6bMZz6rkYzrfUw

