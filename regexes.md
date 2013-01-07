People repeating links over + over
-------------
- (?i)(in.*case|if).*you.*missed.*it

Conferences/events
-----------------------------------
- (\s|#)(ces|Ces|CES)
- (\s|#)(sxsw|Sxsw|SXSW)
- (\s|#)(crunchies|Crunchies|CRUNCHIES)

Tweets mentioning four or more other people
-------------
- @[^@]+@[^@]+@[^@]+@

Giant hashtag punchlines
-------------
- #[^ ]{15}

Four or more hashtags in single tweet
-------------
- #[^#]+#[^#]+#

Tweets to you containing only a link (almost always spammer doing "wait and reply" bomb)
--------------
- ^@bluechoochoo *https?://[^ ]+$

Tweets containing over-repeated characters
-------------
- ([a-z])/1{4}

Retweet cascades
-------------
- RT[^RT]+RT
