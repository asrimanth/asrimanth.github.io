+++
title = ""
date = 2024-09-15
draft = false

[taxonomies]
categories = ["Hello world! Where am I?"]
tags = ["firstpost", "website", "zola", "staticsite", "blog"]

[extra]
lang = "en"
toc = true
comment = true
copy = true
math = false
mermaid = false
outdate_alert = false
outdate_alert_days = 365
display_tags = true
truncate_summary = false
featured = false
+++

# Hello world! Where am I?

Hello world! This is my first blog post (and on my own website! 🎉). In this quick post, I will walkthorugh how I created a static site generator using zola.

<!-- more -->

## What is Zola?
Zola is a fast, lightweight static site generator written in Rust. It's designed to be simple to use, with everything you need built into a single binary. Zola uses Markdown for content creation and offers a powerful templating system.

## Why Zola and Serene?
Zola offers several advantages:

+ Speed: Zola is incredibly fast, generating sites in milliseconds.
+ Simplicity: With a single binary and straightforward configuration, it's easy to get started.
+ Flexibility: Zola's templating system allows for complex site structures.

The Serene theme provides:
+ Clean Design: A minimalist, content-focused layout
+ Responsive: Looks great on all devices
+ SEO-friendly: Built-in features to improve your site's search engine visibility

By combining Zola's power with Serene's elegant design, you can create a beautiful, fast, and easy-to-maintain static website. Happy blogging!

As you can see <a href="https://github.com/asrimanth/asrimanth.github.io/actions/workflows/publish_site.yml" target="_blank">here - publish_site.yml</a>, the build times are incredibly fast (~ 30 seconds 🚀), saving precious CI/CD hours.

## Build and Deploy
Once you're satisfied with your site:
+ Build: Run ```zola build``` to generate your static site. This will create a public directory with your compiled site.
+ Preview: Use ```zola serve``` to preview your site locally. This command will start a local server and automatically rebuild your site when changes are detected.
+ Deploy: Upload the contents of the public directory to your web host or use a service like GitHub Pages or Netlify for easy deployment. Serene provides deployment instructions for various platforms.

## Useful links
+ [zola - A fast static site generator in a single binary with everything built-in.](!https://github.com/getzola/zola)
+ [serene - A blog theme for zola, simple and clean](!https://github.com/isunjn/serene)
+ [serene/USAGE](!https://github.com/isunjn/serene/blob/latest/USAGE.md)
