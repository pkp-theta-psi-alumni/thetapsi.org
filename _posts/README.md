# Posts

## Updating posts

Posts are how we keep the world updated about our chapter.
Anything can fit here as a 'post'. The more posts the better.

## Writing posts

Add a new file to the _posts/ directory. The filename should look like YYY-MM-DD-anything.md.
Jekyll uses this date format to set the data of publication.

Posts should be written in markdown. You can also write inline HTML too,
since Jekyll uses kramdown.

Note: After processing, Jekyll outputs all pages from the _posts directly
to the /posts directory (as raw HTMl).

## Font Matter

Make sure to add front matter to your file. As a post there's a few required fields.

```markdown
---
# Self descriptive - You don't need to add a title as part of your markdown content.
title: New Fall Members
# Last time the post was modified
last_modified_at: 2021-01-01T16:20:02-05:00
# Generally just use Blog
categories:
  - Blog
# Any additional content tags that make sense
tags:
  - Executive Council
---
```

## Liquid Templating

If you need to render data with conditions, iterations or other computation,
you can using Liquid tags.

```markdown
Today is {{"now" | date: "%b %d, %y"}}.
---
Today is Today is Sep 17, 18.
```
