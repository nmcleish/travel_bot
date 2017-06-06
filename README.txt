TravelBot

Travel Bot can tell you the weather forecast for your trip.

To run:
Import the Watson Conversation workspace from conversation/workspace.json into your Watson Conversation Service.

Directions:
1. cd into the python directory
2. Rename .env.template to .env
3. Add your Watson Conversation credentials to .env
4. Add your Cloudant Database Username, Password, and URL to .env
5. Add your Weather api credentials to .env
6. Optionally, add your Slackbot token to .env
7. Install dependencies by running pip install -r requirements.txt
8. Run python app.py
9. Go to http://localhost:8080

*To clear your context, tell the bot no.



