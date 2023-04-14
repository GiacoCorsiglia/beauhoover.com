# [beauhoover.com](https://beauhoover.com)

This website is hosted on [GitHub Pages](https://docs.github.com/en/pages) and is generated using [Jekyll](https://jekyllrb.com/docs/).  To create a new blog post, create a [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) file (`*.md`) in the `_posts` directory.  The file name should start with a date, formatted like `YYYY-MM-DD`.  To publish your blog post (or any other changes to the website), simply commit and push your changes to the `main` branch.  The changes should be reflected on the live website in a few minutes.

The home page of the website shows summaries of a few recent blog posts as well as a little blurb.  To customize the homepage, edit the `index.md` file in the root directory of this repository.  Similarly, there is an Archive page at [beauhoover.com/archive](https://beauhoover.com/archive) that lists every single post in reverse chronological order.

The other Markdown files in the root directory are other pages.  For example, `about.md` can be seen at [beauhoover.com/about](https://beauhoover.com/about).  Unlike blog posts (which live at `beauhoover.com/blog/*`), pages don't have a date, and won't be included in the list of recent posts.  You might link to pages in the navigation menu at the top of the website.  To control the contents of that menu, check out the `navigation_pages` option in the `_config.yml` file.  Publishing pages or any other changes works just like blog posts: commit and push to `main`.

There are a handful of other options in `_config.yml` that you might edit.  In general, the contents of that configuration can be read as `site.$variable_name` in the various `html` template files that can be found in `_layouts` and `_includes`.  To learn about the different files and folders inside this repo, check out [this page](https://jekyllrb.com/docs/structure/) in the Jekyll docs.  The `CNAME` file tells GitHub that the site lives at `beauhoover.com`.

This site uses a custom design, defined by the various `html` files as well as `assets/style.css`.  The CSS uses this nifty design system called ["Typesettings"](http://mikemai.net/typesettings/), but there is also a bit of customization at the bottom of the `style.css` file.  In particular, you can easily adjust the color scheme by editing the lines like `--ts-color-heading` in that file.  This site doesn't currently use a pre-made theme, but there are many such [themes for Jekyll](https://jekyllrb.com/resources/) available.

If you want to try out changes to the website without publishing them right away, you can run a version of the website on your own computer.  [Here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) are instructions for how to do so.

## Revealing the website to Google

This site is currently hidden from Google and other search engines via the `robots.txt` file.  Once you're ready, you should delete that file or otherwise edit it to indicate that search engines are allowed to index the site.  You can read about `robots.txt` [here](https://www.robotstxt.org/robotstxt.html).
