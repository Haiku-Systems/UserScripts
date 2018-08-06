# User Scripts

An assortment of user scripts that are available via GreasyFork and can be installed with TamperMonkey.

These scripts add or enhance various front-end features of the following services:

* FollowUpBoss

## FollowUpBoss

Tasks in FollowUpBoss feature the following data points:

* Task Name
* Associated Contact (can't be explicitly set)
* Assigned Agent
* Due date/time

There is no room for a description or a link.

When the enhance-fub.user.js script is enabled, several things happen:

* If the task name contains data keys of the form {{.*}}, these are removed.
* If the task name contains a URL, it is extracted to a "More Info..." link positioned after the task name.
