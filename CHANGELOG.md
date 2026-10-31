# Changelog

## added/modified:

* 0.2.2: systemd-units runs without the secrets loaded, today's Garmin steps count ahead of UTC, unit paths are quoted, drills tidy up after themselves and mark each line once, and a malformed SMTP port is a failed delivery rather than a crash.
* 0.2.0: renamed from deadman-switch to datakrash; checks GitHub and Garmin for signs of activity on a systemd timer, challenges the owner for a password over ntfy when there are none, and messages the contact by email or SMS through the following week if the challenge fails.

## removed

* 0.2.0: the FastAPI server from the project template.
