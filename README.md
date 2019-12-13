# bs
maybe a competitor to @lukesmithxyz's lb?

actually probably not but still


## what is this
this is a small lightweight static file bash blogging script, similar
to bb (bash blog) or lb (@lukesmithxyz's blogging script), that mainly
uses `sed` (lol idk how to use `awk` it would probably be better in this
situation)

you should probably use one of those, this one is bad lol, im just bored
and dont want my contributings on GitHub to be blank

**note**: `bs` is **only** a script for posting to a blog website, and
will not be able to edit/delete posts unless you do it manually. if you
would like those features, please use `lb` or `bashblog` instead.

**warning**: user input is supposed to be trusted, and is not sanitized. dont
connect some user interface to `bs` and expect it to be secure

## how to use it
edit stuff in `./settings` and then put a text file, with the name being the
title seperated with hyphens, into `./.drafts/` (or whatever you set it in
the settings file). then just run bs in a terminal and select what to post,
and it should post it

## intresting/weird things it does
there are some strange things it does that you would not expect
* it leaves temporary files in `/tmp/bs/` for every session, you might want
to clear that out after a while
* published drafts are hidden in the drafts folder, you might want
to also clear that out after a LONG time (like after a few years delete the
oldest half of published drafts or something)

