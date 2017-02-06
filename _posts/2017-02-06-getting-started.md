---
layout: post
title: Getting started
---

# Getting started

To start, first fork the [repository](https://github.com/ankitrgadiya/proxima) or [download](https://github.com/ankitrgadiya/proxima/archive/master.zip) the zip file. If forked, clone the repository on your machine.

Then edit following fields in `_config.yml`:
* url
* name
* description
* google_verification [Optional]

Note: To test changes locally you'll need to install Jekyll and Bundler gem locally. Assuming that you have already installed Ruby.

```
$ gem install jekyll bundler
$ cd /path/to/repository/locally
$ bundle install
$ bundle exec jekyll serve
```
This will start a server locally which by default will listen in port 4000. To test open browser and go to [localhost:4000](localhost:4000).

# Posts

To add posts on the blog .md files following Jekyll posts [naming scheme](https://jekyllrb.com/docs/posts/#creating-post-files).
Basic post file looks like this:
```
---
layout: post
title: Sample post
---

Your article here
```

# Colors

To change colors on the template edit `_sass/_config.scss` file.

# Navigation

To edit navigation bar, edit `_data/navigation.yml` file.

# Deploy

Once you are satisfied by all the changes and added your articles locally, push changes to github.
