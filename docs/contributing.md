---
layout: docs
title: Contributing
next_section: history
permalink: /docs/contributing/
---

So you've got an awesome idea to throw into OWNER.  
Great! 

There are many ways to help improving OWNER:

1. If you want to implement some change, you can 
   [fork the project on github][fork] then send me a pull request. 
   See the [workflow](#workflow).
2. If you have some idea, you can [submit it as change request][issues] on 
     github.
3. If you've found some defect, you can submit the bug on 
     [github issues][issues].
4. If you want to help the development, you can pick a 
     [bug or an enhancement][issues] then contribute your patches following 
     github [collaboration process][collaborating] (see also #1).
5. Also you can contribute on improving the documentation. Check out 
     the `gh-pages` branch. 
     See [Updating Documentation](#updating_documentation).

  [fork]: https://help.github.com/articles/fork-a-repo
  [issues]: https://github.com/lviggiano/owner/issues
  [collaborating]: https://help.github.com/categories/63/articles


And Please keep the following in mind:

* If you're creating a small fix or patch to an existing feature, just a simple
  test will do. Please stay in the confines of the current test suite.
* Also, some help on documentation on the gh-pages branch would be appreciated. 
  Great docs make a great project!
* Please follow the project code style.

<div class="note warning">
  <h5>Contributions will not be accepted without tests</h5>
  <p>
    If you’re creating a small fix or patch to an existing feature, just
    a simple test will do.
  </p>
</div>


Workflow
--------

Here's the most direct way to get your work merged into the project:

* Fork the project.
* Clone down your fork:

{% highlight bash %}
git clone git://github.com/<your-username>/owner.git
{% endhighlight %}

* Create a topic branch to contain your change:

{% highlight bash %}
git checkout -b my_awesome_feature
{% endhighlight %}


* Hack away, add tests. Not necessarily in that order.
* Make sure everything still passes by running `mvn test`.
* If necessary, rebase your commits into logical chunks, without errors.
* Push the branch up:

{% highlight bash %}
git push origin my_awesome_feature
{% endhighlight %}

* Create a pull request against lviggiano/owner and describe what your change
  does and the why you think it should be merged.

Updating Documentation
----------------------

We want the OWNER documentation to be the best it can be. We've
open-sourced our docs and we welcome any pull requests if you find it
lacking.

You can find the documentation for owner.aeonbits.org in the
[gh-pages branch](https://github.com/lviggiano/owner/tree/gh-pages) of
OWNER's repo on GitHub.com.

All documentation pull requests should be directed at `gh-pages`.  Pull
requests directed at another branch will not be accepted.

The [OWNER wiki](https://github.com/lviggiano/owner/wiki) on GitHub 
can be freely updated without a pull request as all GitHub users have access.