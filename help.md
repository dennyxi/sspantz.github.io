_config.yml is discussed above; it provides basic settings information about your site, such as the site’s title and additional possibilities we won’t cover here, like how to structure links to posts (e.g. should they follow the pattern MySite.com/year/month/day/post-title?).
_includes folder has files that get included on all or certain pages (e.g. code to make the header contain your site title and main menu on every page of the site)
_layouts folder contains code that controls how the pages on your site look (default.html), as well as customizations of that code to further style blog posts (post.html) and pages (page.html)
_posts folder holds the individual files that each represent a blog post on your website. Adding a new post to this folder will make a new blog post appear on your website, in reverse chronological order (newest post to oldest). We’ll cover adding blog posts in the next section.
_sass folder holds SCSS files that control the visual design of the site
_site folder is where the HTML pages that appear on the web are generated and stored (e.g. you’ll write and save posts as Markdown files, but Jekyll will convert these to HTML for display in a web browser)
index.md is a place to add content that you want to appear on your homepage, such as a biography blurb to appear above the “Posts” list
about.md is an example of a Jekyll page. It’s already linked in the header of your website, and you can customize its text by opening and writing in that file. We’ll cover adding more site pages in the next section.
css folder holds CSS converted from SCSS that controls the visual design of the site
feed.xml lets people follow the RSS feed of your blog posts
index.html controls the structuring of content on your site’s homepage
