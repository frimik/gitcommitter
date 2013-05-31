gitcommitter
============

Git commit -a from cron ...

Usage
-----

Put in cron like this for example:

```
*/15 * * * * (cd /var/tmp && /root/gitcommitter /etc) >/dev/null
*/5 * * * * (cd /var/tmp && /root/gitcommitter /var) >/dev/null
```

You'll need to first init a repo, add files you want to track and also add the
remote to where it needs to push...
