# code-conf.com
www.code-conf.com

Conventions
---
Events are built up from partials. Let's say we have a dir `_events/1/2/3`. We start with a file named `_events/1/2/3/index.*` and then output all the files living in `_events/**/3/*`: only the last folder `3` has impact for filtering.
