---
layout: page
title: Channel's FAQ
permalink: /developer-portal/channel-faq/
weight: 170
parent: Developer Portal
---

* TOC
{:toc}


## Slack

## Twitter
* When a user mentions a bot on Twitter for the first time, there is up to a 7 minute delay between the time of the mention and when the bot "sees" the request
* A bot will only respond to mentions when they are mentioned at the beginning of the message, as in:

		"@EchoBot Hello!", but not "Hello @EchoBot!"
* Twitter DM's will not show photos in line; but rather will render a link to the document

## SMS

* Bots chatting via SMS always reply directly to the sender of the message rather than replying to the group.  In turn, a bot will always see two users in the TotalParticipants field when using SMS
	
* Rate limit: 1 msg/s (long number) vs. 30 msg/s (short code) <a href="https://www.twilio.com/help/faq/twilio-basics/how-many-calls-and-sms-messages-per-second-can-my-twilio-account-make" target="_blank">Twilio docs</a>
* Carrier’s spam filtering/blocking logic <a href="https://www.twilio.com/help/faq/sms/how-can-i-prevent-my-messages-from-being-filtered-as-spam" target="_blank">Twilio docs</a>

## GroupMe

* Users: To remove bots from your group visit:  [](https://web.groupme.com/profile/access_tokens)
* If list of groups is from different group during user setup, open an incognito window or clear your "oauth.groupme.com" cookie
	
## Telegram

* Bots on Telegram only receive messages if they are mentioned (due to Telegram behaviour)

## Email


## Skype