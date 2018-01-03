# redis-simple-pubsub

This is just a repo with a python3 version of a simple pubsub exercise published here:
http://programeveryday.com/post/create-a-simple-chat-room-with-redis-pubsub/

The code is the same of the blog post, just adapted to works with python3

All credits for the code goes to: Dan Sacket of http://programeveryday.com


# Usage (as explained in the blog post):

- start a Redis server locally, and check the connection settings (at `settings.py`)
- create a new virtualenv and install dependencies
- start a shell instance and fire a subscribe script to consume messages: `python sub.py PYTHON`
- start one or more shell instance to trigger messages:  `python pub.py Dan PYTHON`
- Done!


# Help!

If you need help, please read the graat blog post... It's fully explained!
