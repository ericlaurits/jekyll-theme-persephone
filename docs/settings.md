# Settings

A complete theme setting in your  `_config.yml` may seem like this:

```yml
title: Your Site Title
description: The description of your site.
email: your-email@address.com

author: Your name #  Default is your site title.

# Your social accounts.
social:
  github: github_username
  twitter: twitter_username
  facebook: facebook_username
  instagram: instagram_username
  linkedin: linkedin_username
  weibo: weibo_username

# Theme Settings

# Your site's logo. Will be shown on the left top of your page.
logo: /img/logo.svg
# If the images of our blog are strored in an external cloud. You can use the jekyll-img-prefix plugin and set your images' base url here.
img_prefix: https://your-img-cdn.com
# The rss link of your blog.
rss: "/feed.xml"

# The followings are settings for displays of your blog.
theme_setting:
  # The slides count in the slides layout. Default is 4.
  slides_count: 5
  # The ← back url on the top of your post page. Default is your site's home page.
  blog_page: "blog/index.md"
  # The url on your name on the bottom of your post and page. Default is your site's home page.
  about_page: "about.md"
  #  The url of the menu icon(which has three black lines). Willl be shown on the slides/book/chapter layouts It won't be shown if blank.
  archive_page: "archive.md"
  # The nav links on the top right of home/page/post/blog layout. You can set a local page(by setting a layout's path) or and external link ( both title and url are requied) here.
  nav_pages:
    - "about.md"
    -
      title: "External Link Title"
      url: "https://your-external-link.com"
  # Every default value in the following settings is false. You can set them globally here or seperatly in a single post/page/chapter.
  code: true # Code highlight.
  math: true # Mathjax
  mermaid: true # Mermaid
  #  Locales of this theme.
  lang:
    category_all: All # The first tag in the categories bar in the blog layout. By clicking it all of your posts will be shown. Default is 'All'.
    blog_title: Blog # The text of ← back url on the top of the post layout.  Default is 'Home'.
    # The locales of the comment controls.
    comment:
      user: "昵称"
      email: "邮箱"
      url: "链接"
      message: "说点什么吧..."
      reply: "回复"

head_code: |
  <!-- Extra codes in the head of your site pages. You can add your Google Analysis codes here! -->

# The settings of comments.
comment:
  enabled: true
  # The external url of your comments (See Staticman).
  postUrl:  https://api.staticman.net/v2/connect/GITHUB-USERNAME/GITHUB-REPOSITORY
# The settings of local smileys used in comments. The jekyll-smiley plugin is required.
smiley:
  enabled: true
  dir: img/smileys

```

Your can download the demo `_config.yml` file [here](/config.yml)