# IJHS ERP — update information

This repository holds **one small file**, `latest.json`, which records the version number of the
newest released build of the Infant Jesus High School ERP.

The app reads it to tell an administrator that a newer version exists. That is all it does.

**Nothing about the school is published here** — no student information, no school data, no source
code, and no settings. Only a version number. The application's source code is kept in a separate,
private repository.

## Publishing a new version

1. Release the new installer.
2. Edit `latest.json` and set `version` to the new version number.

That is the whole process — the app picks it up automatically.
