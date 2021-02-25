## Your-tour telegram bot 🚍🌍

### What is Your-tour bot❓

We will create a little helper for our clients - a telegram bot.

Why is Telegram? Most of the people who choose the bus tour are young people. This is more difficult for elders to endure long journeys in a seated position, very fast pace of excursions, night walks and lack of sleep. But young people put it off with a bang, they will not even notice how the 8 hours of the bus ride fly by.
 
When you buy a bus tour the most often doubts arise due to the fact that it is not known in which hotel you will stay for the night or how friendly the guide will come across. We've fixed that. Now you are the one who decides everything! After registering for the tour, about a week before the start, the bot will send you a quiz: in which hotel you would like to stay (the quiz is anonymous, of course), and which guide you would like to see. This way you can read hotel reviews, see photos and make a decision. The same situation is with the guide.
           
After the start of the tour, the assistant will always be with you, tell you the schedule of the day, at what place and at what time the general meeting, remind you of it with an alert, and give you weather data. Whatever you are late, the telegram bot will send you notifications 1 hour, 30 minutes and 15 minutes before the scheduled meeting time. With him you will always be in the know and save yourself from unnecessary worries.
            
During the tour, many varied and informative excursions await you, but what if you don't know which one to choose? The bot is happy to help you. It will provide you with a very detailed description of the excursion. 
            
Our bot will always be with you, so less worry and more vivid impressions 😉

### Available commands ✔

▶   /start <br>
		 Greetings, request to enter a name -> checking the presence of a name in the database -> if the person is in the database, then the definition of the purchased tour,            otherwise the bot will recommend contacting the travel agency office and stop its work. <br>
▶  	/help <br>
		 Output of all commands with their description.<br>
▶		/stop <br>
		 Stop the bot.<br>
▶		/meeting <br>
     The bot will display the time, the meeting place, which will be marked on the google map.<br>
▶		/excursions <br>
		 The bot will display a list of excursions, when you click on the name, it will display the text accompanying the excursion.<br>
▶		/time <br>
		 The bot will ask you to enter the city for which you want to know the time and then display the information.<br>
▶		/weather <br>
     The bot will ask you to enter the city for which you want to know the weather (for today and tomorrow) and then display the information.<br>

▶		/admin <br>
     Login as administrator, the bot asks for a password, if entered correctly the bot displays a list of possible actions:<br>
    🔹 Send message: the bot asks what you want to send (for example, a vote), the name of the tour and the date to determine which users to send it to.<br>
    🔹 Set meeting time: the bot asks for the time, day of the tour, name and date of its start.<br>
    🔹 Set meeting place: the bot asks for the place, day of the tour, name and start date.<br>

### How it works❓

The bot will have access to the company's customer database, but will not be able to make changes to it. Thus, he will be able to recognize users, whether they have tours and what they are. With each new request to the database, the bot will have its latest version (with all updates).

Tours will be pulled from the site. Source: https://foxiepass.com/ru.

2 weeks before the start of the tour, the bot will re-pull data from the site, in case changes have been made to the site. The user will be shown excursions in the cities that are on the tour, and by the date of his arrival in the city
