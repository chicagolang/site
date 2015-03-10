# ChicaGoLang

This is a jekyll-based website for Chicago Go meetup - http://chicagolang.com

## Setup

Quick start:

```
gem install jekyll
git clone git@github.com:chicagolang/site.git
jekyll server
```

## Publish

Push to Github Pages:

```
git push origin gh-pages
```

## Event Structure

Event is a jekyll page. Page body is an event description while YAML meta 
hosts a bunch of necessary attributes:

```
---
layout: event
title: Event name/title goes here
author: Author Name
author_link: https://twitter.com/username
venue:
  name: DevMynd Studios
  address: 2035 W. Wabansia Ave
  instructions: 2nd Floor, enter the black door
  directions_link: https://www.google.com/maps/place/2035+W+Wabansia+Ave,+Chicago,+IL+60647/@41.9120576,-87.6789658,17z
event:
  date: April ##, 2015
  time: 6:30 PM
meetup_id: meetup id goes here
slides_url: github.com/chicagolang/MONTH-2015/path/to/slide
github_repo: https://github.com/chicagolang/MONTH-2015/path/to/examples
categories:
  - events
  - upcoming (if new)
  - past (if past)
---
Meetup topic / summary goes here.
```

## License

MIT