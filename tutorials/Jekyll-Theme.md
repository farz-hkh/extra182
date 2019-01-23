---
layout: default
---

So now after all we've been through. We finally come to the theme where it all has to change. We don't want simple minima theme on our github pages do we. Now let's go change it.

# How to change your github pages theme
----

# Step 1
Take a look at your config.yml.

![images](https://raw.githubusercontent.com/farz-hkh/extra182/master/assets/images/th1.png)

See the line of theme there, we need to change that to something else, for an exmaple like below in github pages official theme.

![images](https://raw.githubusercontent.com/farz-hkh/extra182/master/assets/images/th2.png)

# Step 2
After that, we're gonna check our Gemfile and our Gemfile.lock, the Gemfile one you have to make sure to add

```
  gem "jekyll-theme-leap-day"
```

And in the Gemfile.lock, you have to make sure that you have

```
  jekyll-theme-leap-day (= 0.1.1)
  jekyll-theme-leap-day (0.1.1)
```

If you don't have it yet in your Gemfile.lock, either you bundle install first or add it manually. It's up to you to decide.

# Step 3
Now go to your localhost:4000, by using command

```
  bundle exec jekyll serve
```

![images](https://raw.githubusercontent.com/farz-hkh/extra182/master/assets/images/th3.png)

Now you can see we've already changed our github pages theme using jekyll.
