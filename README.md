# Podcast Categories

[Apple Podcasts categories](https://podcasters.apple.com/support/1691-apple-podcasts-categories) in JSON and YAML. Makes it easy to build a podcast category selector.

## Download

[👉 Download json](podcast-categories.json)

[👉 Download yaml](podcast-categories.yaml)

## Where to use these categories?

The <itunes:category> tag in a podcast rss feed. From Apple's [A Podcaster’s Guide to RSS](https://help.apple.com/itc/podcasts_connect/#/itcb54353390):

```
The show category information. For a complete list of categories and subcategories, see Apple Podcast categories.

Select the category that best reflects the content of your show. If available, you can also define a subcategory.

Although you can specify more than one category and subcategory in your RSS feed, Apple Podcasts only recognizes the first category and subcategory.

When specifying categories and subcategories, be sure to properly escape ampersands. For example:

Single category:

  <itunes:category text="History" />
Category with ampersand:

  <itunes:category text="Kids &amp; Family" />
Category with subcategory:

  <itunes:category text="Society &amp; Culture">
    <itunes:category text="Documentary" />
  </itunes:category>
Multiple categories:

  <itunes:category text="Society &amp; Culture">
    <itunes:category text="Documentary" />
  </itunes:category>
  <itunes:category text="Health">
    <itunes:category text="Mental Health" />
  </itunes:category>
```

[👉 Example](https://www.listennotes.com/rss-viewer/?url=https%3A%2F%2Ffeeds.megaphone.fm%2Fmark-levin-podcast):

<img width="801" alt="Screenshot 2022-11-20 at 8 56 37 PM" src="https://user-images.githubusercontent.com/1719237/202968749-bb35c762-9d8d-4dda-8c7e-9d1f7e54fe8d.png">

## Where to find podcast rss feeds?


[![The best podcast search engine: Listen Notes](https://user-images.githubusercontent.com/1719237/202967279-f953e730-c299-4337-af47-2631c45575b1.png)](https://www.listennotes.com/)

btw - try [PodcastAPI.com](https://www.podcastapi.com/)
