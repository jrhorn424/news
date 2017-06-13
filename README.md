news
====

Post-Install
------------

Be sure to create an `authinfo` file as follows in the `spool-root`:

```
<username>
<password>
```

Run `slrn-list` to get a list of available newsgroups, and edit `slrnpull.conf`. Pull down news with `slrnpull` and then run `slrn --create` to update the `.jnewsrc` file in `$HOME`. Simply running `slrn` to read news will be sufficient afterward.

Suggested Reading
-----------------

* `man slrn`
* `man slrnpull`
* [Authentication](http://sourceforge.net/p/slrn/mailman/message/3657559/)

