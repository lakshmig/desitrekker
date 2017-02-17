---
title:      How to add post
date:       2015-02-17 16:10:00
summary:    Click to know how to create a post
categories: how-to
---

 Find this file under `_posts` directory. Make a copy & change the content on the top which looks like

```
---
title:      Sample Post
date:       2015-02-17 16:10:00
summary:    Click to know how to create a post
categories: how-to
---
```

 Populate the content below it. This is markdown format file. Keep writing & for changing paragraph, just change line

```
this is first paragraph.

this is second.
```

 Copy images to `assets/images` directory & insert image in the post as below
 
 ```
 ![Image title](/assets/images/<image name>.jpg)
 ```

 Once you are done creating the post, add, commit & push to github

```
git add .
git commit -am "added xyz post"
git push origin master
```

Refresh desitrekker.com to see the new post getting appeared. To test changes locally, do

```
git clone https://github.com/lakshmig/desitrekker.git
cd desitrekker
bundle install
jekyll -s
```
The site then will be accessible at localhost:4000


