---
layout: post
section-type: post
has-comments: true
title: Setting up the Blog
category: tech
tags: ["tutorial"]
---

A website is truly personal if it hosts your blog as well, this place of the
internet where you can place your thoughts about anything. Let's see how you can
set up your Blog.

### Latest post preview in Index page

First of all, you get a preview of the latest post in the index, in order to
attract the visitor to visit your blog. The size of this preview is defined by:

```yaml
post-preview-words: 96
```

Feel free to experiment with different sizes, and pick the best for you.

### Archive

A blog is expected to host many posts, so you will need an archive with
pagination, which in a nutshell it's a grouping of your posts in pages, in
reverse chronological order. You can define the number of posts that are
displayed per page by changing:

```yaml
paginate: 5
```

### Share buttons

Many share buttons are available and can be enabled or disabled by setting the
following:

```yaml
email-share: True
fb-share: True
twitter-share: True
linkedin-share: True
reddit-share: True
tumblr-share: True
pinterest-share: True
pocket-share: True
vkontakte-share: True
```

### Comments

You can enable [Disqus](https://www.disqus.com) comments by just setting your
Disqus username here:

```yaml
disqus-shortname: "Your Disqus username"
```

### RSS feed

The RSS feed is automatically generated and placed in `/feed.xml`.

### Sitemap

The Sitemap is automatically generated and placed in `/sitemap.xml`.
