# Python-Twilio-automated-text-messaging
Project - Good Morning Text Message Sender
Description - You can send free automated text message of an inspirational quote to your cell phone everyday at 6:00 am. Here is the Python code to do that using Twilio and Replit.
Step 1 - Create a Twilio account. At the bottom page, there’s the Account SID, Auth Token, and Twilio number in Replit. Twilio is free. Even though it says it’s $12, it’s only if it’s upgraded.
Step 2 - Create an account on Replit and create a new project in Python.
Step 3 - Go to the Shell tab, enter pip install twilio. And also enter pip install schedule.
Step 4 - Set up the database. Import db from replit.
Step 5 -  Import and set up everything you need. Client, time, schedule and random.
Step 6 - Create the variables to store information, such as the Twilio phone number, cell phone number, and the message you want to send to your cell phone. Note that you need to get your Twilio phone number from your Twilio account. For your cell phone put +1 first to call in Canada. The example Twilio account, token, Twilio and cell number contain fake numbers and characters for security purposes.
Step 7 - From the Twilio webpage, access your Account SID and Authorization Token. Put account_sid and auth_token variables. Note that you’ll need to change the Account SID and Authorization Token to your own information. These are only examples.
Step 8 - Make all the variables stored into the database with the keyword db. It follows this format, db[“variable”]. Every time you use the variables, put db[“variable”]. In this example, line 7 db[“account_sid”] is stored in the database and since the variable is being used again at line 12, it would be db[“account_sid”].
Step 9 - Store quotes in a list. You can add as many quotes as you want! 
Step 10 - Create a new function called task. Print the body of the message, do this by printing msg.body. This will display the message in Python.
Step 11 - Schedule it to do task every day at 6:00 AM. Note that Replit goes by UTC time. 6:00 AM in Canada would be 10:00 UTC time.
Step 12 - Make a while statement that goes on while true. In the while statement, use the time you scheduled to tell it when to run until, to do this, write schedule.run_pending(). Add a 1 second delay to the time, to do this, write time.sleep(1).
Step 13 - Once you have completed coding, click the play button.
