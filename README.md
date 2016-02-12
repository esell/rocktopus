Rocktopus is a re-work of my previous theme. The goal was to clean it up a bit and add in some of the newer Hugo features.
This theme uses the [Skeleton CSS framework](https://github.com/skeleton-framework/skeleton-framework)

![Theme screenshot](https://raw.githubusercontent.com/esell/rocktopus/master/images/screenshot.png)

![Theme screenshot dark](https://raw.githubusercontent.com/esell/rocktopus/master/images/screenshot-dark.png)

# Features
* Lightweight. All CSS and no javascript
* Choice of light or dark color scheme
* Configurable menu
* Supports tags
* Supports Hugo pagination
* Supports Hugo Google Analytics template
* Has an amazing name


# Configuration
The sample config file is pretty well documented and explains what setting does what but here are some key points:

* The `[menu]` section looks best with three entries (in my opinion).
* The `blogHeader` param supports HTML.
* The theme provides a content type of `contact` that will create a simple contact page for your based on the values you put in the config file. Just create a new file under your `content` and add `type="contact"` to the frontmatter, no need to put any actual content in it.
* There are some sample images that come with the theme for the header section but you'll probably want to set your own, just put it into your `static/img` directory update the filename in your config.

# Demo
You can see a live version of this template at [esheavyindustries.com](http://esheavyindustries.com)
