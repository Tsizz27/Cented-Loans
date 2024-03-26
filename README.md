Hi, thank you for buying Cented Loans!

If you need help contact me on discord: tsizzle27
Discord server: https://discord.gg/bz6XBWMNHZ


-> Installation Guide: 

1. Install the newest version of ox_lib dependency from releases tab (https://github.com/overextended/ox_lib/releases)
2. Make sure that ox_lib starts before LoanScript in your server.cfg
	- Make sure that you also have some sort of targeting resource: ox_target or qb-target work
3. Insert the sql file into your database
4. Configure your script, follow comments in config.lua to help you
5. Start and enjoy! Feel free to make any suggestions in our discord!

Notes:
-> If you have custom framework, notifications, TextUI, billing, or inventory, go to the sv_custom.lua file to add your code from those resources
-> The interest rate in the config should be limited to two decimal places | It will round up if the loan amount makes it a very long decimal
-> Make sure to research the blip display numbers and what they mean in the config. 
	- The wrong number could make the blip stick to the edges of the minimap
-> TextUI instead of target is coming soon!