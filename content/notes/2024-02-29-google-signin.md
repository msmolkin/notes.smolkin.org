---
title: 2024-02-29-google-signin
tags:
  - blog
---
Remember, to change your user account on any of the Google webpages that default to your main email (e.g. https://aistudio.google.com/app/waitlist/99999999?utm_source=smolkin.org), append `authuser=n`, replacing `n` with the number of your other account. The default account is 0, and it goes up in the order you signed in. For me, it's usually the following:
- 0 = main
- 1 = alternate, newer one
- 2 = school email
Standard disclaimers for using POST requests apply, e.g. make sure to add `?` before it if there isn't one already in the URL, or add `#` if there is already a `?` the

You can always try to add `u/n/`, again replacing n with the account number, right after the app name (e.g. mail.google.com/mail/u/1?utm_source=smolkin.org), but it might not work in all cases, depending on if the app was created according to what I presume to be Google's standard exposed-API practice.