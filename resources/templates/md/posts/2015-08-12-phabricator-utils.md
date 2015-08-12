{:title "Assign Phabricator reviewers based on module ownership"
 :layout :post
 :tags ["at-work", "code-review", "floss", "phabricator", "python", "traveloka"]}

At [Traveloka](https://www.traveloka.com/), Indonesia's leading travel
booking site, we use [Phabricator](http://phabricator.org/) for code
reviews - and as a growing company it might not be straightforward to
figure out who is knowledgeable about a particular part of the code
base and thus would be a good reviewer.

Inspired by Quora's
[Moving Fast With High Code Quality](https://engineering.quora.com/Moving-Fast-With-High-Code-Quality)
post, we are thus implementing a review routing system - the code is
live on GitHub at
[phabricator-utils](https://github.com/traveloka/phabricator-utils). It's
written in Python (hey, we're a Java/JS/Python shop), though we do
plan to contribute closer to the Phabricator codebase itself and that
will be in PHP.

Code is licensed under the Mozilla Public License version 2 - if you
find it useful, contribution is welcome!
