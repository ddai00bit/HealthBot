# HealthBot

## Milestones
- Bot detects if a person is sick (ex. User: "I'm not feeling well today. Will WFH.")
  - Define series of words that detects sickness
  - Have Slack bot scrape channels for sick words
- Bot provides suggestions for improving their health (ex. Bot: "I heard you're not feeling great today. :( Let's visit your nearest (7m) CVS Minute Clinic in Arlington to have them check your symptoms today. The current wait time is N minutes. {url to nearest minute clinic}")
  - Detect persons location
  - Find closest CVS Minute Clinic to person
  - Check on current wait time at Minute Clinic
  - Respond to person in a DM
- Bot executes tasks for person (ex. Bot "Would you like to schedule an appointment?" )
- Population health analytics (ex. time from first sick mention to other people becoming sick)

## Deploying
Uses Heroku but is leveraging the Automatic Deploy from Github feature. Any commits to the Master branch will automatically go live.

## Setup
- Bot is currently enabled for the #test channel in Slack.
- Bot name, description, and icon is editable within Slack's bot settings.
