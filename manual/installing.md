---
layout: default
title: 'Installing'
---

# Installing

## Compile and install from tarball

Download the latest tarball from the download page on Launchpad ([https://launchpad.net/gearmand](https://launchpad.net/gearmand)).

Once downloaded, run::

{% highlight bash %}
tar xzf gearmand-X.Y.tar.gz 
cd gearmand
./configure 
make 
make install
{% endhighlight %}


## Compile and install from source repository

The Bazaar version control system is required to check out the latest stable development source. To download and install, run::

{% highlight bash %}
bzr branch lp:gearmand 
cd gearmand 
./config/autorun.sh 
./configure 
make 
make install
{% endhighlight %}


## Platform specifics

* [Ubuntu]({{ site.url }}/manual/platform-specifics/ubuntu.html)
* [Fedora]({{ site.url}}/manual/platform-specifics/fedora.html)
* [Centos]({{ sutel.url}}/manual/platform-specifics/centos58.html)



