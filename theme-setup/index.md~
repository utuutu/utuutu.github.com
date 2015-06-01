---
layout: page
title: Theme Setup
modified: 2014-07-31T13:23:02.362000-04:00
excerpt: "Instructions on how to install and customize the Jekyll theme Minimal Mistakes."
image:
  feature: sample-image-3.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---

{% include _toc.html %}

## 1. 경기 규칙
---

---





## 2. 선수 소개

#### * 강민호

---
#### * 김태현

---
#### * 이승엽

---

## 3. 프로야구 팀 소개

#### * 팀 소개 1탄

---
#### * 팀 소개 2탄

---
#### * 팀 소개 3탄

---

## 4. 야구 어디까지 봤니?

#### * 금주의 선수

---
#### * 야구장을 여행하는 히치하이커를 위한 안내

---
#### * 거포본색 테이즈, 3연타석 홈런쇼

Used to generate absolute urls in `sitemap.xml`, `feed.xml`, and for generating canonical URLs in `<head>`. When developing locally either comment this out or use something like `http://localhost:4000` so all assets load properly. *Don't include a trailing `/`*.

Examples:

{% highlight yaml %}
url: http://mmistakes.github.io/minimal-mistakes
url: http://localhost:4000
url: //cooldude.github.io
url: 
{% endhighlight %}

#### Google Analytics and Webmaster Tools

Google Analytics UA and Webmaster Tool verification tags can be entered under `owner` in `_config.yml`. For more information on obtaining these meta tags check [Google Webmaster Tools](http://support.google.com/webmasters/bin/answer.py?hl=en&answer=35179) and [Bing Webmaster Tools](https://ssl.bing.com/webmaster/configure/verify/ownership) support.

### Navigation Links

To set what links appear in the top navigation edit `_data/navigation.yml`. Use the following format to set the URL and title for as many links as you'd like. *External links will open in a new window.*

{% highlight yaml %}
- title: Portfolio
  url: /portfolio/

- title: Made Mistakes
  url: http://mademistakes.com  
{% endhighlight %}

---

## Adding New Content with Octopress

While completely optional, I've included Octopress and some starter templates to automate the creation of new posts and pages. To take advantage of it start by installing the [Octopress](https://github.com/octopress/octopress) gem if it isn't already.

{% highlight bash %}
$ gem install octopress --pre
{% endhighlight %}

### New Post

Default command

{% highlight bash %}
$ octopress new post "Post Title"
{% endhighlight %}

Default works great if you want all your posts in one directory, but if you're like me and want to group them into subfolders like `/posts`, `/portfolio`, etc. Then this is the command for you. By specifying the DIR it will create a new post in that folder and populate the `categories:` YAML with the same value.

{% highlight bash %}
$ octopress new post "New Post Title" --dir posts
{% endhighlight %}

