hooker
======

Hooker is an api request router.

E.g. you are using GitHub and MailGun and wish to get an email each time your repository is changed.

Both services have their APIs – GitHub Api and MailGun Api.

You register hooker in GitHub webhooks to get event created in hooker.

Then you register MailGun in hooker webhooks and subscribe it to github event, so hooker makes MailGun Api call each time GitHub triggers event.
