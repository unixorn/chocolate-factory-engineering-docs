# Safely managing and manipulating data during an incident response

It's easy to get caught up in "fix it now NOW NOW" during an incident, especially when people are telling you "It costs $$$$$$ a minute while we're down." and start cutting corners.

That is what leads to unrecoverable data loss.

Here are some guidelines to keep in mind the next time you're working on data during an incident response (credit to a comment from @brentchapman on a slack):

* Set aside snapshots at each stage
* Try your changes first on a small subset of data, or on a copy
* Don’t assume your changes are going to work
* Don’t delete things, just move them aside
* Don’t do anything irreversible, especially when it comes to database updates
* Don’t overwrite data
* Include LIMIT statements in SQL commands
