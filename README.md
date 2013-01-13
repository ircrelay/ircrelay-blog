## IRCRelay Blog

To write a post, simply place a markdown file in:

    posts/*.md

The name will be the URL, preceeded by `posts/`

### Building

To build the site:

    bin/gostatic config

Optionally, you can specify a `-w` flag to watch and serve on a webserver.

    bin/gostatic config -w

You can now visit http://localhost:8000 to view the website.

### Deploying

    git push heroku master

The site will automatically rebuild and launch.
