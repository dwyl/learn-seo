# learn-seo
:mag: Learn search engine optimisation :sparkles:

## Why should I care about Search Engine Optimisation?
If a tree falls in the woods and no one is there to
hear it, does it make a sound? If a website isn't
on the first page of a google search, does how good
it is even matter? :thinking:

The majority of traffic for sites still comes from organic searches (this means
people searching using normal search queries).

There is an increase in traffic coming from social
media and people sharing things, but the majority
is still coming from search engines. So you want to
make sure your site shows
up for the relevant queries, so that it gets optimum
traffic, and all of the benefits that come with it.

 You can make the best website in the world, but if _no one_ can find it, then it doesn't matter!

And being high up in searches matters! A study indicated that the first result
from a google search recieves 32.5% of clicks, where the second receives only
17.6%, that's almost half the traffic, due to only being one position lower!
[source](https://searchenginewatch.com/sew/study/2276184/no-1-position-in-google-gets-33-of-search-traffic-study)

## What is SEO?

Search engine optimisation is an effort to increase the traffic to a website by
trying to make sure it appears as high in the search results as possible for
searches related to certain queries.

Before looking into SEO too much it is useful to have a little understanding
of the way searches on the web work, for which we really recommend [this short
video on how google searches work](https://www.youtube.com/watch?v=BNHR6IQJGZs).
[
![screen shot of a youtube video with the title "How Search Works by Matt Cutts"](https://user-images.githubusercontent.com/21139983/30594806-4808aa00-9d47-11e7-8267-fd8bad7304ad.png)
](https://www.youtube.com/watch?v=BNHR6IQJGZs).

By understanding the way that searches work, we can try to make sure that our
website has as high of a chance as possible to be a high result in searches
relevant to our topic. It's still important to remember to keep
[User Experience](https://en.wikipedia.org/wiki/User_experience_design)
at the heart of all of our decisions, and make sure we are not
compromising UX for the sake of SEO just as google themselves advocate:

> Search engine optimization is about putting your site's best foot
forward when it comes to visibility in search engines, but your
ultimate consumers are your users, not search engines.

>_[From google's own guide to SEO](https://static.googleusercontent.com/media/www.google.com/en//webmasters/docs/search-engine-optimization-starter-guide.pdf)_

## How do I do it?

A lot of SEO is making a clear site with good quality content that users will
engage with, but
there are some basic tips that can help to make sure that search engines show your site in relevant searches.

### Titles
`<title>Learn Search Engine Optimisation (SEO) - dwyl</title>`

First and foremost your titles should be useful and readable, not just a
collection of keywords. They should also be unique for each page (this helps
with search engines knowing that it's a different page).

The title tag should be contained within the `<head>` tag of the HTML
document, it is what will be displayed in the tab on your browser when the
page is open, and what the title of the entry in the search results will be.

Search engines generally only display the first **65-75** characters of the
`<title>` so it's best to make sure your title is within that limit. If you
_really_ need to have it longer to get an accurate title it may be
worthwhile, but at least make sure the first 65-75 characters give a good
idea of the page, so when the user sees the search result they get the idea
of what the page is. Depending on what you are trying to rank for,
it sometimes makes sense to place your brand at the beginning.

For best SEO, keywords should go close to the front, for example "Web
development agency" as opposed to "Fun creative agency specialising in web development".

### URLs
URLs play an important role in both user experience and search engine optimisation.
Luckily search engines are engineered to like the same types of url as humans,
so if you concentrate on keeping urls short and descriptive, it should translate
into great SEO.

#### Guidelines for a great URL
**Be descriptive:** If you can't easily tell the purpose of a page from the
URL, you're probably doing something wrong.

**Use human-readable urls:** Try to keep numbers, weird symbols and nonsensical
text to a minimum. Again, if the url isn't easy to interpret, _something is
wrong_.  

**Use keywords, but don't overuse them:** If you're targeting a specific set of
keywords, including them in the url can help to improve search rankings. On the
flipside, if the url is _just_ a series of keywords with no relation to page
content, then search engines will sometimes tag the site as spam and ranking
will take a hit.

**Keep it short:** Shorter URLs mean nicer links for emailing and inclusion on
other sites. They also allow the whole url to be displayed with search results.

**Use hyphens to separate words:** Underscores and other separators can be
intepreted incorrectly by search engines. Hyphens (-) are the standard.

**Each page should have one URL:** Repeating content with different URLs will
lead the search engine to consider them as two competing pages rather than
categorizing them as the same page, linked to multiple times. If you want to
have a different link for some reason you can use a 301 status code and redirect
the user to the already existing page, or you can put a `<link>` tag with
`rel="canonical"` in the head of the duplicate page. This will lead the search
engine to treat the page as a copy of the linked page. Like so:

`<link rel="canonical" href="https://dwyl.com/super-awesome-page"/>`

### Images
Search engine crawlers can't _see_ images unless they come with alt (alternative)
text :eyes:

Although it _can_ sometimes be useful for SEO to include keywords in the alt
text of images, as with urls this should **only** be done if the words fit with
the image. **First and foremost alt text should be a description of the image**:

```
This:
<img src="/happy-squirrel.jpg" alt="A joyous squirrel eating an acorn." />
```
```
Not this:
<img src="/happy-squirrel.jpg" alt="Super cheap acorns sold here! Buy ten get one free" />
```

### What not to do

We've given a bit of advise of thing you _should_ be doing in order to increase
your site's traffic from search engines, but there are also a few things you
should _avoid_ doing.

+ **Don't** bury text inside rich media. If you put your search engine relevant
content inside of things like flash and javascript the search engine robots
won't see them.
+ **Make sure** you're using the appropriate spelling for your target audience.
If you are mostly looking to be found in the UK, spell "colour" with a `u`, if
you're aiming for USA then leave the `u` out.
+ **Don't** use search forms as the main form of navigation. Search engine
robots don't fill out forms, so if you want the robots to see it, you need to
have a proper link to it! Make sure the search feature is supplementary rather
than the only form of navigation.
+ **Don't** hide content behind a login. Again, search engine robots don't go
through forms, so if all of your search relevant content is hidden behind a log
in, then it will never get crawled!
+ **Don't** use unclear link text. The body of your links should be clear and
semantic. `click here` is unhelpful to users, and unclear to search engines. A
clear, semantic link such as: `this video about Search Engines on youtube` is
much better for UX, accessibility and SEO.

## Further reading

**Beginner's guide to SEO - Moz:**
https://moz.com/beginners-guide-to-seo

**Steps to a Google-friendly site - Google:** https://support.google.com/webmasters/answer/40349?hl=en

**Google SEO starter guide - Google:** https://static.googleusercontent.com/media/www.google.com/en//webmasters/docs/search-engine-optimization-starter-guide.pdf

## SEO tools

**Google keyword planner:** http://adwords.google.com/keywordplanner

**Google trends:** https://trends.google.com/trends/

**Moz keyword explorer:** https://moz.com/explorer
