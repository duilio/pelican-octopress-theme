Octopress Theme for Pelican
===========================

This is a theme for `Pelican`_ that looks like `Octopress`_ default theme. I wrote this
theme for `my personal blog`_.

Why use this theme?
-------------------

I really like Octopress default theme, I think is enough pretty and very readable. On the other
hand I don't like any of the themes currently available for Pelican. As I'm not able to write a
nice theme from scratch I've just copied the Octopress' one.

Why didn't you use Octopress?
-----------------------------

I've started writing my blog with Octopress but I haven't found a way to easily have a
multi-language blog without hacking more than the time I was planning to spend to setup my blog.
You can argue that the time spent to copy the Octopress' theme is more than adding a
multi-language feature for Octopress.. I'm not sure of that since I've no idea what kind of
changes Octopress required to support multiple language per post.

I've found out that I like more the organization of Pelican: Octopress/Jekyll have a unique
repository you have to fork, so its code is mixed with your blog's data. Pelican instead separates
the two things. Also Pelican is written in Python that I know way better than Ruby.

The theme is missing `XXX`
--------------------------

I've started writing this theme just for my blog and my blog required few template pages and few
features. If you want to add `XXX` please be free to fork this repository and submit a pull request,
I'll be happy to merge it!

Plugins
-------

This theme add a nice section on the sidebar with a list of GitHub repositories of the user.
You can enable it by using these settings:

- ``GITHUB_USER``: (required to enable) your username
- ``GITHUB_REPO_COUNT``: ``5``
- ``GITHUB_SKIP_FORK``: ``False``
- ``GITHUB_SHOW_USER_LINK``: ``False``

This theme also allows sharing via Twitter, Google Plus, and Facebook.  To
enable any of these, use the following settings:

- ``TWITTER_USER``: (required to enable) your username
- ``GOOGLE_PLUS_ID``: (required to enable) your ID
- ``FACEBOOK_LIKE``: (required to enable) ``True``

Extra Twitter options (default values are shown):

- ``TWITTER_WIDGET_ID``: (required to enable feed) ID obtained from `twitter settings <https://twitter.com/settings/widgets>`_
- ``TWITTER_TWEET_BUTTON``: ``False`` show twitter tweet button
- ``TWITTER_FOLLOW_BUTTON``: ``False`` show twitter follow button
- ``TWITTER_TWEET_COUNT``: ``3`` number of latest tweets to show
- ``TWITTER_SHOW_REPLIES``: ``'false'`` whether to list replies among latest tweets
- ``TWITTER_SHOW_FOLLOWER_COUNT``: ``'true'`` show number of followers

Extra google plus options (default values are shown):

- ``GOOGLE_PLUS_ONE``: ``False`` show +1 button
- ``GOOGLE_PLUS_HIDDEN``: ``False`` hide the google plus sidebar link.

By default, comments are enabled for all articles and disabled for pages.
To enable comments for a page, add ``Comments: on`` in page meta.
To disable comments for an article, add ``Comments: off`` in article meta.

Google Analytics
-------------

- ``GOOGLE_ANALYTICS``: "UA-XXXX-YYYY" to activate Google Analytics(classic)
- ``GOOGLE_UNIVERSAL_ANALYTICS``: "UA-XXXX-Y" to activate Google Universal Analytics
- ``GOOGLE_UNIVERSAL_ANALYTICS_COOKIEDOMAIN``: ``'auto'`` optional cookie domain setting for Google Universal Analytics

Sidebar image
-------------

- ``SIDEBAR_IMAGE``: Adds specified image to sidebar. Example value: "images/author_photo.jpg"
- ``SIDEBAR_IMAGE_ALT``: Alternative text for sidebar image
- ``SIDEBAR_IMAGE_WIDTH``: Width of sidebar image

- ``SEARCH_BOX``: set to true to enable site search box
- ``SITESEARCH``: [default: 'http://google.com/search'] search engine to which
  search form should be pointed (optional)
  
QR Code generation
-------------

- ``QR_CODE``: set to true to enable the qr code generation for articles and pages by browser

FeedBurner integration
----------------------

- ``FEED_FEEDBURNER``: set this to the part of your FeedBurner URL after the ``http://feeds.feedburner.com/`` to set the
  displayed feed URL to your FeedBurner URL. This also disables generation of the RSS and ATOM tags, regardless of whether
  you've set the ``FEED_RSS`` or ``FEED_ATOM`` variables. This way, you can arbitrarily set your generated feed URL while
  presenting your FeedBurner URL to your users.

Neighbor Articles
-------------------

- ``SHOW_ARTICLE_NEIGHBORS``: set this to ``True`` to show "Previous Post" and "Next Post" bellow article content in the article pages.
  ``neighbors`` plugin is required for this feature.

Disqus
--------

- ``SHOW_DISQUS_COMMENT_COUNT``: set this to ``True`` to show disqus comments count in article meta paragraph.

Controlling Asides
-------------------

- ``ARTICLE_ASIDES``: a list of asides names, controls which asides and order to be displayed on articles.
  If not set, all available asides will be shown.
- ``PAGE_ASIDES``: just like above, but for pages.
- ``INDEX_ASIDES``: just like above, but for the index page.

Individual settings for article or page is available. Just add an ``asides`` in the corresponding article or page meta,
the value is a list of asides names, separated by commas.

Check ``templates/_includes/asides/`` to get the list of available asides, the asides name does not contain ``.html``.
Example setting: ``ARTICLE_ASIDES = ['recentpost', 'categories', 'tags', 'recentcomment', 'github']``.

Contribute
----------

#. Fork `the repository`_ on Github
#. Send a pull request


Authors
-------

- `Maurizio Sambati`_: Initial porting of the theme.
- `Geoffrey Lehée`_: GitHub plugin, some cleaning and some missing standard Pelican features (social plugins and links).
- `Ekin Ertaç`_: Open links in other window, add tags and categories.
- `Jake Vanderplas`_: Work on Twitter, Google plus, Facebook, and Disqus plugins.
- `Nicholas Terwoord`_: Additional fixes for Twitter, Google plus, and site search
- ... and many others. `Check the contributors`_. 


.. _`Pelican`: http://getpelican.com
.. _`Octopress`: http://octopress.org
.. _`my personal blog`: http://blogs.skicelab.com/maurizio/
.. _`the repository`: http://github.com/duilio/pelican-octopress-theme
.. _`Maurizio Sambati`: https://github.com/duilio
.. _`Geoffrey Lehée`: https://github.com/socketubs
.. _`Ekin Ertaç`: https://github.com/ekinertac
.. _`Jake Vanderplas`: https://github.com/jakevdp
.. _`Nicholas Terwoord`: https://github.com/nt3rp
.. _`Check the contributors`: https://github.com/duilio/pelican-octopress-theme/graphs/contributors
