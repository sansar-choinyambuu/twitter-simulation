
twitter-simulation
=======

[twitter-simulation](https://github.com/sansar-choinyambuu/twitter-simulation) (is provided AS IS), is a one page html that simulates home screen of twitter

# Usage

1. Home account can be configured using config.json
* Profile name, @handle, profile picture, bio, banner picture, following and followers count
* Trends
* Who to follow

2. Tweets can be added in tweets.json
* Last added, first shown
* Twitter account's name, @handle should be configured
* Twitter profile picture can be configured
* Actual tweet text should be configured, html is supported. Quotes need to be escaped in for html.
* Optional - Reply, retweet and love counts [default random 0-100]
* Optional - Delay in seconds [default 0]

3. A click on "Tweet" button refreshes the tweets and plays tweet sound

# Requirement
Same origin policy in your browser must be disabled, for twitter-simulation to run smoothly.
- Chrome -> 'chromium-browser --disable-web-security --user-data-dir="[some directory here]"'
- FireFox -> about:config - 'security.fileuri.strict_origin_policy = false'
- Internet Explorer -> tools - Internet Options - Security - 'Internet' security zone - Custom level - Miscellaneous - enable "Access data sources across domain"  

# References
Some pretty cool references/credits to people I got inspired by with their project: 

- [twitter layout](https://codepen.io/Gi_18/pen/xwVJKg) from Giada Cantarutti

# Contact/Contributing

You can reach me on Twitter [@SansarTweets](https://twitter.com/SansarTweets).
Feel free if you want to contribute, clone, fork, submit your PR and so on.

# License

twitter-simulation is licensed under a [MIT License](https://opensource.org/licenses/MIT).
