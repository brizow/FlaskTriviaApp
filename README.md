# PythonTriviaApp
This is a small trivia app made with Python Flask. It relies on Redis to handle the backend.

Updated with Proper Bootstrap.

The links on the index page are static at the moment. Upon clicking after a fresh pull they will not work properly unless you title a question with their exact case matches. The question link route relies on the Title key from the redis database to funtion properly.

This is a work in progress.

###Example:
- Title: Sports
- Question: What is the oldest sport in history?
- Answer: Wrestling

###Future Design:
- A dynamic table for posted questions. 
- Current back end relies on Redis. As far as I have been able to make out you can only query direct keypairs.
- Score system for right and wrong answers.
