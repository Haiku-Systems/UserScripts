# User Scripts

An assortment of user scripts that are available via [GreasyFork](https://greasyfork.org/en/users/201424-haiku-systems-llc) and can be installed with [TamperMonkey](https://tampermonkey.net/).

These scripts add or enhance various front-end features of the following services:

* FollowUpBoss [[Install Script](https://greasyfork.org/en/scripts/370946-enhance-followupboss)]

## FollowUpBoss

Tasks in FollowUpBoss feature the following data points:

* Task Name
* Associated Contact (can't be explicitly set)
* Assigned Agent
* Due date/time

There is no room for a description or a link.

When the enhance-fub.user.js script is enabled, a couple of things happen:

* The Broker Machine adds data keys to tasks to facilitate lead flow processing. The keys look like this: {{TASK-1}}. If a task name contains such a data key, this script removes it.
* If the task name contains a URL, it is extracted to a "More Info..." link positioned after the task name.
