Grabber
---

(Name will probably change)

A simple (mostly) posix compliant shell script that checks if changes have been made to user-given urls, and uses [ntfy](https://github.com/dschep/ntfy) to send notifications.

Dependencies:
- wget
- md5sum
- ntfy

It mostly works for simple webpages with minimal dynamic content, but you can add patterns to be ignored when calculating the hashes.
