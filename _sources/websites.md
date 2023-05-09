---
layout: episode
title: Hosting websites on GitHub Pages
teaching: 30
exercises: 0
questions:
  - How to serve a website using GitHub
---

# Hosting websites on GitHub Pages

You can host your personal homepage or group webpage
or project website on GitHub using
[GitHub Pages](https://pages.github.com/).

[GitLab](https://about.gitlab.com/features/pages/) and
[Bitbucket](https://confluence.atlassian.com/bitbucket/publishing-a-website-on-bitbucket-cloud-221449776.html)
also offer a very similar solution.

Unless you need user authentication or a sophisticated database behind your website,
[GitHub Pages](https://pages.github.com/) can be a very nice alternative
to running your own web servers.

Go back to your initial recipes repository, and let's go into Settings to tell GitHub how to make your repository into a website.

Now, let's add a new file call _config.yml.

Add the following text, and then commit the changes:

```
plugins:
  - jekyll-relative-links
relative_links:
  enabled: true
include:
  - README.md
  - guacamole.md
```

Now go to the Actions tab at the top of the page, to watch as GitHub builds and deploys your website.
