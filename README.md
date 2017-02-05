
# queb

queb (Queen's University Event Bot) is a Facebook Messenger chat bot allowing users to learn about local events in their area. It is aimed at Queen's students and residents of Kingston, but anyone can converse with the bot to learn about events in their area.

Built by Stephen ([@BearGuy](github.com/bearguy)) and Simon ([@skhzhang](github.com/skhzhang) at QHacks 2017 ([qhacks.io](qhacks.io)) at Queen's University within a timespan of 36 hours. It was the first time we ever worked with chat bots or Natural Language Processing, and was an amazing way to learn.

Users directly interact with queb using Facebook Messenger ([https://developers.facebook.com/docs/messenger-platform/](https://developers.facebook.com/docs/messenger-platform/)), which connects with [wit.ai](wit.ai) handling the Natural Language Understanding and Processing work.

We use Facebook's Graph API and (@tobilg)[github.com/tobilg]'s API at https://github.com/tobilg/facebook-events-by-location to get data about events. Everything was put together using Node and Express, and was built using Gomix [gomix.com](gomix.com).

The bot's Facebook page is at https://www.facebook.com/queb17/, but you might need to ask for rights before you can talk to it.
