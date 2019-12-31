---
layout: page
title: P R O J E C T S
permalink: /projects/
---
I like to noodle around with code. Here's a few things that have made into the public eye, and a few that can't, at least not yet.

[Act Human](https://github.com/yellingviv/act_human) - A Twilio-based li'l computer friend to help me remember to act like a human being during the workday (drink water, fix my posture, unclench my jaw, go to lunch, go home, etc) because I'm terrible without reminders. It selects random reminders from a selection of messages that focuses on the things I need to remember to do. It works! Except that I want to create a randomly generated schedule for sending those texts, so that I don't get used to a time-based reminder (I quickly learned to ignore Slackbot reminders). This part is proving elusive, but I'll get there.

[Chonkspiration](https://github.com/yellingviv/chonkspiration) - I love cats, you love cats, the internet loves cats! So I am creating a service that will provide on-demand cat images to match your mood (courtesy of the [RequestKittens API](https://joshwcomeau.github.io/RequestKittensDocs/public/)), paired with Markov text captions generated from a selection of nihilism quotes and texts that I'm scraping from GoodReads and a few other sources. Because cats are great, but nihilism and Markov bots are *hilarious*. This is a work in progress, just getting started during December 2019. Please hold for better cat content.

[Hackbright Labs](https://github.com/yellingviv/hackbright-labs) - The labs and homework assignments from my studies at Hackbright.

Vuln Valet - This is regrettably not currently available for public consumption, but we are hoping to open source this project when it's done. I am writing a tool that connects with the Tenable Nessus API to pull information from vulnerability scans (servers, vuln ID, CVE info, severity, etc) and then automatically generate Jira tickets to assign to the relevant teams. In addition, it will communicate via Slack with the engineering manager(s) for the relevant team(s) so that everyone is aware. It will post weekly status information in a dedicated Slack channel, and @-mention stakeholders when issues are time-sensitive. I am really looking forward to being able to open source this when I'm done, as I know a lot of people are looking for better ways to handle their Nessus reports!

VendorBot - This is not available for public consumption because the code is terrible. This was my first code project at work, and I "learned" Node.js to do it. It provides intake for new vendor security review requests, and tracks requests in our vendor records. We had a pretty terrible process previously, with an absurd number of steps required to kickoff a vendor security review, so this really streamlined things. That said, it's pretty janky and really just not fit to be allowed out in polite company. If I ever get around to cleaning it up and adding the additional functionality I'd like to add, maybe that will change, but please don't hold your breath.
