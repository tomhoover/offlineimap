[offlineimap]: https://github.com/OfflineIMAP/offlineimap
[website]: http://offlineimap.org
[wiki]: http://github.com/OfflineIMAP/offlineimap/wiki

# OfflineImap

## Description

OfflineIMAP is a software to dispose your e-mail mailbox(es) as a **local
Maildir**. OfflineIMAP will synchronize both sides via *IMAP*.

The main downside about IMAP is that you have to **trust** your MAIL provider to
not loose your mails. This is not something impossible while not very common.
With OfflineIMAP, you can download your Mailboxes and make you own backups of
the Maildir.

This allows reading your mails while offline without the need for the mail
reader (MUA) to support IMAP disconnected operations. Need an attachement from a
message without internet? It's fine, the message is still there.


## License

GNU General Public License v2.


## Why should I use OfflineIMAP?

* It is **fast**.
* It is **reliable**.
* It is **flexible**.
* It is **safe**.


## Downloads

You should first check if your distribution already package OfflineIMAP for you.
Downloads releases as [tarball or zipball](https://github.com/OfflineIMAP/offlineimap/tags).


## Feedbacks and contributions

**The user discussions, development, announces and all the exciting stuff take
place in the mailing list.** While not mandatory to send emails, you can
[subscribe here](http://lists.alioth.debian.org/mailman/listinfo/offlineimap-project).

Bugs, issues and contributions can be requested to both the mailing list or the
[official Github project][offlineimap].


## The community

* OfflineIMAP's main site is the [project page at Github][offlineimap].
* There is the [OfflineIMAP community's website][website].
* And finally, [the wiki][wiki].


## Requirements

* Python v2.7
* Python SQlite (optional while recommended)


## Documentation

All the current and updated documentation is at the [community's website][website].

### Dispose locally

You might want to dispose the documentation locally. Get the sources of the website.
For the other documentations, run the approppriate make target:
```
$ ./scripts/get-repository.sh website
$ cd docs
$ make html  # Require rst2html
$ make man   # Require a2x
$ make api   # Require sphinx
```
