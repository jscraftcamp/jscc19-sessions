# Secret Santa
_Session facilitated by Philip Saa ([@cowglow](https://twitter.com/cowglow))__

The goal of the session was t refactor the loops in my[SecretSanta])(http://github.com/cowglow/SecretSanta) project.

The question was how I would sort a list of people in a [Secret Santa](https://en.wikipedia.org/wiki/Secret_Santa) game and ensure that siblings (i.e. people with the same last name) wouldn't be matched with one another. So Luke Skywalker wouldn't give a gift to his sister Lea Skywalker.

We spend our time extracting the loops into their own individual functions. And concerns arouse for code sniffer issues. But Willy, had an idea to simplify the whole thing. Only fall back was that we need to pop entries from the participant array as we're pairing them with their secret Santa candidate.

Changes are under a different branch of the repo. And you're welcome to fork it and create a pull request with your changes or suggestions.