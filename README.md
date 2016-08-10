# PythonTriviaApp
This is a small trivia app made with Python Flask. It relies on Redis to handle the backend.

Updated with Proper Bootstrap.

The links on the index page are static at the moment. Upon clicking after a fresh pull they will not work properly unless you title a question with their exact case matches. The question link route relies on the Title key from the redis database to funtion properly.

Example:
Title: Sports
Question: What is the oldest sport in history?
Answer: Wrestling

This is a work in progress.

Future Design:
A dynamic table for posted questions.
Score system for right and wrong answers.
