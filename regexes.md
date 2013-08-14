repeating links over + over
-------------
- (?i)(in.*case|if).*you.*missed.*it


wealth fetish
-----------------------------------
- (\s|#)(billionaire|Billionaire|billionaires|Billionaires)
- (\s|#)(billions|Billions)
- (\s|#)(richest|Richest|RICHEST)

concepts
-----------------------------------
- (\s|#)(fail|Fail|FAIL)
- (\s|#)(firstworldproblems|Firstworldproblems|FIRSTWORLDPROBLEMS)
- (\s|#)(sorrynotsorry|Sorrynotsorry|SORRYNOTSORRY)

shopping, shipping, consumption
-----------------------------------
- (\s|#)(ups|Ups|UPS)
- (\s|#)(fedex|fedex|FEDEX)
- (\s|#)(foursquare|Foursquare|FOURSQUARE)

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

Filtered domains
-------------

- techcrunch
- mashable
- paper.li
- foursquare
- huffingtonpost
- businessinsider
- forbes

Filtered clients
---------------
- ifttt
- buffer

