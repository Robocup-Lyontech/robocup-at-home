---
permalink: /
title: Jekyll Minimalist
---
by [Roman Zolotarev](https://www.romanzolotarev.com/)

This website is a minimalist boilerplate powered by [GitHub Pages][pages].

**It is not a Jekyll theme**. 

The goal of this project is to demonstrate meaningful defaults of Jekyll,
GitHub Pages, and modern browsers. [Websites we build today look virtually
identical][jongold], but don't we want to stand out?

Create your [standalone website](https://www.romanzolotarev.com/standalone/) in
few minutes without installing anything or touching the command line. All you
need is your GitHub account (or email) and few minutes.

Build it from scratch. Make it unique. Design it for your needs. Express
yourself in HTML and CSS, but [do not overdo it][oatmeal], please. Make the web
diverse and clean place.

Read the source code of this website. It is just [three small files][source].

If you are looking for a theme, I would recommend

- [Minima](https://github.com/jekyll/minima) by Parker Moore, 
- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes) by Michael Rose.

## Quick Start

1. [View source of this site on GitHub][source].
1. Click on **Fork** button.
1. You may need to **Sign in** (or **Create an account**).
1. Go to **Settings** of your new repository and rename it to
   `USERNAME.github.io`, where `USERNAME` is your username on GitHub.
1. Check (on **Settings** page) that **GitHub Pages** is enabled.
1. Your site should be available at:

```
http://USERNAME.github.io/
```

## Add your pages

1. Click on **Create new file** in your new repository.
1. Type-in file name, e.g. `about.md`
1. Put some file content like this:

```
---
title: About
---

This site is clean and beautiful.
```

It is important to use front matter with `title` in every file. The new page
should be available at:

```
http://USERNAME.github.io/about
```

(based on its file name).

## Custom domain (optional)

Add `CNAME` file to your repository with your domain name. For example:

```
www.romanzolotarev.com
```

Then add `CNAME` record to DNS zone for your domain that points to
`USERNAME.github.io`. For example:

```
;; CNAME Records
www.romanzolotarev.com. 300 IN CNAME romanzolotarev.github.io.
```

Now your site should be available via your domain name. In case of those examples at:

```
http://www.romanzolotarev.com/
```

## Install on your computer (optional)

GitHub Pages uses Jekyll to do all this magic. If you are familiar with git,
then you may want to install GitHub Pages (with Jekyll) on your computer. So
you will be able to edit your pages locally (e.g. when you are offline) and
view your site locally before publishing.

For example to install on Mac run this command:

```
# Install bundler
gem install bundler

# and then jekyll plus jekyll-livereload
bundle install

# Start local server
bundle exec jekyll serve --livereload --increment
```

Then clone your repository and run Jekyll locally.

```
git clone https://github.com/USERNAME/USERNAME.github.io
cd USERNAME.github.io
jekyll serve -w
```

While Jekyll is running, open <http://localhost:4000/> in your browser. Your
site should be there. You can add and edit pages and Jekyll will automatically
regenerate HTML files, just reload the page in the browser to see changes.

[Learn more about Jekyll][jekyll].

[jekyll]: https://jekyllrb.com/docs/home/
[jongold]: https://mobile.twitter.com/jongold/status/694591217523363840
[md]: https://guides.github.com/features/mastering-markdown/
[pages]: https://pages.github.com/
[source]: https://github.com/romanzolotarev/jekyll-minimalist
[oatmeal]: http://theoatmeal.com/comics/design_hell
