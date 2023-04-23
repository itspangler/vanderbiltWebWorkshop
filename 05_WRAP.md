---
title: 5. Parting thoughts
---

# Parting thoughts

By way of conclusion, here are some other points that you might return to as you consider how to build a personal website.

---

## Domain names

GitHub automatically generates a pretty crisp domain name, but if you want one that is truly your own, you unfortunately will have to pony up for it. I pay GoDaddy for my domain name. It's not terribly expensive, and they usually give you some kind of deal for the first year or two.

If you want to use a custom domain, you can still set everything up through GitHub as described so far; you'll just need to take the extra step of [configuring a custom domain for your GitHub pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## Search engine optimization

Once your website's published, you might notice that you have trouble getting it to the front page of Google. Search engine optimization, or the process of improving traffic to your site, can help with this. I did most of mine through Google's Search Console, and it seems to have worked alright. Here are some starting points:
1. [Getting started with Search Console](https://support.google.com/webmasters/answer/10267942?hl=en)
2. [Add a website property to Search Console](https://support.google.com/webmasters/answer/34592?hl=en)
3. [Verify your site ownership](https://support.google.com/webmasters/answer/9008080?hl=en)
4. [Build a sitemap](https://developers.google.com/search/docs/crawling-indexing/sitemaps/build-sitemap)
5. [Coding SEO into your site via HTML](https://html.com/seo/)

## Turnkey alternatives to building from scratch

### GitHub Pages + Jekyll

This guide was built using GitHub Pages and [Jekyll](https://jekyllrb.com/), a static site generator. Static site generators parse plain text files---often [Markdown](https://www.markdownguide.org/getting-started/) files, which are a bit more human readable and intuitive than HTML---as fully rendered HTML. This removes the need for you to fuss around with raw HTML and CSS. Thankfully, GitHub Pages integrates automatically with Jekyll, making it relatively easy to spin up a site like the one you're reading.

In addition to this one, GitHub Pages supports [twelve other themes](https://pages.github.com/themes/) out of the box. If you want to create your site using a Jekyll theme instead of Bootstrap, you can follow the [instructions on GitHub for getting started with GitHub Pages and Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll). You could even try [cloning this repo](https://github.com/itspangler/vanderbiltWebWorkshop), publishing it via GitHub Pages, and then remixing the content to suit your needs. Themes are set in the `_config.yml` file.

Note that Jekyll is not officially supported for Windows.

### WordPress, Wix, and SquareSpace

Where the GitHub Pages model is free, you'll need to pay a monthly rate for something like WordPress, Wix, or SquareSpace. They each have their pros and cons.

WordPress is the cheapest and most popular---something like 40% of the web is built on WordPress---but it's also a regular victim of security breaches and data leaks.

I've never used Wix or SquareSpace, so I'll refrain from advising on them. Just know that they are options.

---

# Return to Table of Contents