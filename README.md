# efrantzparsons.com

## Cheat sheet

To add a new post:

1. Create a file in the `_posts` directory. The name should start with the date and end with a .md extension for markdown, for example: `2016-07-24-todays-underground-railroad.md`. Note that files with dates in the future won't show up on the site.

2. Open the file in a text editor or in github's editor.

3. Add a header. Most of this is stock information and shouldn't change from post to post other than the title. You can copy this or steal one from another file under _posts.

        ---
        layout: essay
        published: true
        title: DOCUMENT TITLE HERE
        category: posts
        ---

4. Insert the text. The site uses markdown, so you need to use its formatting rules. The basic rule is that you need two returns for a new paragraph. More rules for things such as lists can be found at the [Markdown Cheat Sheet](http://support.mashery.com/docs/read/customizing_your_portal/Markdown_Cheat_Sheet)

        This is paragraph one.

        This is paragraph two.

5. Save the file in github, and the page should be live.

## Sample full file - called `_posts/2016-07-24-test-file.md`

```
---
layout: essay
published: true
title: The Ku Klux Klan's Challenge to Black Lives Matter
category: posts
---

This is paragraph one.

This is paragraph two.

```

## front cover jekyll theme info

### Why choose this jekyll theme for your front page?
* You don't have to modify any HTML, everything can be modified in config.yml.
* Very lightweight. No Javascript, No Bootstrap etc..
* MIT licensed.


### See it in action
<a href="https://dashingcode.github.io/front-cover/">Live demo page</a>

### Credits
The background image that was used as an example comes from Tom Hall.
You can find it on <a href="https://flic.kr/p/pqEPBb">Flickr</a>.
It's licensed under Creative-Commons.

This theme makes use of the amazing <a href="http://fontawesome.io/">Font Awesome</a> icons.

