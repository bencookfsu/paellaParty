# paellaParty
Monitors a twitter id for a specified keyword, sends user a twilio SMS message if/when a match is found.

_Originally created to monitor a local pub's twitter in order to catch a deliciously elusive paella food truck. It works._

<strong>Summary</strong><br />
* Enter a twitter id<br />
* Enter a keyword<br />
* paellaParty will check the twitter feed for the specified keyword every 5 minutes and will send a twilio SMS message upon each match

<strong>Notes</strong><br />
* oldtweets.txt contains a list of tweet ids for previously matched tweets<br />
* all twitter/twilio api keys should be stored in a separate keys.py
