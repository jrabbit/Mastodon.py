Here's some general stuff to keep in mind, and some work that needs to be done

* Mastodon.py tries to work for python2 as well as python3, so avoid things like annotations,
  use requests over urllib, et cetera.

* Current TODOs:
    * Testing - test 2.3 stuff and verify it works: TODO: media updating
    * 2.4 support:
        * Document and add tests for webpush
        