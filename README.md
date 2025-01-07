# lbrss
a script that notifies you when a new letterboxd diary entry is logged by one of your friends using rss feeds

# Requirements
- `dunst`
- `notify-send`
- `xmlstarlet`
- `beep` _(optional)_

# Usage
first, in the script, change `baseDir` to wherever you'll put the config files and move everything except the script there.

in that location, make a `feeds` directory, where the rss feeds will be placed, and in the `users` file put names and urls to the rss feeds you want to follow in the format:

`<username>` (or optionally `<username>(<custom name>)`)

(name can be anything you want to show up the notification)

on first run, all the feeds will be added to the `feeds` directory.

after that, i recommend putting `lbrss` somewhere in your `PATH` and running it as a cronjob.
