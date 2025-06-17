# EARLY WARNING SYSTEM

https://youtu.be/daR8V0rW5mE?si=sd8oxtxQZ5QexzDn
[![Watch the video](https://github.com/Mac16661/DisasterAwareness/blob/main/img.png?raw=true)](https://youtu.be/daR8V0rW5mE?si=sd8oxtxQZ5QexzDn)

It is a system that can ingest posts from Twitter in real time (simulating the Twitter Streaming API to listen for tweets and filter them based on criteria such as hashtags). Since there was no free tier available at the time, the data was collected offline from a third-party source. We classify the tweets as either disaster-related or not using a BERT model. If a tweet is classified as disaster-related, the system sends alerts to the appropriate authorities via email and forwards the information to the frontend using message queues (via Pusher). The frontend, built with React, then visualizes the event’s location on a map. The backend was developed using Flask and deployed using AWS services.
