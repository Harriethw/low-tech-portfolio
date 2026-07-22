# How to add a blog post

1. create a new html file in [../posts](.), copying the existing posts to include the `head` and metadata etc. Write the new content within the `<article>`.
1. update [rss.xml](../rss.xml) with a new `<item>` element, copying the existing post structure with a `<title>` `<link` and `<description>` (remember to update each one!)
1. add a new `<li>` element to [blog.html](../blog.html) above the existing elements, copying the existing ones if needed and changing the link etc.
1. enjoy your new blog post. 