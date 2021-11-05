---
title: "Add Content to Pages Site"
date: 2021-11-05
categories: jekyll github
---
![monkey](./assets/happy-monkey.svg)
Main types of content are pages and posts. Pages are for standalone content not associated with specific date

## Add a new page
1. Go to root of your publishing source
2. Create a new file for your page _PAGENAME.md_
3. Add this to front matter. Replace _PAGETITLE_ with your page title. Replace _URLPATH_ with the path you want for your page url
4. If your base URL is `<username/github.io>` and your URLPATH is `/about/contact` then your page can be found at `<username/github.io>/about/contact`
```yaml
---
layout: page
title: "PAGETITLE"
permalink: /URLPATH/
---
```

## Add a new post
1. go to *_posts* directory
2. Create new file *YYYY-MM-DD-NAME-OF-POST.md*
3.  Add front matter
```
---
layout: post
title: "POSTITLE"
date: YYYY-MM-DD hh:mm:ss -0000
categories: CATEGORY-1 CATEGORY-2
---
```
4. Add your content after the front matter
