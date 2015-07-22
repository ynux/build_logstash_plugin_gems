# build_logstash_plugin_gems
Some Dockerfiles to build logstash plugin gems

## What I use it for
logstash 1.5 requires plugins to be gems. This is good, but getting the environment right to build a gem was an effort for me, so now I'm using docker. It works for plugins that are well prepared, like translate or math. 
One word of warning: This rvm stuff takes long.
And yes, I should build an image for the rvm environment, and then base the other two images on this.
