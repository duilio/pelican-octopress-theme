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

- ``GITHUB_USER``: (required to enable) username
- ``GITHUB_REPO_COUNT``: 5
- ``GITHUB_SKIP_FORK``: False
- ``GITHUB_SHOW_USER_LINK``: False

This theme also allows sharing via Twitter, Google Plus, and Facebook.  To
enable any of these, use the following settings:

- ``TWITTER_USER``: ['username'|'']
- ``GOOGLE_PLUS_ID``: ['id'|'']
- ``FACEBOOK_LIKE``: [True|False]

Extra twitter options: default values are shown

- ``TWITTER_WIDGET_ID``: (required to enable feed) ID obtained from `twitter settings <https://twitter.com/settings/widgets>`_
- ``TWITTER_TWEET_BUTTON``: ``False`` show twitter tweet button
- ``TWITTER_FOLLOW_BUTTON``: ``False`` show twitter follow button
- ``TWITTER_TWEET_COUNT``: ``3`` number of latest tweets to show
- ``TWITTER_SHOW_REPLIES``: ``'false'`` whether to list replies among latest tweets
- ``TWITTER_SHOW_FOLLOWER_COUNT``: ``'true'`` show number of followers

Extra google plus options: default values are shown

- ``GOOGLE_PLUS_ONE``: ``False`` show +1 button
- ``GOOGLE_PLUS_HIDDEN``: ``False`` hide the google plus sidebar link.

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

.. _`Pelican`: http://getpelican.com
.. _`Octopress`: http://octopress.org
.. _`my personal blog`: http://blogs.skicelab.com/maurizio/
.. _`the repository`: http://github.com/duilio/pelican-octopress-theme
.. _`Maurizio Sambati`: https://github.com/duilio
.. _`Geoffrey Lehée`: https://github.com/socketubs
.. _`Ekin Ertaç`: https://github.com/ekinertac
.. _`Jake Vanderplas`: https://github.com/jakevdp
.. _`Nicholas Terwoord`: https://github.com/nt3rp
