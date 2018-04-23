## Postmark + Firebase + Cloud Functions Tutorial

The following is some demo code that is included within [this blog post](https://postmarkapp.com/blog/sending-transactional-emails-via-firebase-and-cloud-functions).

### File structure

Here’s a quick structural overview of how this code is organized:

```
- functions
  - db
    - users
      - onUpdate.f.js
- public
  - admin
    - index.html
  - google-signin.png
  - index.html
```

### Requirements

We won’t cover the Firebase setup process in this tutorial. The [Firebase documentation](https://firebase.google.com/docs/web/setup) is excellent though. If you’re just getting started, you should definitely check it out. From this point forward I’ll assume that you have Firebase set up with [authentication](https://firebase.google.com/docs/auth/web/start), [real-time database](https://firebase.google.com/docs/database/web/start), and [Cloud Functions](https://firebase.google.com/docs/functions/get-started) up and running locally.
