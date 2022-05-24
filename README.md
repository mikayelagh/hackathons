# hackathons
Contains skeleton projects for hackathons.


Welcome! We’re excited to welcome you and your team to this year’s Virtual Confluent Hackathon from May 23, 2022 - June 23, 2022

To confirm your participation in this year’s event, please complete the registration form. We’ll follow up with relevant hackathon updates and submission details. In the meantime, read more about the Hackathon below!

HACKATHON INFO
Submission Deadline: Participants must submit their projects by 11:59 PM PDT on June 23, 2022.

We Promise! All the code you create during this hackathon is yours, and we will take no ownership of it. You are encouraged to do whatever you want with your project after this event.

Office Hours: June 7th, 2022, 9:00 AM - 12:00 PM (PDT) and 3:00 PM - 6:00 PM (PDT)

The Challenge: The goal of this challenge is to create an event streaming application with Confluent Cloud, Apache Kafka® and other relevant technologies. The one real rule we have: Build something that interests you!

Prizes will be given out for projects that are deemed the most useful, innovative, and/or interesting for the judges.

Where Do You Start? You can start from scratch with the minimal restrictions we are giving you, or you can work with our specially made end-to-end streaming application created by Confluent’s Developer Relations team, detailed below.

We want you to build something that you find interesting, useful, or cool. But sometimes an empty directory is an overwhelmingly blank canvas. So to get you started, our Developer Relations team will provide you with a complete end-to-end event streaming application. You can use it as a scaffold to add to, a set of components to steal from, a crib sheet, or you can ignore it entirely and do your own thing!

Our starter project streams sensor data from a Raspberry Pi collector into Kafka (running on Confluent Cloud). From there, we do some simple processing with ksqlDB and then stream the data back out to a WebSocket server running in Python, and on a React/JavaScript dashboard. A full Collect-Process-Display pipeline that runs in real-time.

Download the starter project on GitHub
There are hundreds of directions you could take it in, but here are some ideas to get you thinking:

Change the domain - We’re collecting data from a Raspberry Pi’s sensors - maybe you’re more interested in financial data, or the Twitch API or system stats from /proc? Rewrite our starter project to gather something you find interesting. This could end up being the new dashboard you need at work or the hub of your smart home?
Rewrite, rewrite, rewrite - Are you trying to improve your Java skills? Planning to pick up Rust? Have you been meaning to dive into TypeScript? Take our working system and rewrite a piece in the language that interests you most. Then improve on it. Integrating with a working system is a great way to sharpen your coding skills.
Slice & dice the data - We’re processing a single stream of events for a single result. You can add more streams of data. Slice them in different ways. Join them together. Stream out multiple different events and display them concurrently on a dashboard that shows everything and the kitchen sink. And then maybe make the dashboard interactive?
Complete the loop - Raspberry Pi streams sensor data out to a React dashboard. But what instructions could the dashboard stream back to the Pi? Playing an alert sound? Triggering a servo that waters a plant? Driving motors to move the sensor around the house?
How Do You Win? Well, technically speaking, to win, you have to learn something, as everyone who learns something is the real winner…

But our judges will review project submissions with these criteria in mind:

Innovation: Are you using a data source we’d never have thought of, or using data in a novel way? Or perhaps you’ve integrated a new tool or process that surprises us?
Coding Skills: Have you rewritten parts of the application in $EXCITINGNEWLANGUAGE? Or just done a really elegant job with something mainstream? Perhaps you’ve written a complete app in bash, just to see if you can? These are just some examples of how you can display your coding abilities.
Usability: Is it useful? Have you built something non-technical people could use? Will you use it once the hackathon is over?
Feasibility: Could this be the start of a brand new business?
Prizes: Knowledge, fun, the respect of your peers, but also real $$$$: Each member of a winning team will receive an Amazon gift card and Confluent Cloud credit. We’ll announce and reach out to winners on June 30, 2022.

Terms & Conditions: By participating in 2022, you agree to abide by the following code of conduct. Please click here to review - https://www.confluent.io/community-code-of-conduct/. Teams can be disqualified from the competition at the organizers' discretion. Reasons might include but are not limited to breaking the competition rules, breaking the Code of Conduct, or other unsporting behavior. Amazon gift cards may not be eligible in all countries. Please contact the Confluent Community team about gift card verification.
