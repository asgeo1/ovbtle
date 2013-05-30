# ovbtle
### A svbtle-clone theme for octopress

## What is this?
So, I really like [svbtle](http://svbtle.com). It is clean, elegant, and concise.

What I *really* don't like about it though is the fact it is this 'ivory tower 
in a walled garden' of sorts. It has been said over and over again that the 
founder of svbtle, [Dustin Curtis](http://dcurt.is/) has always been very
protective of the little ecosystem he has made. And trust me: he has every right
to be! A lot of the content on there is very interesting and *extremely*
high-quality. However, the design is so gorgeous and jaw dropping (I'm a HUGE
fan of minimalism) it should be shared with the world, and so, here it is!

This is originally the work of [Orlando Del
Aguila](http://orlando.delagui.la/code/2013/03/10/svbtle-theme-for-jekyll.html) with just a few
modifications on top. Thank you Orlando! Be sure to go to his blog and give him
some well deserved kudos!

[View my personal site for a demo](http://devon.so)

## Requirements:
You need to have the following things defined in _config.yml:

<pre>
site.email
site.subscribe_rss
site.subtitle
site.title
site.twitter_user
site.url
</pre>

## Setup
1. Get into the root of your octopress.
2. Run the following:
<pre>
git clone git://github.com/dmizelle/ovbtle.git
bundle exec rake install['ovbtle']
bundle exec rake clean && bundle exec rake generate
</pre>
3. Change the picture at the following location to be a 300x300 circle of whatever you'd like. This will be the logo at the top left:
<pre>
source/assets/images/me.png
</pre>
4. Deploy as you usually do!
