---
layout: page
title: "Hello, QIICR Blog!"
teaser: "January 18, 2016: MLK day. Finally, snow in Boston. Updated qiicr.org."
header:
  image_fullwidth: harvard-yard-snow.jpg
categories:
  - web
  - outreach
---

Shame on us, but since the initial release, our web site has not seen a whole lot of new content.
There are several reasons to that. A lot of development was happening in the past two
years, but most of it was not ready to be advertised until very recently. At the same time,
the initial, very static version of our web-site was developed without any strategic thinking
put into facilitating its updates.

But all of this is now history. Over the last two days we have been rolling out an updated version of the QIICR web site!
The new site is designed to make it easier to update content, contribute blog posts, and provide improved
experience to the visitor. After considering several choices, I decided to use [Jekyll][1] as the content
delivery platform.

Here are some of the considerations for the choices made in the new incarnation of qiicr.org:

 * Web hosting is free and Jekyll support is included for Github hosted pages! No need to maintain a separate
CMS server, or deal with the severe restrictions of free public blog hosting such as Wordpress.com or Google Blog.
 * New content, such as blog posts or pages, can be contributed in [markdown format][2], and update to the web site
content is propagated via a pull request to the web site repository on github (for those who fret at the words "pull request", it is possible to [edit github content from the browser][3]).
 * Lots and lots of themes and templates are freely available (these are the collections I used as a resource: [http://themes.jekyllrc.org/][6] and [https://drjekyllthemes.github.io/][7]).
 * Site can be tested locally before being deployed.
 * All of the content is versioned and conveniently maintained in a github repository.
 * The site is now a lot better organized for integration with social media, google search services, embedding of video content.

Many things need to improve as we continue to customize and refine the web site content. Time will show if removing some technical obstacles will facilitate contribution of the new content to the QIICR home page, but
I feel hopeful and happy about this change!

Big thanks go to [@Phlow][5] for the [Feeling Responsive][4] theme, and to the Github support team for the
quick turnaround in resolving minor technical issues encountered while performing the site update!

[1]: https://jekyllrb.com/
[2]: http://daringfireball.net/projects/markdown/
[3]: http://www.markwk.com/2013/04/prose.io-content-editor-for-jekyll-sites.html
[4]: http://phlow.github.io/feeling-responsive/
[5]: https://github.com/Phlow
[6]: http://themes.jekyllrc.org/
[7]: https://drjekyllthemes.github.io/
