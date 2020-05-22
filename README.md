# New York Times Top 100 Articles a Week

Combines public New York Times RSS feeds into one feed, with the goal of
surfacing only the top items.

Aggregated feed: https://s3-us-west-2.amazonaws.com/rsscombine/new-york-times-rss-top-100.xml

## Guidelines

As pull requests are merged and this README is updated, the aggregated feed will automatically update.

## RSS Feeds

- http://rss.nytimes.com/services/xml/rss/nyt/MostViewed.xml
- http://rss.nytimes.com/services/xml/rss/nyt/MostShared.xml
- http://rss.nytimes.com/services/xml/rss/nyt/Upshot.xml
- http://www.nytimes.com/services/xml/rss/nyt/Magazine.xml
- http://www.nytimes.com/services/xml/rss/nyt/sunday-review.xml

## Technical Details

The code that does the aggregation is here: https://github.com/chase-seibert/rsscombine

There is a cache timeout of one hour on adding new feeds, and updating feeds.
