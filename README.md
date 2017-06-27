# mtremsal

Marc Tremsal's blog based on [Grav](http://getgrav.org/downloads)

# Deploying

```
vagrant ssh
cd /var/www/public
composer install --no-dev
exit
git add .
git commit -m "message"
git push
```

# Adding Functionality

You can download [plugins](http://getgrav.org/downloads/plugins) or [themes](http://getgrav.org/downloads/themes) manually from the appropriate tab on the [Downloads page on http://getgrav.org](http://getgrav.org/downloads), but the preferred solution is to use the [Grav Package Manager](http://learn.getgrav.org/advanced/grav-gpm) or `GPM`:

```
$ bin/gpm index
```

This will display all the available plugins and then you can install one or more with:

```
$ bin/gpm install <plugin/theme>
```

# Updating

To update Grav you should use the [Grav Package Manager](http://learn.getgrav.org/advanced/grav-gpm) or `GPM`:

```
$ bin/gpm selfupgrade
```

To update plugins and themes:

```
$ bin/gpm update
```

# Getting Started

* [What is Grav?](http://learn.getgrav.org/basics/what-is-grav)
* [Install](http://learn.getgrav.org/basics/installation) Grav in few seconds
* Understand the [Configuration](http://learn.getgrav.org/basics/grav-configuration)
* Take a peek at our available free [Skeletons](http://getgrav.org/downloads/skeletons)
* If you have questions, jump on our [Gitter Room](https://gitter.im/getgrav/grav)!
* Have fun!

# Exploring More

* Have a look at our [Basic Tutorial](http://learn.getgrav.org/basics/basic-tutorial)
* Dive into more [advanced](http://learn.getgrav.org/advanced) functions