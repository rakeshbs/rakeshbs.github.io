---
layout: post
title: A gem for Reliance Broadband
description: About my first gem
comments: true
keywords: "ruby gem, reliance login"
---

I use Reliance Broadband Internet connection.
Even though I use an unlimited 4mbps connection, I have to login through their web interface and it is annoying.

**So I created a gem. My first gem actually.**

**It's called login_reliance.**

You can install it using

    gem install login_reliance

After installing, you can run the gem using the command

    login_reliance

The first time you run the script, it will prompt you to enter the username and password. You can choose to save the login information in a file. The information will be stored in a file in the home directory.

Sometimes the connection is buggy and won't login on the first try. To keep looping till you are successfully logged in, you can use

    login_reliance -r

You can checkout the code at [https://github.com/rakeshbs/login_reliance](https://github.com/rakeshbs/login_reliance).
Feel free to modify and use it as you like.

