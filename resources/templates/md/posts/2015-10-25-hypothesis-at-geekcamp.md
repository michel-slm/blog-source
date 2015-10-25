{:title "Property-based Testing in Python with Hypothesis @ GeekCamp.ID"
 :layout :post
 :tags ["fedora", "floss", "presentations", "python", "testing"]}

Several months ago I discovered David R. MacIver's impressive
property-based testing library for Python,
[Hypothesis](https://hypothesis.readthedocs.org/). Having been a big
fan of Haskell's QuickCheck -- but not having much opportunity to use
Haskell in daily life -- this is hugely exciting. A mature
property-testing tool, targeting a popular dynamic language ... soon
afterwards I
[packaged this library for Fedora](https://apps.fedoraproject.org/packages/python-hypothesis/overview/)
-- fellow Fedora users can install it with a simple

```shell
dnf install python-hypothesis
```

or, to specify the Python interpreter explicitly,

```shell
dnf install python2-hypothesis
dnf install python3-hypothesis
```

The next step is obviously to evangelize this tool's adoption. After
trialing ("alpha testing") the subject at a work study session, and
beta testing it at a recent Python meetup (thanks guys!), the final
version of the presentation debuted at
[GeekCamp.ID](http://geekcamp.id) on October 24th.

Currently the
[slides](https://speakerdeck.com/michelslm/property-based-testing-in-python-with-hypothesis)
and
[examples](https://github.com/michel-slm/talk--property-based-testing--hypothesis)
used in the talk are available; will post the link to the video
recording here when it becomes available.

Do check them out if you are interested, and feel free to hit me with
any question on
[Google+](https://plus.google.com/+MichelAlexandreSalim) or
[Twitter](https://twitter.com/michel_slm)!
