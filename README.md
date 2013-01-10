Spree Showcase
===========

Spree Showcase is a simple extension that allows you to create the good ol' slideshow. The goal is to create a slideshow extension that makes things easy for the users and programmers. Minimal effort needed.

The secondary objective is to create a slideshow template that allows most types of JS slider to be implemented easily into Spree.

#### Screenshot of Frontend:
![Screenshot of Frontend](https://github.com/downloads/daemonsy/spree_showcase/in%20action.png)

#### Admin Backend:
![Screenshot of Backend](https://github.com/downloads/daemonsy/spree_showcase/Screen%20Shot%202012-05-09%20at%202.07.00%20AM.png)

Currently, this is the first iteration of the slideshow extension at v0.5.2. Contributors are greatly welcomed =)

**Next to come:**
- Adding sliders to different layout positions
- Enabling more options to be customized in the Admin Menu

Installation
=======
Get a clean Spree Installation

```rails new spree_demo```
```cd spree_demo```
```spree install```

**In Gemfile**

```gem 'spree_showcase' # Ruby Gems```

**After That**

```bundle install```
```rails g spree_showcase:install```

**Remember** to run ```rake assets:clean```, otherwise the javascript library might not be loaded.

Supports Spree 1.1 and 1.3

Testing
-------
No tests have been done yet. Use at your own risk!


Copyright (c) 2012 Damon Aw, released under the New BSD License.
[What is the BSD license anyway?]
